<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 h1 {
   margin-bottom: 60px;
   font-size: 30px;
 }

 .command {
   font-size: 18px;
   display: inline-block;
   color: #490AEF;
 }
</style>
