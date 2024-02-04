<template>
    <section>
        <div class="container position-relative ">
            <div class="main_title">
              <h2 class="m-0">CURRENT SERIES</h2>
            </div>
        </div>
    </section>
</template>

<script>
  export default {
    name: 'MainJumbotron',
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
    @use '../../assets/style/partials/variables' as *;

    section
    {
        background-image: url(../../assets/img/jumbotron.jpg);
        background-size: cover;
    }
    .container
    {
        height: 25rem;
    }

    .main_title
    {
      background-color: $primary;
      color: $white;
      display: inline-block;
      padding: 0.5rem 2rem;
      position: absolute;
      bottom: 0;
      transform: translate(0, 50%);
    }

</style>