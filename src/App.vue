<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="bg-johnatan1 h-[600px] w-[375px] p-5">
    <img src="/Logo.png" alt="logo" class="w-36 h-32 left-0 right-0 mx-auto mb-10"/>
    <p class="text-white text-2xl font-bold leading-7 mb-5 tracking-tight">Un objet ne vous plait plus
      et vous souhaitez vous en 
      débarasser?</p>
    <p class="text-white tracking-tighter mb-5">Renovae s’engage à donner une nouvelle vie à vos objets en vous mettant en relation avec des artistes au quatres coins de la france !</p>
    <a href="http://renova.arnaut.fr">
      <button class="border-2 border-orange-300 shadow-lg p-2 rounded-xl bg-orange-300 text-white mr-5">
        S'inscrire
      </button>
    </a>
    <button class="border-2 border-white p-2 rounded-xl text-orange-300">
      En savoir plus
    </button>
  </div>
  <div class="bg-orange-300 w-[375px] h-[500px] p-5">
    <p class="text-white font-bold text-2xl mb-5 leading-7">2 Millions de tonnes de mobilier
sont jeter en France par an</p>

    <p class="text-white font-semibold leading-5 mb-2">Au lieu de jeter vos anciens meubles pourquoi ne pas les confier à Renovae ?</p>
    <p class="text-white leading-5 font-light mb-5">Renovae vous permetterait de re-donner une nouvelle vie à vos objets en les rendants accessible à tous !</p>
    <a href="http://renova.arnaut.fr">
    <button class="bg-white p-2 rounded-xl mb-10">
      Rejoindre l'aventure
    </button>
    </a>
    <img src="/boite-de-recyclage.png" alt="boiterecyclage" class="left-0 right-0 mx-auto">
  </div>
  <div class="bg-johnatan2 w-[375px] h-[500px] p-7">
     <p class="text-white text-2xl font-bold leading-7 mb-5 tracking-tight mt-24">Un objet ne vous plait plus
      et vous souhaitez vous en 
      débarasser?</p>
    <p class="text-white tracking-tighter mb-5">Renovae s’engage à donner une nouvelle vie à vos objets en vous mettant en relation avec des artistes au quatres coins de la france !</p>
  </div>
  
  
</template>

<style>
  body{
    width: 100%;
    margin: 0;
  }
  html{
    margin: 0;
    height: 100%;
    width: 100%;
  }
</style>
