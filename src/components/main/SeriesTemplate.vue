<script>
  export default {
    name: 'SeriesTemplate',
    props: {
        img: String,
        series: String,
        price: String
    }
  }
</script>

<template>
    <div class="col-6 col-md-4 col-lg-3 col-xxl-2 p-3">
      <div class="img_container">
        <img :src="img" :alt="series">
        <div class="series_price">
          <p>{{ price }}</p>
        </div>
      </div>
      <p class="mt-3">{{ series }}</p>
    </div>
</template>


<style lang="scss" scoped>
    @use '../../assets/style/partials/variables' as *;
    .img_container
    {
      width: 100%;
      aspect-ratio: 1;
      position: relative;
    }
    .img_container img
    {
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: top;
    }

    .series_price
    {
      position: absolute;
      height: 100%;
      background-color: #00000080;
      width: 100%;
      top: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      transition: 0.2s;
      opacity: 0;
      
      &:hover
      {
        opacity: 1;
      }
    }

</style>