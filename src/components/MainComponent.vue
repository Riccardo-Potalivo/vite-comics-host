<template>
    <MainJumbotron/>
    <MainContent/>
</template>

<script>
  import MainJumbotron from './main/MainJumbotron.vue';
  import MainContent from './main/MainContent.vue';
  export default {
    name: 'MainComponent',
    components: {
      MainJumbotron,
      MainContent
    },
    data(){
      return {

      }
    },
    methods: {

    },
    computed: {

    }
  }
</script>

<style lang="scss" scoped>
  @use '../assets/style/partials/variables' as *;

</style>