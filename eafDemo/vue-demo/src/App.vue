<template>
  <div id="app">
    <dynamicPolygon></dynamicPolygon>
  </div>
</template>


<script>

import HelloWorld from './components/HelloWorld.vue'
import searchTest from './components/searchTest.vue'
import dynamicPolygon from './components/dynamicPolygon.vue'

 export default {
  components: {
    dynamicPolygon
   },
   mounted() {
   },
   name: 'App',
 }
</script>

<style>
 #app {
   display: flex;
   flex-direction: column;
   align-items: left;
   justify-content: center;
   width: 100%;
   height: 100%;
 }

 html, body {
   width: 100%;
   height: 100%;
   margin: 0;
   padding: 0;
 }
</style>
