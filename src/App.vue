<script setup>
//import { RouterLink, RouterView } from 'vue-router'

import {RouterView} from 'vue-router'
import BlogHeader from '@/views/BlogHeader.vue'
import Jumbo from '@/views/JumboHeader.vue'
</script>

<template>
  <!--  <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>-->
<div class="container">
  <BlogHeader></BlogHeader>
  <Jumbo title="My Title" desc="csmju Drop tomorrow"></Jumbo>
  <div class="main">
    <RouterView />
  </div>
  <div class="footer"></div>
</div>
</template>

<style scoped></style>
