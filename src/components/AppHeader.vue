<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header class="container-fluid">
    <nav class="">
      <li><RouterLink to="/">Home</RouterLink></li>
      <li><RouterLink to="/about">About</RouterLink></li>
    </nav>
  </header>
</template>