<template>
    <div class="main info-posicao">
      <button class="btn-pagamento">PAGUE PELO APP</button>
        <div class="texto-informativo">
            Efetue o pagamento on-line pelo app e acumule seus pontos automaticamente.
        </div>
        <div class="">
            <a class="text-saiba-mais" href="#">Saiba aqui como pagar.</a>
        </div>
    </div>
    
</template>

<script>
export default {
  name: 'Pagamento',
  data () {
    return {
      msg: 'Componente referente as opções de pagamento para o usuario'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.info-posicao {
	margin-top: 10px;
   text-align: center;
}
.btn-pagamento{
   border-radius: 10px;
   height: 60px;
   overflow: hidden;
   position: relative;
   width: 50%;
   color: white;
   background-color: #5f5d5d;
   font-size: 30px;
}




.texto-informativo{
  position: absolute;
  box-sizing:border-box;
  width:80%;  
  right: 50px;
  margin-top: 30px;
  color: #5f5d5d;
  font-size: 30px;
  text-align: center;
  border-color:black;
}
.text-saiba-mais{
     position: absolute;
  box-sizing:border-box;
  width:80%;  
  right: 100px;
  margin-top: 100px;
  color:  #ebac00;
  font-size: 30px;
  text-align: center;
  border-color:black;
}

/* Menu responsivo */
@media (max-width: 480px) {
	
  .texto-informativo{
    font-size: 15px;
    text-align: center;
    right: 40px;
    margin-top: 5px;
    
  }
  .text-saiba-mais{
    width:80%;  
    right: 50px;
    margin-top: 50px;
    color:  #ebac00;
    font-size: 18px;
    text-align: center;
    border-color:black;
    }
}
@media (max-width: 768px) {
  .btn-pagamento{
    border-radius: 10px;
    height: 50px;
    overflow: hidden;
    position: relative;
    width: 80%;
    color: white;
    background-color: #5f5d5d;
    font-size: 20px;
    }

    .texto-informativo{
        font-size: 18px;
         margin-top: 5px;
        
    }

    .text-saiba-mais{
        margin-top: 70px;
        right: 40px;
    }

    


}

</style>
