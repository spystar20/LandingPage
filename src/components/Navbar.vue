<script setup>
import { XIcon, MenuIcon } from 'lucide-vue-next';
import { onMounted, ref } from 'vue';
import gsap from 'gsap';
const isOpen = ref(false)
onMounted(()=>{
    // const tl = gsap.timeline()
    gsap.from('.logo',{
        xPercent:-100,ease:'sine',duration:0.8,scale:0
    })
    gsap.from('.nav',{
                xPercent:100,ease:'sine',duration:0.8,scale:0

    })
})
</script>

<template>
    <div
        class="px-5 hidden md:flex justify-between items-center-safe text-gray-800 font-medium w-full  py-5 text-lg  capitalize ">
        <div>
            <h2 class="text-4xl font-bold text-main uppercase logo">spaceaura</h2>
        </div>
        <ul class="flex justify-center items-center gap-6 text-main font-body font-medium nav">
            <li
                class="px-5 py-1 rounded-full hover:border-main hover:bg-main  hover:text-white border-white border-2  hover:-translate-y-1 hover:ease-out duration-150 cursor-pointer ">
                <a>home</a></li>
            <li
                class="px-5 py-1 rounded-full hover:border-main hover:bg-main  hover:text-white border-white border-2  hover:-translate-y-1 hover:ease-out duration-150 cursor-pointer ">
                <a>about</a></li>
            <li
                class="px-5 py-1 rounded-full hover:border-main hover:bg-main  hover:text-white border-white border-2  hover:-translate-y-1 hover:ease-out duration-150 cursor-pointer ">
                <a>services</a></li>
            <li
                class="px-5 py-1 rounded-full hover:border-main hover:bg-main  hover:text-white border-white border-2  hover:-translate-y-1 hover:ease-out duration-150 cursor-pointer ">
                <a>contact</a></li>

        </ul>

    </div>
<div class="flex flex-col items-center justify-center relative">
    <div
        class="px-5 md:hidden flex justify-between items-center-safe text-gray-800 font-medium w-full  py-5 text-lg  capitalize ">

        <h2 class="text-4xl font-bold text-main uppercase">spaceaura</h2>
        <div @click="isOpen=!isOpen">
             <XIcon  v-if="isOpen"/>
        <MenuIcon v-else class="w-5 h-5" />
     
      </div>
    </div>
  
      <ul  :class="['bg-white w-full absolute top-18 z-[999] items-center flex flex-col gap-4  font-body text-lg py-6 font-medium duration-300 ease-in transition-all ',
      
      isOpen ? 
      'translate-y-0  opacity-100'
      :'-translate-y-12 opacity-0 pointer-events-none']" >
            <li class=" border-b">Home</li>
            <li>Home</li>
            <li>Home</li>
            <li>Home</li>
        </ul>

</div>
</template>



<style  scoped></style>