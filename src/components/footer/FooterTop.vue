<template>
    <section>
        <div class="container">
            <div class="container row justify-content-around    gy-4">
                <div class="col-12 col-md-auto center-block d-flex justify-content-center align-items-center gap-3">
                    <div class="img_box">
                        <img src="../../assets/img/buy-comics-digital-comics.png" alt="comics-digital">
                    </div>
                    <a href="#">DIGITAL COMICS</a>
                </div>
                <div class="col-12 col-md-auto d-flex justify-content-center align-items-center gap-3">
                    <div class="img_box">
                        <img src="../../assets/img/buy-comics-merchandise.png" alt="comics-merchandise">
                    </div>
                    <a href="#">DC MERCHANDISE</a>
                </div>
                <div class="col-12 col-md-auto  d-flex justify-content-center align-items-center gap-3">
                    <div class="img_box">
                        <img src="../../assets/img/buy-comics-subscriptions.png" alt="comics-subscriptions">
                    </div>
                    <a href="#">SUBSCRIPTION</a>
                </div>
                <div class="col-12 col-md-auto  d-flex justify-content-center align-items-center gap-3">
                    <div class="img_box">
                        <img src="../../assets/img/buy-comics-shop-locator.png" alt="shop-locator">
                    </div>
                    <a href="#">COMIC SHOP LOCATOR</a>
                </div>
                <div class="col-12 col-md-auto  d-flex justify-content-center align-items-center gap-3">
                    <div class="img_box">
                        <img src="../../assets/img/buy-dc-power-visa.svg" alt="shop-locator">
                    </div>
                    <a href="#">DC POWER VISA</a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
  export default {
    name: 'FooterTop',

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
        background-color: $primary;
        color: $white;
        padding: 3rem 0;
    }

    img
    {
        width: 100%;
        height: 100%;
        object-fit: contain;
    }

    .img_box
    {
        height: 60px;
        aspect-ratio: 1;
    }


    .gap-3
    {
        transition: 0.3s;

        &:hover
        {
            transform: scale(1.1);
        }
    }

</style>