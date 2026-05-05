<script setup>
const year = new Date().getFullYear()
import { Icon } from '@iconify/vue';
</script>

<template>
    <div class="bg-black w-full py-16 px-12 text-white flex justify-between items-center">
        <div class="w-full">
        <h2 class="font-footer text-9xl w-full text-white uppercase leading-none ">spaceaura</h2>
        <p class="font-body capitalize">@{{year }} created By Santoshi</p>

        </div>
           <div class="text-3xl flex flex-col gap-1 ">
  <Icon icon="mdi:github"  />
    <Icon icon="mdi:gmail"  />
  <Icon icon="mdi:linkedin" />

    </div>
    </div>
 
</template>

<style scoped>
    
</style>