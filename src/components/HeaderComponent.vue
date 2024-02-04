<template>
    <header>
        <nav class="container d-flex align-items-stretch justify-content-between py-3">

            <a class="navbar-brand" href="#">
                <img src="../assets/img/dc-logo.png" alt="logo">
            </a>

            <ul class="nav justify-content-end position-relative ">
              <li class="nav-item d-flex align-items-center position-relative" v-for="(el, index) in navEl" :key="index">
                <a class="nav-link active" :href="el.url">{{el.title}}</a>
                <div class="bt_bar"></div>
              </li>
            </ul>

        </nav>
    </header>
</template>

<script>
  import {navEl} from '../data/data.js';
  // import {obj} from '../data/data.js';
  export default {
    name: 'HeaderComponent',
    data(){
      // console.log(obj)
      return {
        navEl: navEl

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

  nav img
  {
    height: 80px;
  }

  a
  {
    font-family: 'Open Sans Condensed';
    color: $header-text;
    font-size: 0.9rem;
  }

  .bt_bar
  {

    display: none;
    width: 100%;
    border-top: solid 5px $primary;
    position: absolute;
    bottom: -1rem;
    
  }
  li:hover .bt_bar
  {
    display: block;
  }
  
  li:hover a
  {
    color: $primary;
  }
</style>