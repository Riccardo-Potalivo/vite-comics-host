<template>
  <FooterTop/>
  <FooterMiddle/>
  <FooterBottom/>
</template>

<script>
    import FooterTop from './footer/FooterTop.vue';
    import FooterMiddle from './footer/FooterMiddle.vue';
    import FooterBottom from './footer/FooterBottom.vue';
  export default {
    name: 'FooterComponent',
    
    components: {
        FooterTop,
        FooterMiddle,
        FooterBottom
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