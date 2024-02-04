<template>
    <section>
        <div class="container">
          <div class="row g-0">
            <SeriesTemplate v-for="(series, index) in currentSeries" :key="index"
            :img="series.thumb"
            :series="series.series"
            :price="series.price"
            />

          </div>
        </div>
    </section>
</template>

<script>
  import SeriesTemplate from './SeriesTemplate.vue'
  import {currentSeries} from '../../data/data.js';
  // console.log(currentSeries[5].price)
  export default {
    name: 'MainContent',
    components: {
      SeriesTemplate
    },
    data(){
      return {
        currentSeries: currentSeries
      }
    },

    methods: {

    },

    computed: {

    }
  }
</script>

<style lang="scss" scoped>
    @use '../../assets/style/partials/variables' as *;

    section
    {
        background-color: $bg-main;
        color: $white;
        padding: 3rem 0;
    }

</style>