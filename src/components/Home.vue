<template>

<div class="home flex flex-col md:flex-row items-center justify-center bg-white">
  
    <div class="content text-center md:text-left md:mr-8">
      <div class="intro">
    <h1 id="typed" class="text-4xl font-extrabold leading-tight tracking-tight mb-8 text-black-1000">
      <span class="rgb-animation text-4xl">Hello there, I'm Lievan</span>
    </h1>
    <p class="mb-2 text-xl text-black font-semibold leading-tight tracking-tight">
     
    </p>
    <p class="mb-6 text-xl text-black font-semibold leading-tight tracking-tight">
     
    </p>
  </div>
      </div>
    </div>
     <p class="mx-auto mb-16 text-lg text-size-40 font-lg font-semibold text-black max-w-lg text-center">This is My First Portfolio Website</p>
  <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-gray-1000">
      <img class="w-full h-40 object-cover" src="/images/library.jpg" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">CPC Library Kioks</h2>
        <p class="text-gray-700 mb-4">In this library app, students of Cordova Public College can reserve the books they need to borrow.</p>
      </div>
    </div>
    
    
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-gray-1000">
      <img class="w-full h-40 object-cover" src="/images/Pacific.jpg" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">TBA Pacific Corporation Website</h2>
        <p class="text-gray-700 mb-4">On this website, customers can browse and book the hotels they desire to stay in.</p>
      </div>
    </div>
    
    
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-gray-1000">
      <img class="w-full h-40 object-cover" src="/images/flavour2.jpg" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Flavour Coffee Shop Website</h2>
        <p class="text-gray-700 mb-4">This app allows customers to easily view the available coffee options on the menu. It was developed using PHP and Vue.js.</p>
      </div>
    </div>
    
    <!-- Card 6 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-gray-1000">
      <img class="w-full h-40 object-cover" src="/images/port2.jpg" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Portfolio Website</h2>
        <p class="text-gray-700 mb-4">My personal Portfolio made with Vue.js</p>
      </div>
    </div>
  </div>


<section class="container mx-auto py-8">
  
    
    
</section>


</template>

<script>
</script>

<style scoped>
body{
  background-color: black;
}
.rgb-animation {
  animation: rgbAnimation 3s infinite alternate;
}

@keyframes rgbAnimation {
  0% {
    color: rgb(17, 13, 13);
  }
  33% {
    color: rgb(8, 8, 8);
  }
  66% {
    color: rgb(1, 1, 8);
  }
  100% {
    color: rgb(2, 2, 2);
  }
}
</style>
