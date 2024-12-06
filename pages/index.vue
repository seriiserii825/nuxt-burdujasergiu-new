<script setup lang="ts">
import Intro from '../components/sections/Intro.vue';


</script>
<template>
  <div class="home">
    <Intro />
    <!-- <Intro/> -->
    <!-- <section-header title="Обо мне" /> -->
    <!-- <About /> -->
    <!-- <section-header title="Последние посты" /> -->
    <!-- <div class="last-posts"> -->
    <!--   <blogs-component :posts="posts" align="center" /> -->
    <!--   <div class="last-posts__btn"> -->
    <!--     <btn> -->
    <!--       <router-link to="/blog">Посмотреть все посты</router-link> -->
    <!--     </btn> -->
    <!--   </div> -->
    <!-- </div> -->
    <!-- <section-header title="Последние работы порртфолио" /> -->
    <!-- <div class="last-portfolio"> -->
    <!--   <PortfoliosComponent -->
    <!--     v-if="portfolios &#38;&#38; portfolios.length" -->
    <!--     :portfolios="portfolios" -->
    <!--   /> -->
    <!-- </div> -->
  </div>
</template>

<style lang="scss">
.last-posts {
  padding: 10rem;
  &__btn {
    margin-top: 6rem;
    text-align: center;
  }
}
.last-portfolio {
  padding: 10rem;
}
</style>
