<template>
    <div class="main info-posicao">
      <span class="texto-informativo">
          Olá, Jabes! <span class="segundo-info">Você está agora em um posto participante da rede+</span>
           
          </span>
       <img class="img-informativo" src="../assets/img/container2.png">
    </div>
    
</template>

<script>
export default {
  name: 'Informacao',
  data () {
    return {
      msg: 'Texto informativo da aplicacao'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.info-posicao {
	margin-top: -4px;
}

.img-informativo {
  width: 100%;
  height: 100px;
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


.texto-informativo{
  position: absolute;
  box-sizing:border-box;
  width:80%;  
  right: 100px;
  margin-top: 30px;
  color: white;
  font-size: 30px;
  text-align: center;
  border-color:black;
}

/* Menu responsivo */
@media (max-width: 480px) {
	
  .texto-informativo{
    font-size: 15px;
    text-align: left;
    right: 50px;
    margin-top: 0px;
    
  }
}
@media (max-width: 768px) {
  .texto-informativo{
    font-size: 20px;
    text-align: left;
    right: 50px;
    margin-top: 8px;
  }

 
	

  .img-informativo {
    width: 100%;
    height: 100px;
    background-size: 100% 100%;
  }
}

</style>
