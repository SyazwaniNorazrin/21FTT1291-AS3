<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
 
    <!-- <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" /> -->

  

<div class="grid grid-rows-3 grid-flow-col gap-4 max-md">

  <div class="row-span-3 "><img src="mypic.jpeg" width="200" height="100" alt=""></div>

  <div class="col-span-2 underline"><h1>About me</h1></div>

  <div class="row-span-2 col-span-2 bg-[#083344]" >
    <p class="text-white ">Hellow! My Name is Syazwani also known as Wani. 
    I am a student from Politeknik Brunei currently taking Web development.
    I would describe myself as an introvert person.
    My MBTI is INFJ.
  </p>
  </div>
</div>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
