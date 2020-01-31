<template>
  <nav class="flex lg:justify-between bg-gray-200 lg:h-12 p-2 md:p-2 lg:p-2">
    <div class="w-1/2 lg:w-4/12 flex justify-start">
      <img src="../assets/school.png" class="w-10 md:w-10 lg:w-8 h-10 md:h-10 lg:h-8 mx-2">
      <p id="title" class="pt-2 md:pt-3 lg:pt-1 md:pl-1 lg:pl-1 text-base md:text-xl lg:text-xl hidden md:inline-block">Escuela Online</p>
    </div>
    <div class="w-1/2 lg:w-8/12 flex justify-end">
      
      <div class="lg:hidden">
        <button @click="isOpen = !isOpen"  type="button" class="block focus:outline-none lg:hidden">
          <img v-if="isOpen" src="../assets/menu-alt-512.png" class="w-8 md:w-8 h-8 md:h-8 mr-2 mt-1">
          <img v-if="!isOpen" src="../assets/menu-alt-512.png" class="w-8 md:w-8 h-8 md:h-8 mr-2 mt-1">
        </button>
      </div>

      <ul :class="isOpen ? 'block' : 'hidden'" class="lg:flex text-lg text-gray-500">
        <a href="#" class="block hover:text-gray-800 mx-4 mt-1">Inicio</a>
        <a href="#" class="block hover:text-gray-800 mx-4 mt-1">Cursos</a>
        <a href="#" class="block text-gray-800 mx-4 mt-1">Áreas de conocimiento</a>
        <a href="#" class="block hover:text-gray-800 mx-4 mt-1">Acerca de</a>
        <a href="#" class="block hover:text-gray-800 mx-4 mt-1">Contacto</a>
      </ul>
    
    </div>

  </nav>

</template>

<style>

  #title {
    font-family: 'Galdeano', sans-serif;
  }

</style>

<script>
export default {
  data() {
    return {
      isOpen: false,
    }
  },
}
</script>