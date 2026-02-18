<template>
    <div class="w-full h-screen flex flex-col gap-10">
        <!-- hero-section -->
        <div class="w-full flex items-center justify-center relative h-screen rounded-4xl ">
            <div style="background-image: url(https://i.pinimg.com/736x/f0/fc/2b/f0fc2b6b3a4ed4ca321fdecdd6b5fe98.jpg);"
                class="bg-black w-full h-screen rounded-4xl  bg-cover bg-center ">
                <div class="absolute flex justify-center  items-center inset-0 bg-black/40 rounded-4xl">
                    <div class=" text-center flex flex-col items-center gap-5  justify-center text-white  ">
                        <h2 class="font-semibold font-heading text-5xl capitalize ">Designed Around Your <span
                                class="italic bg-linear-to-r from-white to-main text-transparent bg-clip-text  ">Comfort</span>
                        </h2>
                        <p class="font-body text-sm normal-case w-1/2 ">Lorem ipsum, dolor sit amet consectetur
                            adipisicing elit. Obcaecati animi explicabo maiores placeat labore alias, a error quis, qui
                            quia quas.</p>
                        <div>
                            <button
                                class=" border border-white hover:text-white   hover:bg-[#645a4e] hover:border-main font-body font-medium px-8 py-3 rounded-lg cursor-pointer hover:scale-105 scale-100 ease-linear duration-150">Get
                                Started</button>
                        </div>
                    </div>

                </div>

            </div>
        </div>
        <!-- about -->
        <div class="py-5 flex flex-row gap-8">
            <!-- col-1 -->
            <div class="w-[70%]">
                <div style="background-image: url(https://i.pinimg.com/1200x/5d/2f/b8/5d2fb87f8c6aacb1d930e01e401f8a05.jpg
);"
                    class="bg-black rounded-4xl bg-center bg-cover h-screen flex flex-col items-start  justify-end">
                    <div class="flex flex-col items-start justify-start rounded-4xl text-black font-poppins capitalize ">
                        <span class="pr-6 pt-4 rounded-tr-lg  bg-white"><h6 class="rounded-full border px-3 py-1 text-sm  ">gorgeous interior</h6></span>
                        <span class="pr-6 py-2 rounded-tr-lg bg-white"><h6 class="font-bold text-6xl bg-linear-to-r from-black to-main text-transparent bg-clip-text  ">Modern</h6></span>
                          <span class="pr-6 py-2 rounded-tr-lg bg-white"><h6 class="font-bold text-6xl  bg-linear-to-r from-black to-main text-transparent bg-clip-text ">Minimalist</h6></span>
                    </div>
                </div>
            </div>
            <!-- col-2 -->
            <div class="w-[30%] grid grid-rows-2 gap-6">

<div class="flex flex-col items-start justify-center gap-3 font-body  rounded-4xl bg-linear-120 from-black to-main text-white p-5">
<h6 class="rounded-full border px-3 py-1 text-sm  ">aesthetic</h6>
<p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis labore doloribus recusandae </p>
<h2 class="font-heading capitalize text-4xl font-medium">
    into a gallery of elegance
</h2>
</div>
<div style="background-image: url(https://i.pinimg.com/1200x/ac/61/19/ac61196521cec3df1e94987c0b176b79.jpg);" class="rounded-4xl  bg-cover bg-center">

</div>

            </div>
        </div>

        <!-- project -->
         <div class="py-5  ">
            <!-- heading -->
     <div  class="flex flex-row  justify-between items-start w-full">
        <div class="w-full">
        <h2  class="font-bold font-heading text-5xl bg-linear-to-r from-black to-main text-transparent bg-clip-text ">
Explore Our  Collection
        </h2>
         
        </div>
        <div class="flex flex-col items-end justify-center gap-4">
            <p class="text-end font-body font-medium text-sm">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum possimus atque dolores quasi Lorem ipsum dolor sit amet consectetur adipisicing elit. A
            </p>
           
        </div>
     </div>
     <div class="grid grid-cols-4 ">
     
  <div class="col-span-1 relative">
    <div>
    <img src="https://i.pinimg.com/1200x/24/0f/02/240f02d6bf3f0c363907d28fc7ffd670.jpg" alt="">

    </div>
    <div class="absolute inset-0 bg-linear-120 from-black to-main opacity-10 hover:opacity-0 ease-in duration-200"> </div>
   <div class=" flex">
        <h2 class="text-white text-3xl absolute bottom-8">Project 1</h2> <span class="text-white text-2xl"><MdArrowOutward />
</span>
    </div>
  </div>      
  
    
      
     </div>
    
         </div>
    </div>
</template>

<script setup>
import { MdArrowOutward } from "react-icons/md";

</script>

<style lang="scss" scoped></style>