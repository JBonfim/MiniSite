<template>
  <div id="app">
     <Slide>
       <div class="">
         <img class="img-user-redondo" src="./assets/img/users.jpg">
         <span class="nome-user">Jabes Bonfim</span>
         
       </div>
      <a id="" href="#">
        <span>Minha Conta</span>
      </a>
      <a id="" href="#">
        <span>Formas Pagamento</span>
      </a>
      <a id="" href="#">
        <span>Hístorico pagamentos</span>
      </a>
      <a id="" href="#">
        <span>Resgate de Pontos</span>
      </a>
      <a id="" href="#">
        <span>Indicar Amigos</span>
      </a>
      <a id="" href="#">
        <span>Ajuda</span>
      </a>
      <a id="" href="#">
        <span>Sobre o App</span>
      </a>
      <a id="" href="#">
        <span>Logaut</span>
      </a>
    </Slide>
    <mHead/>
    <mFooter/>
  </div>
</template>

<script>

import mHead from './components/Head'
import { Slide } from 'vue-burger-menu'
import mFooter from './components/Footer'

export default {
  name: 'AppDesafioRedSoft',
  components: {
    mHead,
    Slide,
    mFooter
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
	margin:  0;
	padding:  0;
	box-sizing: border-box;
}



.img-user-redondo {
   border-radius: 50%;
   height: 80px;
   overflow: hidden;
   position: relative;
   width: 80px;
}
.nome-user{
  margin-top: 20px;
}
</style>
