<template>
    <div id="MainLayout" class="w-full fixed z-50 backdrop-blur-md border-t-2 border-[#fbbf24] ">

        <div 
            id="TopMenu"
            class="w-full bg-[#f78a23]"
        >
            <ul 
                class="
                    flex 
                    items-center 
                    justify-end
                    text-sm
                    text-[#ffffff]
                    font-light 
                    px-2 
                    h-10
                    bg-[#f78a23]
                    max-w-[1200px] 
                "
            >
            <h1>CATÁLOGO DE PRODUTOS DIRETO DA FÁBRICA</h1>
              <!--  <li class="border-r border-r-gray-400 px-3 hover:text-[#f59e0b] cursor-pointer">
                    Ajuda
                </li>
                <li class="border-r border-r-gray-400 px-3 hover:text-[#f59e0b] cursor-pointer">
                    Site seguro
                </li>
                <li 
                class="border-r border-r-gray-400 px-3 hover:text-[#f59e0b] cursor-pointer"
                >
                    <Icon name="ph:user-thin" size="17"/>
                    Conta
                    <Icon name="mdi:chevron-down" size="15" class="ml-5"/>

                </li>-->
            </ul>
        </div>


<div 
    id="MainHeader" 
    class="flex items-center w-full bg-[#7b0000]"
>
        <div class="flex  justify-between gap-10 max-w-[1150px] w-full px-3 py-0 mx-auto">

                <NuxtLink to="/" class="top-0 bottom-0 left-200 min-w-[170px]">
                    <img 
                        class="absolute top-2"
                        width="120"
                        src="/logo.png"
                    >
                </NuxtLink>



<nav class=" border-gray-200 dark:bg-gray-900">
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">

    <button data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-orange-500 rounded-lg md:hidden  focus:outline-none focus:ring-2    " aria-controls="navbar-default" aria-expanded="false">
        <span class="sr-only">Open main menu</span>
        <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
        </svg>
    </button>
    <div class="hidden w-full md:block md:w-auto  " id="navbar-default">
      <ul class="font-medium flex flex-col p-4 md:p-0 mt-4 rounded-lg  md:flex-row md:space-x-8 rtl:space-x-reverse ">
 
        <li>
            <button type="button" @click="navigateTo('/')" class="text-white font-medium rounded-lg text-2xl px-1 py-.5 text-center">Início</button>
        </li>

        <li>
            <a type="button" href="https://wa.me/5511998905016?text=Oi, gostaria de mais informações!"  class="text-white font-medium rounded-lg text-2xl px-1 py-.5 text-center" target="_blank">Whatsapp</a>
        </li>

      </ul>
    </div>
  </div>
</nav>





        </div>


</div>


    </div>


                    <!-- Modal toggle 1 -->


        <!-- Main modal -->
        <div id="default-modal1" tabindex="-1" aria-hidden="true" class="hidden overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 justify-center items-center w-full md:inset-0 h-[calc(100%-1rem)] max-h-full">
            <div class="relative p-4 w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
                    <!-- Modal header -->
                    <div class="flex items-center justify-center p-4 md:p-5 border-b rounded-t dark:border-gray-600">
                        <div class="w-full flex items-center justify-center py-5 bg-blue-900">
                            <NuxtLink to="/" class="min-w-[170px]">
                                <img width="170" src="/logo.png">
                            </NuxtLink>
                            <button type="button" class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 ms-auto inline-flex justify-center items-center dark:hover:bg-gray-600 dark:hover:text-white" data-modal-hide="default-modal1">
                                    <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14">
                                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"/>
                                    </svg>
                                <span class="sr-only">Close modal</span>
                            </button>
                        </div>

                    </div>
                    <!-- Modal body -->
                    <div class="p-4 md:p-5 space-y-4">
                        <h3 class="text-center leading-relaxed text-gray-500 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                            Plotagem Total
                        </h3>
                        <p class="text-center leading-relaxed text-gray-500 dark:text-gray-400">
                            Plotagem cobre todo o veículo, ótima opção para preservação da lataria e customização
                            com aplicação minuciosa e profissional.
                        </p>
                    </div>
                    <!-- Modal footer -->
                    <div class="flex items-center p-4 md:p-5 border-t border-gray-200 rounded-b dark:border-gray-600">
                        <a  href="https://api.whatsapp.com/send?phone=5511995103964&text=Olá, estou interessado em fazer um orçamento de plotagem total para meu veículo ou frota." target="_blank" data-modal-hide="default-modal1" type="button" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">
                            Solicitar orçamento</a>
                    </div>
                </div>
            </div>
        </div>
        


                            <!-- Modal toggle 2 -->


        <!-- Main modal -->
        <div id="default-modal2" tabindex="-1" aria-hidden="true" class="hidden overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 justify-center items-center w-full md:inset-0 h-[calc(100%-1rem)] max-h-full">
            <div class="relative p-4 w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
                    <!-- Modal header -->
                    <div class="flex items-center justify-center p-4 md:p-5 border-b rounded-t dark:border-gray-600">
                        <div class="w-full flex items-center justify-center py-5 bg-blue-900">
                            <NuxtLink to="/" class="min-w-[170px]">
                                <img width="170" src="/logo.png">
                            </NuxtLink>
                            <button type="button" class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 ms-auto inline-flex justify-center items-center dark:hover:bg-gray-600 dark:hover:text-white" data-modal-hide="default-modal2">
                                    <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14">
                                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"/>
                                    </svg>
                                <span class="sr-only">Close modal</span>
                            </button>
                        </div>

                    </div>
                    <!-- Modal body -->
                    <div class="p-4 md:p-5 space-y-4">
                        <h3 class="text-center leading-relaxed text-gray-500 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                            Plotagem Parcial                         
                        </h3>
                        <p class="text-center leading-relaxed text-gray-500 dark:text-gray-400">
                            Plotagem cobre até 70% do veículo, customização adaptada sobre medida e aplicação profissional.                         
                        </p>
                    </div>
                    <!-- Modal footer -->
                    <div class="flex items-center p-4 md:p-5 border-t border-gray-200 rounded-b dark:border-gray-600">
                        <a  href="https://api.whatsapp.com/send?phone=5511995103964&text=Olá, estou interessado em fazer um orçamento de plotagem parcial para meu veículo ou frota." target="_blank" data-modal-hide="default-modal2" type="button" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">
                            Solicitar orçamento</a>
                    </div>
                </div>
            </div>
        </div>






         <!-- Modal toggle 3 -->


        <!-- Main modal -->
        <div id="default-modal3" tabindex="-1" aria-hidden="true" class="hidden overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 justify-center items-center w-full md:inset-0 h-[calc(100%-1rem)] max-h-full">
            <div class="relative p-4 w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
                    <!-- Modal header -->
                    <div class="flex items-center justify-center p-4 md:p-5 border-b rounded-t dark:border-gray-600">
                        <div class="w-full flex items-center justify-center py-5 bg-blue-900">
                            <NuxtLink to="/" class="min-w-[170px]">
                                <img width="170" src="/logo.png">
                            </NuxtLink>
                            <button type="button" class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 ms-auto inline-flex justify-center items-center dark:hover:bg-gray-600 dark:hover:text-white" data-modal-hide="default-modal3">
                                    <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14">
                                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"/>
                                    </svg>
                                <span class="sr-only">Close modal</span>
                            </button>
                        </div>

                    </div>
                    <!-- Modal body -->
                    <div class="p-4 md:p-5 space-y-4">
                        <h3 class="text-center leading-relaxed text-gray-500 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                            Fachada                         
                        </h3>
                        <p class="text-center leading-relaxed text-gray-500 dark:text-gray-400">
                            Planejamento e construção de fachada para empresa.                         
                        </p>
                    </div>
                    <!-- Modal footer -->
                    <div class="flex items-center p-4 md:p-5 border-t border-gray-200 rounded-b dark:border-gray-600">
                        <a  href="https://api.whatsapp.com/send?phone=5511995103964&text=Olá, estou interessado na criação de um projéto para a construção da fachada da minha empresa." target="_blank" data-modal-hide="default-modal3" type="button" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">
                            Solicitar orçamento</a>
                    </div>
                </div>
            </div>
        </div>







                <!-- Modal toggle 4 -->


        <!-- Main modal -->
        <div id="default-modal4" tabindex="-1" aria-hidden="true" class="hidden overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 justify-center items-center w-full md:inset-0 h-[calc(100%-1rem)] max-h-full">
            <div class="relative p-4 w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
                    <!-- Modal header -->
                    <div class="flex items-center justify-center p-4 md:p-5 border-b rounded-t dark:border-gray-600">
                        <div class="w-full flex items-center justify-center py-5 bg-blue-900">
                            <NuxtLink to="/" class="min-w-[170px]">
                                <img width="170" src="/logo.png">
                            </NuxtLink>
                            <button type="button" class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 ms-auto inline-flex justify-center items-center dark:hover:bg-gray-600 dark:hover:text-white" data-modal-hide="default-modal4">
                                    <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14">
                                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"/>
                                    </svg>
                                <span class="sr-only">Close modal</span>
                            </button>
                        </div>

                    </div>
                    <!-- Modal body -->
                    <div class="p-4 md:p-5 space-y-4">
                        <h3 class="text-center leading-relaxed text-gray-500 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                           Lertra Caixa Luminoso                         
                        </h3>
                        <p class="text-center leading-relaxed text-gray-500 dark:text-gray-400">
                            Planejamento e construção de letra caixa luminoso.                         
                        </p>
                    </div>
                    <!-- Modal footer -->
                    <div class="flex items-center p-4 md:p-5 border-t border-gray-200 rounded-b dark:border-gray-600">
                        <a  href="https://api.whatsapp.com/send?phone=5511995103964&text=Olá, estou interessado na criação de um projéto para a construção da letra caixa luminoso da minha empresa." target="_blank" data-modal-hide="default-modal4" type="button" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">
                            Solicitar orçamento</a>
                    </div>
                </div>
            </div>
        </div>








    <div class="lg:pt-[150px] md:pt-[130px] pt-[130px]" />
    <slot />

    <Footer />

</template>

<script setup>
 import 'flowbite';

 import { onMounted } from 'vue'
import { 
    initAccordions, 
    initCarousels, 
    initCollapses, 
    initDials, 
    initDismisses, 
    initDrawers, 
    initDropdowns, 
    initModals, 
    initPopovers, 
    initTabs, 
    initTooltips } from 'flowbite'

// initialize components based on data attribute selectors
onMounted(() => {
    initAccordions();
    initCarousels();
    initCollapses();
    initDials();
    initDismisses();
    initDrawers();
    initDropdowns();
    initModals();
    initPopovers();
    initTabs();
    initTooltips();
})

</script>
