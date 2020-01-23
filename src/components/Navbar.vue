<template>
  <nav class="flex lg:justify-between bg-gray-200 lg:h-12 p-2 md:p-4 lg:p-2">
    <div class="w-1/2 lg:w-4/12 flex justify-start">
      <img src="../assets/school.png" class="w-10 md:w-20 lg:w-8 h-10 md:h-20 lg:h-8 mx-2">
      <p id="title" class="pt-2 md:pt-5 lg:pt-1 md:pl-3 lg:pl-1 text-base md:text-4xl lg:text-xl hidden md:inline-block">Escuela Online</p>
    </div>
    <div class="w-1/2 lg:w-8/12 flex justify-end">
      
      <img src="../assets/menu-alt-512.png" class="w-10 md:w-20 h-10 md:h-20 mr-2 lg:hidden">

      <div class="hidden lg:flex justify-end text-lg">
        <a href="#" class="mx-4 mt-1">Inicio</a>
        <a href="#" class="mx-4 mt-1">Cursos</a>
        <a href="#" class="mx-4 mt-1">Áreas de conocimiento</a>
        <a href="#" class="mx-4 mt-1">Acerca de</a>
        <a href="#" class="mx-4 mt-1">Contacto</a>
      </div>

    </div>
  </nav>

</template>

<style>

  #title {
    font-family: 'Galdeano', sans-serif;
  }

</style>