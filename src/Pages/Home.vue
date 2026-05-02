<template>
    <div class="w-full min-h-screen  flex flex-col gap-10 ">
        <!-- hero-section -->
        <div class="w-full flex items-center justify-center relative h-screen rounded-4xl px-5 box-border ">
            <div style="background-image: url(https://i.pinimg.com/736x/f0/fc/2b/f0fc2b6b3a4ed4ca321fdecdd6b5fe98.jpg);"
                class="bg-black  w-full h-screen rounded-4xl  bg-cover bg-center ">
                <div class=" absolute  flex justify-center  items-center inset-x-5 inset-y-0 bg-black/40 rounded-4xl ">
                    <div class=" text-center flex flex-col items-center gap-5  justify-center text-white  hero-title">
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
        <div class="p-5 flex flex-row gap-8 ">
            <!-- col-1 -->
            <div class="w-[70%] ">
                <div style="background-image: url(https://i.pinimg.com/1200x/5d/2f/b8/5d2fb87f8c6aacb1d930e01e401f8a05.jpg
);" class="bg-black rounded-4xl bg-center bg-cover  h-screen flex flex-col items-start  justify-end ">
                    <div
                        class="flex flex-col items-start justify-start rounded-4xl text-black font-poppins capitalize ">
                        <span class="pr-6 pt-4 rounded-tr-lg  bg-white">
                            <h6 class="rounded-full border px-3 py-1 text-sm  ">gorgeous interior</h6>
                        </span>
                        <span class="pr-6 py-2 rounded-tr-lg bg-white">
                            <h6
                                class="font-bold text-6xl bg-linear-to-r from-black to-main text-transparent bg-clip-text  ">
                                Modern</h6>
                        </span>
                        <span class="pr-6 py-2 rounded-tr-lg bg-white">
                            <h6
                                class="font-bold text-6xl  bg-linear-to-r from-black to-main text-transparent bg-clip-text ">
                                Minimalist</h6>
                        </span>
                    </div>
                </div>
            </div>
            <!-- col-2 -->
            <div class="w-[30%] grid grid-rows-2 gap-6">

                <div
                    class="flex flex-col items-start justify-center gap-3 font-body  rounded-4xl bg-linear-120 from-black to-main text-white p-5">
                    <h6 class="rounded-full border px-3 py-1 text-sm  ">aesthetic</h6>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis labore doloribus recusandae </p>
                    <h2 class="font-heading capitalize text-4xl font-medium">
                        into a gallery of elegance
                    </h2>
                </div>
                <div style="background-image: url(https://i.pinimg.com/1200x/ac/61/19/ac61196521cec3df1e94987c0b176b79.jpg);"
                    class="rounded-4xl  bg-cover bg-center">

                </div>

            </div>
        </div>
        <!-- approach -->
        <div class="p-5">
            <div class=" w-full rounded-3xl bg-gray-100 px-6 py-20 grid grid-cols-2 ">
                <div class="flex flex-col gap-6 ">
                    <h1 class="font-heading text-5xl font-semibold ">Elevating Everyday Spaces</h1>
                    <p class="font-body font-normal text-sm text-gray-700 w-[86%]">Lorem ipsum dolor sit amet
                        consectetur adipisicing elit. <span class="font-semibold">Temporibus</span> quis voluptate vitae
                        eaque! Nostrum facilis minus, alias necessitatibus, <span class="font-semibold">maiores</span>
                        est beatae quaerat explicabo repudiandae</p>
                    <img :src="approach" class="opacity-95 brightness-75" alt="">
                </div>
                <!-- Material & Texture -->
                <!-- Lighting & Atmosphere -->
                <div class="flex flex-col gap-5 items-center justify-center px-12 w-[85%]">
                    <div
                        class="feature flex gap-4 bg-linear-to-t from-main to-black  hover:bg-black rounded-xl p-4 group">
                        <div class=" transition-all duration-300 ease-out">
                            <img src="https://i.pinimg.com/1200x/87/3f/89/873f8928e27c13c03bb5862951ddb09a.jpg"
                                class="rounded-lg aspect-square  transition-all duration-300 ease-out w-50 group-hover:scale-110 hover:transform-border border-2"
                                alt="">

                        </div>
                        <div class=" text-white flex flex-col  gap-1 items-start justify-center ">
                            <h3 class="font-heading font-medium text-2xl">Concept & Planning</h3>
                            <p class="font-body text-sm ">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                Laboriosam quas consequuntur </p>
                        </div>
                    </div>

                    <div class="feature flex gap-4 bg-black/85 rounded-xl p-5 ">
                        <div>
                            <img src="https://i.pinimg.com/1200x/87/3f/89/873f8928e27c13c03bb5862951ddb09a.jpg"
                                class="rounded-lg aspect-sqaure w-50" alt="">

                        </div>
                        <div class=" text-white flex flex-col gap-2">
                            <h3 class="font-heading font-medium text-2xl">Lorem, ipsum dolor.</h3>
                            <p class="font-body text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                Laboriosam quas consequuntur cumque?</p>
                        </div>
                    </div>
                    <div class="feature flex gap-4 bg-black/85 rounded-xl p-5 ">
                        <div>
                            <img src="https://i.pinimg.com/736x/ae/68/b6/ae68b669e2b0ce0174ab9a70980f4cf9.jpg"
                                class="rounded-lg aspect-sqaure w-50" alt="">

                        </div>
                        <div class=" text-white flex flex-col gap-2">
                            <h3 class="font-heading font-medium text-2xl">Lorem, ipsum dolor.</h3>
                            <p class="font-body text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                Laboriosam quas consequuntur cumque?</p>
                        </div>
                    </div>
                </div>
            </div>

        </div>
        <!-- project -->
        <div class=" px-5">
            <!-- heading -->
            <div class="flex flex-row gap-12  justify-between items-start w-full">
                <div class="w-[50%]">
                    <h2
                        class="font-bold font-heading text-5xl bg-linear-to-r from-black to-main text-transparent bg-clip-text ">
                        Explore Our Collection
                    </h2>

                </div>
                <div class="w-[40%]">
                    <p class="text-end font-body font-medium text-sm">
                        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum possimus atque dolores quasi
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. A
                    </p>

                </div>
            </div>

            <div class="grid grid-cols-4 gap-5 py-10 w-full min-h-screen">
                <!-- coloumn-1 -->
                <div class="flex flex-col h-full gap-3 ">
                    <div class=" h-[40%]  relative group overflow-hidden rounded-3xl">
                        <div style="background-image: url(https://i.pinimg.com/1200x/ac/61/19/ac61196521cec3df1e94987c0b176b79.jpg);"
                            class="w-full bg-cover bg-center rounded-3xl h-full group-hover:scale-105 transition transform duration-500 ease-in">
                        </div>
                        <div
                            class=" w-full h-auto hover:bg-black/30 ease-in duration-300 transition-all rounded-2xl bg-linear-to-t from-black/90 from-0% via-black/40 via-25% to-transparent to-30% absolute inset-0 flex items-end justify-between py-3 px-6">
                            <div class="transform translate-y-[65%] group-hover:translate-y-0 transition duration-300">
                                <div class="flex  justify-between items-center ">
                                    <h1 class="text-3xl font-projects font-semibold  text-white">Obsidian Living</h1>
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
                    <div class=" h-[60%]  relative group overflow-hidden rounded-3xl">
                        <div style="background-image: url(https://i.pinimg.com/1200x/d9/bc/a3/d9bca3639c17c89bff02fed826effd28.jpg);"
                            class="w-full bg-cover bg-center rounded-3xl h-full group-hover:scale-105 transition transform duration-500 ease-in">
                        </div>
                        <div
                            class=" w-full h-auto hover:bg-black/30 ease-in duration-300 transition-all rounded-2xl bg-linear-to-t from-black/90 from-0% via-black/40 via-25% to-transparent to-30% absolute inset-0 flex items-end justify-between py-3 px-6">
                            <div class="transform translate-y-[65%] group-hover:translate-y-0 transition duration-300">
                                <div class="flex  justify-between items-center ">
                                    <h1 class="text-3xl font-projects font-semibold  text-white"> Noir Nest</h1>
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
                </div>
                <!-- coloumn-2   -->
                <div class="flex flex-col col-span-2 h-full gap-3 ">
                    <div class=" h-[60%]  relative group overflow-hidden rounded-3xl">
                        <div style="background-image: url(https://i.pinimg.com/1200x/a3/1f/d3/a31fd30764e7b6c3652bbcf30be59db9.jpg);"
                            class="w-full bg-cover bg-center rounded-3xl h-full group-hover:scale-105 transition transform duration-500 ease-in">
                        </div>
                        <div
                            class=" w-full h-auto hover:bg-black/30 ease-in duration-300 transition-all rounded-2xl bg-linear-to-t from-black/90 from-0% via-black/40 via-25% to-transparent to-30% absolute inset-0 flex items-end justify-between py-3 ">
                            <div class="transform translate-y-1/2 group-hover:translate-y-0 transition duration-300">
                                <div class="flex  justify-between items-center w-full">
                                    <h1 class="text-3xl font-projects font-semibold  text-white"> Velvet Dusk Interiors
                                    </h1>
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
                    <!-- row-2 -->
                    <div class="h-[40%] flex  gap-5">
                        <div class=" w-full relative group overflow-hidden rounded-3xl">
                            <div style="background-image: url(https://i.pinimg.com/736x/1e/8b/5e/1e8b5e3b25be07a2114d891185a2263d.jpg);"
                                class="w-full bg-cover bg-center rounded-3xl h-full group-hover:scale-105 transition transform duration-500 ease-in">
                            </div>
                            <div
                                class=" w-full h-auto hover:bg-black/30 ease-in duration-300 transition-all rounded-2xl bg-linear-to-t from-black/90 from-0% via-black/40 via-25% to-transparent to-30% absolute inset-0 flex items-end justify-between py-3 px-6">
                                <div
                                    class="transform translate-y-[65%] group-hover:translate-y-0 transition duration-300">
                                    <div class="flex  justify-between items-center">
                                        <h1 class="text-3xl font-projects font-semibold text-white">Coal & Concrete</h1>
                                        <span class=" text-black bg-white rounded-full p-2 ">
                                            <ArrowUpRight
                                                class="hover:scale-125 transition-all ease-in duration-200 cursor-pointer" />
                                        </span>
                                    </div>
                                    <div class="opacity-0 group-hover:opacity-100 transition duration-300 mt-3">

                                        <p class="font-body text-white text-sm py-2 text-center">Lorem ipsum dolor sit
                                            amet, consectetur
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
                        <div class="w-full relative group overflow-hidden rounded-3xl">
                            <div style="background-image: url(https://i.pinimg.com/736x/e4/fe/01/e4fe01b5a543853d5e88e67e0ea0a27a.jpg);"
                                class="w-full bg-cover bg-center rounded-3xl h-full group-hover:scale-105 transition transform duration-500 ease-in">
                            </div>
                            <div
                                class=" w-full h-auto hover:bg-black/30 ease-in duration-300 transition-all rounded-2xl bg-linear-to-t from-black/90 from-0% via-black/40 via-25% to-transparent to-30% absolute inset-0 flex items-end justify-between py-3 px-6">
                                <div
                                    class="transform translate-y-[65%] group-hover:translate-y-0 transition duration-300">
                                    <div class="flex  justify-between items-center ">
                                        <h1 class="text-3xl font-projects font-semibold  text-white">The Ember House
                                        </h1>
                                        <span class="  text-black bg-white rounded-full p-2 ">
                                            <ArrowUpRight
                                                class="hover:scale-125 transition-all ease-in duration-200 cursor-pointer" />
                                        </span>
                                    </div>
                                    <div class="opacity-0 group-hover:opacity-100 transition duration-300 mt-3">

                                        <p class="font-body text-white text-sm py-2 text-center">Lorem ipsum dolor sit
                                            amet, consectetur
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
                    </div>
                </div>
                <div class="flex flex-col h-full gap-3 ">
                    <div class=" h-[40%]  relative group overflow-hidden rounded-3xl">
                        <div style="background-image: url(https://i.pinimg.com/736x/6c/3b/98/6c3b98387420fe48520ffec55e887aa6.jpg);"
                            class="w-full bg-cover bg-center rounded-3xl h-full group-hover:scale-105 transition transform duration-500 ease-in">
                        </div>
                        <div
                            class=" w-full h-auto hover:bg-black/30 ease-in duration-300 transition-all rounded-2xl bg-linear-to-t from-black/90 from-0% via-black/40 via-25% to-transparent to-30% absolute inset-0 flex items-end justify-between py-3 px-6">
                            <div class="transform translate-y-1/2 group-hover:translate-y-0 transition duration-300">
                                <div class="flex  justify-between items-center ">
                                    <h1 class="text-3xl font-projects font-semibold  text-white"> Ebon Space </h1>
                                    <span class="  text-black bg-white rounded-full p-2 ">
                                        <ArrowUpRight
                                            class="hover:scale-125 transition-all ease-in duration-200 cursor-pointer" />
                                    </span>
                                </div>
                                <div class="opacity-0 group-hover:opacity-100 transition duration-300 mt-3">

                                    <p class="font-body text-white text-sm py-2">Lorem ipsum dolor sit amet, consectetur
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
                    <div class=" h-[60%]  relative group overflow-hidden rounded-3xl">
                        <div style="background-image: url(https://i.pinimg.com/736x/05/4d/e6/054de67c4ed18ebfc5a6def03aa6c957.jpg);"
                            class="w-full bg-cover bg-center rounded-3xl h-full group-hover:scale-105 transition transform duration-500 ease-in">
                        </div>
                        <div
                            class=" w-full h-auto hover:bg-black/30 ease-in duration-300 transition-all rounded-2xl bg-linear-to-t from-black/90 from-0% via-black/40 via-25% to-transparent to-30% absolute inset-0 flex items-end justify-between py-3 px-6">
                            <div class="transform translate-y-1/2 group-hover:translate-y-0 transition duration-300">
                                <div class="flex  justify-between items-center ">
                                    <h1 class="text-3xl font-projects font-semibold  text-white">Midnight Haven </h1>
                                    <span class="  text-black bg-white rounded-full p-2 ">
                                        <ArrowUpRight
                                            class="hover:scale-125 transition-all ease-in duration-200 cursor-pointer" />
                                    </span>
                                </div>
                                <div class="opacity-0 group-hover:opacity-100 transition duration-300 mt-3">

                                    <p class="font-body text-white text-sm py-2">Lorem ipsum dolor sit amet, consectetur
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
                </div>


            </div>
        </div>

        <!-- stats section -->
        <div class="px-5 pb-12 grid grid-cols-2 gap-6">
            <div class="w-full  p-12 items-center gap-3 rounded-2xl  bg-linear-to-b from-black to-main text-gray-100 grid grid-cols-2">
<div class="flex flex-col gap-8 mb-16">
<div class=" border-gray-200/20 border rounded-2xl flex flex-col gap-3 p-4 bg-white/5 backdrop-blur-md transition duration-300 hover:bg-white/10">
    <div class="flex items-center gap-3">
        <PenTool class="text-white w-6 h-6 opacity-80"/>
        <h2 class="text-xl font-semibold ">Bespoke Concepts</h2></div>
    <P class="text-sm font-body  text-gray-300 leading-relaxed">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores necessitatibus t</P>
</div>
<div class=" border-gray-200/20 border rounded-2xl flex flex-col gap-3 p-4 bg-white/5 backdrop-blur-md transition duration-300 hover:bg-white/10">
    <div class="flex items-center gap-3">
        <PenTool class="text-white w-6 h-6 opacity-80"/>
        <h2 class="text-xl font-semibold ">Bespoke Concepts</h2></div>
    <P class="text-sm font-body  text-gray-300 leading-relaxed">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores necessitatibus t</P>
</div>
</div>
<div class="flex flex-col gap-8 mt-16">
<div class=" border-gray-200/20 border rounded-2xl flex flex-col gap-3 p-4 bg-white/5 backdrop-blur-md transition duration-300 hover:bg-white/10">
    <div class="flex items-center gap-3">
        <PenTool class="text-white w-6 h-6 opacity-80"/>
        <h2 class="text-xl font-semibold ">Bespoke Concepts</h2></div>
    <P class="text-sm font-body  text-gray-300 leading-relaxed">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores necessitatibus t</P>
</div>
<div class=" border-gray-200/20 border rounded-2xl flex flex-col gap-3 p-4 bg-white/5 backdrop-blur-md transition duration-300 hover:bg-white/10">
    <div class="flex items-center gap-3">
        <PenTool class="text-white w-6 h-6 opacity-80"/>
        <h2 class="text-xl font-semibold ">Bespoke Concepts</h2></div>
    <P class="text-sm font-body  text-gray-300 leading-relaxed">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores necessitatibus t</P>
</div>
</div>
            </div>
            <div class=" px-3 box-border w-full flex flex-col justify-end items-end-safe gap-4">
                <!-- heading -->
                <div class="flex flex-col items-end w-full gap-4 ">

                    <h2 class=" flex flex-wrap justify-end font-heading text-5xl font-semibold capitalize gap-x-4  leading-tight ">
                        <span class="text-center">Where Detail Shapes</span>
                        <div class="flex gap-4"><span class="italic  ">Meaningful</span> <img
                                class="w-40  h-20 object-cover  rounded-full"
                                src="https://i.pinimg.com/736x/db/48/75/db4875081f8248aa02d8420912fcf84e.jpg" alt="">
                        </div>
                        <span class="italic"> Design </span>
                    </h2>
                    <h6 class="capitalize font-body font-bold flex items-center gap-2 "><ArrowLeft class="w-5 text-black" /><span class=" h-[0.5px] bg-black w-50"></span>inside the process</h6>

                  <div class="flex items-end flex-row-reverse gap-3 ">  
                    <p class=" w-[65%] text-xs font-body  text-end">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde rem accusamus, fuga saepe aut eos optio repudiandae Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt enim facere architecto.
                    </p>
                <button class="px-6 py-2 cursor-pointer hover:bg-white hover:border-black border hover:text-black transition-all duration-300 ease-in
                 bg-black text-white rounded-full">Learn More</button></div>
                </div>
<!-- stat -->
 <div class="flex gap-4 py-6">
    <div class="flex flex-col items-center  gap-1 px-6 ">
        <h2 class="text-4xl font-bold font-projects">150+</h2>
        <p class="text-base font-medium">Curated Interiors</p>
    </div>
    <span class="w-[0.5px] h-5 bg-gray-400 flex self-center"></span>
 <div class="flex flex-col items-center  gap-1 px-6 ">
        <h2 class="text-4xl font-bold font-projects">50+</h2>
        <p class="text-base font-medium">Happy Customers</p>
    </div>
    <span class="w-[0.5px] h-5 bg-gray-400 flex self-center"></span>
    <div class="flex flex-col items-center  gap-1 px-6 ">
        <h2 class="text-4xl font-bold font-projects">10+</h2>
        <p class="text-base font-medium">Industry Expertise</p>
    </div>
 </div>
 <div class="w-full">
    <img class="rounded-2xl h-[280px] object-cover w-full" src="https://i.pinimg.com/1200x/e5/b0/c7/e5b0c7297721a4be2f3e258a3afc5587.jpg" alt="">
 </div>
            </div>

        </div>

    </div>



</template>

<script setup>
import { ArrowUpRight,ArrowLeft, PenTool } from 'lucide-vue-next';
import approach from '../assets/approach.png'
import gsap from 'gsap';
import { onMounted } from 'vue';

onMounted(() => {
    gsap.from(".hero-title", {
        y: -80, opacity: 0, duration: 1.2, ease: "power3.out"
    })
    gsap.from(".feature", {
        y: 100, opacity: 0, stagger: {
            each: 0.15, from: 'center'
        }, ease: "power3.out", duration: 1.2
    })
})
</script>

<style lang="scss" scoped></style>