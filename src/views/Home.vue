<template>
   <div class="home">
      <button @click="saluda">Saludar..!</button>
      <button @click="saluda2">Saludar 2</button>
      <img alt="Vue logo" src="../assets/logo.png">
      <HelloWorld msg="Welcome to Your Vue.js App"/>
      <div class="boxs"></div>
      <div class="parrafo-3">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum amet illum dolor laudantium eveniet dolores magnam id fuga totam! Minus consequatur neque amet corrupti nulla nesciunt obcaecati ipsam architecto adipisci.
      </div>
   </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  // d915459b3ead927af67dcbb267273ae9
  methods:{
    saluda(){
      confirm('Hola...')
    },
    saluda2(){
      alert('Hola hola como estan amigos....')
    }
  }
}
</script>
