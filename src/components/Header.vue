<script setup lang="ts">
import { Slide } from 'vue3-burger-menu'

</script>

<template>
    <div class="container-fluid d-flex flex-wrap bg-black user-select-none w-100">
        <h1 class="text-white position-absolute top-50 start-50 translate-middle fw-bold">Docker</h1>
    </div>
    <Slide>
      <a id="home" href="#">
        <span>Home</span>
      </a>
    </Slide>
</template>

<style scoped>
    .container-fluid{
        height: 9vh
    }

</style>