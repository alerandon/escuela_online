<template>  
<div>

  <div class="bg-gray-300 flex justify-center">
    <img src="../assets/phone-1052023_1920.jpg" class="w-full h-full" id="libros">
  </div>

  <div class="bg-blue-600 p-2">
    <p class="text-gray-100 text-base md:text-xl lg:text-2xl">Áreas de conocimiento</p>
  </div>

  <div class="flex justify-center bg-gray-300 text-base md:text-xl lg:text-xl">

    <div class="flex justify-center bg-gray-100 md:rounded-lg md:m-10 lg:mx-40 lg:my-16 w-3/4 md:w-full  ">

    <div class="mx-auto md:w-5/6 lg:w-9/12 text-left flex flex-wrap flex-col md:flex-row lg:justify-between">
      
      <div class="flex mt-3 md:w-2/4 md:p-3">
        <div class="flex justify-center bg-green-300 rounded p-1 md:p-2 lg:p-2 md:h-20 lg:h-20 md:w-20 lg:w-20">
          <img class="w-8 md:w-16 lg:w-16 h-8 md:h-16 lg:h-16" src="../assets/fine-arts.png">
        </div>
        <p class="pt-2 pl-3 md:w-40">Artes y Humanidades</p>
      </div>
  
      <div class="flex mt-3 md:w-2/4 md:p-3 ">
        <div class="flex justify-center bg-teal-300 rounded p-1 md:p-2 lg:p-2 md:h-20 lg:h-20 md:w-20 lg:w-20">
          <img class="w-8 md:w-16 lg:w-16 h-8 md:h-16 lg:h-16" src="../assets/car-first-aid-kit.png">
        </div>
        <p class="pt-2 pl-3 md:w-40">Ciencias de la Salud</p>
      </div>
      
      <div class="flex mt-3 md:w-2/4 md:p-3 ">
        <div class="flex justify-center bg-yellow-400 rounded p-1 md:p-2 lg:p-2 md:h-20 lg:h-20 md:w-20 lg:w-20">
          <img class="w-8 md:w-16 lg:w-16 h-8 md:h-16 lg:h-16" src="../assets/lab.png">
        </div>
        <p class="pt-2 pl-3 md:w-40">Ciencias Exactas</p>
      </div>

      <div class="flex mt-3 md:w-2/4 md:p-3 ">
        <div class="flex justify-center bg-red-500 rounded p-1 md:p-2 lg:p-2 md:h-20 lg:h-20 md:w-20 lg:w-20">
          <img class="w-8 md:w-16 lg:w-16 h-8 md:h-16 lg:h-16" src="../assets/plan.png">
        </div>
        <p class="pt-2 md:pt-6 pl-3 md:w-40">Ingenieria</p>
      </div>

      <div class="flex my-3 md:w-2/4 md:p-3">
        <div class="flex justify-center bg-pink-400 rounded p-1 md:p-2 lg:p-2 h-10 md:h-20 lg:h-20 md:w-20 lg:w-20">
          <img class="w-8 md:w-16 lg:w-16 h-8 md:h-16 lg:h-16" src="../assets/icons8-lugar-de-encuentro-de-seguridad-50.png">
        </div>
        <p class="pt-2 pl-3 md:w-40">Ciencias Sociales</p>
      </div>

    </div>

    </div>

  </div>

</div>
</template>

<style>

@media only screen and (min-width: 1024px) {
  
  #libros {
    max-width: 75%;
    max-height: 550px;
  }

}

</style>