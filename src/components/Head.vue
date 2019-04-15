<template>
    <div class="main">
      <span class="nome-logo">rede+</span>
      <hr class="linha1"/>
      <span class="texto-head">O pit stop onde você ganha pontos  muito mais!</span>
      <hr class="linha2"/>
       <img class="img-home" src="../assets/img/img_home.jpg">
       
       
       <mInformatvo/>
        <mContainer_Pagamento/>

    </div>
    
</template>

<script>

import mInformatvo from './Informativo'
import mContainer_Pagamento from './Container_pagamento'

export default {
  name: 'Head Aplicacao',
  data () {
    return {
      msg: 'Topo da aplicacao'
    }
  },
  components: {
    mInformatvo,
    mContainer_Pagamento
  }
 

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.img-home {
  width: 100%;
  height: 300px;
  background-size: 100% 100%;
}
.nome-logo{
   position: absolute;
  font-size: 30px;
  right: 100px;
  color: white
  
}
.main{
  text-align: right;
}
.linha1{
  position: absolute;
  width:80%;  
 right: 100px;
  margin-top: 70px;
  height: 2px;
  background-color: white;
  border-color:white;
  border-radius: 50%;
}
.linha2{
  position: absolute;
  width:80%;  
 right: 100px;
  margin-top: 150px;
  height: 2px;
  background-color: white;
  border-color:white;
  border-radius: 50%;
}

.texto-head{
  position: absolute;
  box-sizing:border-box;
  width:80%;  
  right: 100px;
  margin-top: 90px;
  color: white;
  font-size: 45px;
  text-align: center;
  border-color:black;
}

/* Menu responsivo */
@media (max-width: 480px) {
	.linha1 {
    right: 10px;
	}
  	.linha2 {
    right: 10px;
     margin-top: 300px;
	}
  .texto-head{
    font-size: 20px;
    
  }
}
@media (max-width: 768px) {
  .texto-head{
    font-size: 30px;
    right: 50px;
    text-align: right;
  }
	.linha1 {
    right: 20px;
	}
  .linha2 {
    right: 20px;
     margin-top: 190px;
	}

  .img-home {
    width: 100%;
    height: 230px;
    background-size: 100% 100%;
  }
}

</style>
