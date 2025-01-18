

<template class="bg-white">




    <MainLayout>  



<!--Banner-->



    <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-0 drop-shadow-lg">

      
      <!--Plotagem automotiva-->
      <Carousel :autoplay="10000" :wrap-around="true">
          <Slide v-for="slide in 1" :key="slide">
            <div class="carousel__item_1">
                  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-8 grid lg:grid-cols-2 gap-8 lg:gap-8">
                      <div class="flex flex-col justify-center">
                          <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-[#f78a23] to-[#7b0000]">Lonas plásticas</h1>
                          <p class="mb-8 text-lg font-normal  lg:text-xl dark:text-gray-400 text-transparent bg-clip-text bg-[#7b0000]">Lonas plásticas ideais para construção civil e agronegócio.</p>
                          <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/lonasplasticas')" class="text-white bg-gradient-to-br from-[#7b0000] to-[#f78a23] hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Conheça</button>
                          </div>
                      </div>
                      <div>
                        <img class="rounded-t-lg"  width="500" src="/b1.png" alt="">
                      </div>
                  </div>
            </div>
          </Slide>




          <!--Fachadas-->
          <Slide v-for="slide in 1" :key="slide">
            <div class="carousel__item_1">
                  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-8 grid lg:grid-cols-2 gap-8 lg:gap-8">
                      <div class="flex flex-col justify-center">
                          <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-[#f78a23] to-[#7b0000]">Filme Stretch</h1>
                          <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400 text-transparent bg-clip-text bg-[#7b0000]">Solução ideal para proteger e embalar.</p>
                          <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/filmestretch')" class="text-white bg-gradient-to-br from-[#7b0000] to-[#f78a23] hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Veja mais</button>
                          </div>
                      </div>
                      <div>
                        <img class="rounded-t-lg" width="500"  src="/b2.png" alt="">
                      </div>
                  </div>
            </div>
          </Slide>


          <!--Luminoso-->
          <Slide v-for="slide in 1" :key="slide">
            <div class="carousel__item_1">
                  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-8 grid lg:grid-cols-2 gap-8 lg:gap-8">
                      <div class="flex flex-col justify-center">
                          <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-[#f78a23] to-[#7b0000]">Tela Agrícola Aviário Netlon</h1>
                          <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400 text-transparent bg-clip-text bg-[#7b0000]">Flexível e resistente.</p>
                          <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/telaaviaria')" class="text-white bg-gradient-to-br from-[#7b0000] to-[#f78a23] hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Veja mais</button>
                          </div>
                      </div>
                      <div>
                        <img class="rounded-t-lg" width="500"  src="/b3.png" alt="">
                      </div>
                  </div>
            </div>
          </Slide>    


      </Carousel>

    </div>


    <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">
    
     
    <!-- <div class="bg-gray-50 rounded-lg p-8 md:p-12 mb-8 drop-shadow-lg">
               <h1 class="text-gray-900 dark:text-white text-3xl md:text-5xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Somos a Flex design</h1>
               <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-6">Atuamos no ramo de Comunicação Visual desde o ano 2000. Nossa empresa conta com mão-de-obra especializada e equipamentos de ultima geração, oferecendo serviço de alta qualidade, preço acessível em um curto prazo. O grande diferencial é o nosso atendimento personalizado, visa entender as necessidades de seus clientes, os ajudando com estratégias e posicionamento para atingir o melhor resultado de comunicação, respeitando ás suas exigências de qualidade. O Propósito da Flex Design é sempre desenvolver um relacionamento sólido com seus clientes, executando nosso trabalho de forma transparente, assim transmitindo credibilidade na realização de seus serviços, com isso obtendo á expansão de seus negócios estrategicamente planejada, tornando-se uma empresa atuante no mercado.</p>
    </div>-->
           <div class="grid md:grid-cols-3 gap-8 justify-center">
              <div class="bg-[#7b0000] dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12 drop-shadow-lg backdrop-blur-md ">


                   <img class="rounded-t-lg"  src="/ca1.png" alt="Luminoso">
                   <h1 class="text-gray-900 dark:text-white text-3xl font-extrabold mb-2 text-transparent bg-clip-text bg-clip-text bg-[#ffffff]">
                      Lonas Plásticas</h1>
                   <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4 text-transparent bg-clip-text bg-[#ffffff]">
                    A Construlonas fornece as lonas plásticas flexíveis mais resistentes do mercado, Lonas impermeáveis fabricadas em polietileno de alta qualidade.</p>
                    <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/lonasplasticas')" class="text-white bg-gradient-to-br from-[#7b0000] to-[#f78a23] hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Ver mais</button>
                          </div>
               </div> 
   
               <div class="bg-[#7b0000] dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12 drop-shadow-lg backdrop-blur-md">
                   <img class="rounded-t-lg"  src="/ca2.png" alt="Fachada">
                   <h2 class="text-gray-900 dark:text-white text-3xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r bg-[#ffffff] text-transparent">
                      Filme Stretch</h2>
                   <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4 text-transparent bg-clip-text bg-gradient-to-r bg-[#ffffff]">
                    Para proteção e embalagem de produtos, especialmente no transporte e armazenamento, grande aderência e resistência.
                    Bobinas disponiveis para produtos leves e pesados ou com bordas pontiagudas.
                   </p>
                   <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/filmestretch')" class="text-white bg-gradient-to-br from-[#7b0000] to-[#f78a23] hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Ver mais</button>
                    </div>
               </div> 

               <div class="bg-[#7b0000] dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12 drop-shadow-lg backdrop-blur-md">

                   <img class="rounded-t-lg"  src="/ca3.png" alt="Plotagem">
                   <h2 class="text-gray-900 dark:text-white text-3xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r bg-[#ffffff]">
                    Tela Agrícola Aviária </h2>
                   <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4 text-transparent bg-clip-text bg-gradient-to-r bg-[#ffffff]  ">
  Tela fabricada em polietileno de alta densidade
 desenvolvida especialmente para o uso em aviários, 
 viveiro para aves e manejo de criações. Também aplicações agricultura, jardinagem e paisagismo.     </p>                 <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/telaaviaria')" class="text-white bg-gradient-to-br from-[#7b0000] to-[#f78a23] hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Ver mais</button>
                    </div>
               </div> 
           </div>
       </div>




<div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">



        <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-[#f78a23] to-[#7b0000]">
              LONAS PLÁSTICAS</h1>
            <h2 class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-48 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r bg-[#7b0000]">
              LONAS MUITO UTILIZADAS POR PINTORES PARA COBERTURA DA ÁREA DE TRABALHO, UTILIZADAS POR CONSTRUTORAS E EMPRESAS DE PISOS INDUSTRIAIS, NAS OBRAS PARA PROTEÇÃO DE PISOS, IMPERMEABILIZAÇÃO E PROTEÇÃO DE MATERIAIS.</h2>
        </div>


        <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-[#f78a23] to-[#7b0000]">
              BOBINAS PLÁSTICAS</h1>
            <h2 class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-48 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r bg-[#7b0000]">
              AS BOBINAS PLÁSTICAS TEM DIVERSAS UTILIDADES, POREM SUA
              MAIOR UTILIZAÇÃO É PARA EMBALAR QUAISQUER TIPO DE
              INSUMOS, TAMBÉM CONHECIDA COMO BOBINA TUBULAR.</h2>
        </div>


        <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-[#f78a23] to-[#7b0000]">
              FRETE</h1>
            <h2 class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-48 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r bg-[#7b0000]">
              ATENDEMOS TODO O TERRITÓRIO NACIONAL<br>
              FRETE GRÁTIS PARA GRANDE SÃO PAULO.</h2>
        </div>


        <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-[#f78a23] to-[#7b0000]">
              COMPRE DIRETO COM O FABRICANTE!!!</h1>
            <h2 class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-48 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r bg-[#7b0000]">
              LONA PRETA E COLORIDA,TELA PARA AVICULTURA<br>
              FILME STRETCH COM E SEM TUBETE.<br>
              ENTRE EM CONTATO CONOSCO PELO WHATSAPP E FAÇA JÁ SEU PEDIDO!!!</h2>
        </div>
</div>




<!--
<div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">
        <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 quemsomos">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
              Nossos clientes</h1>
              

              <div class="grid grid-cols-4 md:grid-cols-4 gap-4">
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/1.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/2.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/3.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/4.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/5.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/6.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/7.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/8.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/9.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/10.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/11.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/12.jpg" alt="">
                </div>
              
            </div>


        </div>
</div>
-->




<!--

<div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">
    
     
    <div class="bg-gray-50 rounded-lg p-8 md:p-12 mb-8 drop-shadow-lg">
            <h1 class="text-gray-900 dark:text-white text-3xl md:text-5xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Somos a Flex design</h1>
            <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-6">Atuamos no ramo de Comunicação Visual desde o ano 2000. Nossa empresa conta com mão-de-obra especializada e equipamentos de ultima geração, oferecendo serviço de alta qualidade, preço acessível em um curto prazo. O grande diferencial é o nosso atendimento personalizado, visa entender as necessidades de seus clientes, os ajudando com estratégias e posicionamento para atingir o melhor resultado de comunicação, respeitando ás suas exigências de qualidade. O Propósito da Flex Design é sempre desenvolver um relacionamento sólido com seus clientes, executando nosso trabalho de forma transparente, assim transmitindo credibilidade na realização de seus serviços, com isso obtendo á expansão de seus negócios estrategicamente planejada, tornando-se uma empresa atuante no mercado.</p>
        
        </div>
        
        <div class="grid md:grid-cols-2 gap-8">
          <div class="bg-gray-100 rounded-lg backdrop-blur-md">
              <Carousel :autoplay="6000" :wrap-around="true">


                  <Slide v-for="slide in 1" :key="slide">
                    <div class="item_card_1">
                        <figure class="bg-gray-100 rounded-lg backdrop-blur-md">
                         <a href="https://www.flexdesignituoficial.imprimastore.com.br/" ><img class="h-auto max-w-full rounded-lg" src="/banner_aqui.jpg" alt="image description"></a>
                        </figure>
                    </div>
                  </Slide>
                  
                  <Slide v-for="slide in 1" :key="slide">
                    <div class="item_card_1">
                        <figure class="bg-gray-100 rounded-lg backdrop-blur-md">
                          <a href="https://www.flexdesignituoficial.imprimastore.com.br/" ><img class="h-auto max-w-full rounded-lg" src="/faixa_banner_aqui.jpg" alt="image description"></a>
                        </figure>
                    </div>
                  </Slide>


                  <template #addons>
                  </template>
              </Carousel>
            </div>

            <div class="bg-gray-100 rounded-lg backdrop-blur-md">
              <Carousel :autoplay="6000" :wrap-around="true">


                  <Slide v-for="slide in 1" :key="slide">
                    <div class="item_card_1">
                        <figure class="bg-gray-100 rounded-lg backdrop-blur-md">
                         <a href="https://www.flexdesignituoficial.imprimastore.com.br/" ><img class="h-auto max-w-full rounded-lg" src="/banner_aqui.jpg" alt="image description"></a>
                        </figure>
                    </div>
                  </Slide>
                  
                  <Slide v-for="slide in 1" :key="slide">
                    <div class="item_card_1">
                        <figure class="bg-gray-100 rounded-lg backdrop-blur-md">
                          <a href="https://www.flexdesignituoficial.imprimastore.com.br/" ><img class="h-auto max-w-full rounded-lg" src="/faixa_banner_aqui.jpg" alt="image description"></a>
                        </figure>
                    </div>
                  </Slide>


                  <template #addons>
                  </template>
              </Carousel>
            </div>
        </div>
    </div>

  -->




  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
    <a href="https://wa.me/5511998905016?text=Olá, gostaria de mais informações!" style="position:fixed;width:60px;height:60px;bottom:40px;right:40px;background-color:#25d366;color:#FFF;border-radius:50px;text-align:center;font-size:30px;box-shadow: 1px 1px 2px #888;
      z-index:1000;" target="_blank">
    <i style="margin-top:16px" class="fa fa-whatsapp"></i>
    </a>




     </MainLayout>  
  
  </template>






<script>
import { defineComponent } from 'vue'
import { Carousel, Pagination, Slide } from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

export default defineComponent({
  name: 'Autoplay',
  components: {
    Carousel,
    Slide,
    Pagination,
  },
})
</script>

<style>




.carousel__item {
  min-height: 300px;
  width: 100%;
  background-color: var(--vc-clr-primary);
  color: var(--vc-clr-white);
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url(/50001.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.carousel__item_2 {
  min-height: 300px;
  width: 100%;
  background-color: var(--vc-clr-primary);
  color: var(--vc-clr-white);
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url(/50002.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}




.item_card_1 {
  width: 100%;
  background-color: var(--vc-clr-primary);
  color: var(--vc-clr-white);
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url(/flex_design_3d.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

</style>






  
  <script setup>
  
  import MainLayout from '~/layouts/MainLayout.vue';

  

  </script>
  