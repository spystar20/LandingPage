<script setup>
import { ArrowUpRight } from 'lucide-vue-next';

defineProps({
    project:Object
})
</script>
<template >
 
        <div    :style="{ height: project.height }"
 class="   relative group overflow-hidden rounded-3xl">
                        <div :style='{backgroundImage: `url(${project.img})`}'
                            class="w-full bg-cover bg-center rounded-3xl h-full group-hover:scale-105 transition transform duration-500 ease-in">
                        </div>
                        <div
                            class=" w-full h-auto hover:bg-black/30 ease-in duration-300 transition-all rounded-2xl bg-linear-to-t from-black/90 from-0% via-black/40 via-25% to-transparent to-30% absolute inset-0 flex items-end justify-between py-3 px-6">
                            <div class="transform translate-y-[65%] group-hover:translate-y-0 transition duration-300">
                                <div class="flex  justify-between items-center ">
                                    <h1 class="text-3xl font-projects font-semibold  text-white">{{ project.title }}</h1>
                                    <span class="  text-black bg-white rounded-full p-2 ">
                                        <ArrowUpRight
                                            class="hover:scale-125 transition-all ease-in duration-200 cursor-pointer" />
                                    </span>
                                </div>
                                <div class="opacity-0 group-hover:opacity-100 transition duration-300 mt-3">

                                    <p class="font-body text-white text-sm py-2 text-center">Lorem ipsum dolor sit amet,
                                        consectetur
                                        adipisicing elit. Cumque magni alias ipsam?</p>
                                    <!-- buttons -->
                                    <div class="flex items-center justify-center  gap-3 py-2 w-full">
                                        <button
                                            class="px-4 py-0.5 text-white border border-white rounded-full capitalize hover:bg-white/5 hover:scale-95 ease-in transition-all duration-100 cursor-pointer">view</button>
                                        <button
                                            class="px-4 py-0.5 text-white border border-white rounded-full capitalize hover:bg-white/5 hover:scale-95 ease-in transition-all duration-100 cursor-pointer">contact</button>
                                        <button
                                            class="px-4 py-0.5 text-white border border-white rounded-full capitalize hover:bg-white/5 hover:scale-95 ease-in transition-all duration-100 cursor-pointer">learn</button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
    
</template>

<style scoped>
    
</style>