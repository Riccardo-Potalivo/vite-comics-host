<template>
    <section>
        <div class="container d-flex justify-content-between">
            <div class="btn">SIGN-UP NOW!</div>
            <div class="d-flex align-items-center gap-3">
                <h4>FOLLOW US</h4>
                <img src="../../assets/img/footer-facebook.png" alt="facebook">
                <img src="../../assets/img/footer-twitter.png" alt="twitter">
                <img src="../../assets/img/footer-youtube.png" alt="youtube">
                <img src="../../assets/img/footer-pinterest.png" alt="pinterest">
                <img src="../../assets/img/footer-periscope.png" alt="periscope">
            </div>
        </div>
    </section>
</template>

<script>
  export default {
    name: 'FooterBottom',
    
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
        background-color: $bg-footer;
        color: white;
        padding: 2rem 0;
    }
    
    .btn
    {
        border: solid 2px $primary;
        border-radius: 0;
        color: $white;
        font-weight: 600;
        padding: 12px;
    }
    
    h4
    {
        margin: 0 1rem;
        color: $primary;
    }

    img
    {
        transition: 0.3s;

        &:hover
        {
            transform: scale(1.1);
        }
    }
    
</style>