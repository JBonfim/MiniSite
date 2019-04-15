<template>

    <div class="main info-posicao ">
      <div class="wrapper">
        <div><a href=""><img class="img-tem" src="../assets/img/Icon home.svg"></a><br>Home</div>
        <div><a href=""><img class="img-tem" src="../assets/img/Icon promocoes.svg"></a><br>Promoções</div>
        <div><a href=""><img class="img-tem" src="../assets/img/Icon postos.svg"></a><br>Posto</div>
        <div><a href=""><img class="img-tem" src="../assets/img/Icon extrato.svg"></a><br>extrato</div>
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

.wrapper {
 display: grid;
   grid-template-columns: repeat(4, 1fr);
   grid-auto-rows: 100px;
}

.main{
  background-color: #f6f6f6;
}

.info-posicao {
	   margin-top: 180px;
}


.img-tem{
   height: 100px;
}

.nav-item {
			float: left;
			*display:  inline;
			zoom: 1;
			list-style: none;
     

		}
  .nav-item a {
    display: block;
    text-decoration: none;
    color: #000;
    padding:  15px 30px;
  }





/* Menu responsivo */
@media screen and (max-width: 480px)  {

	.img-tem{
    height: 30px;
  }

  .nav-item a {
    padding:  5px 10px;
  }

 

 
  
}
@media only screen and (max-width: 768px) {
 .img-tem{
    height: 50px;
  }
  .nav-item a {
    padding:  1px 5px;
    margin: 0 0 10px 0;
  }

  .info-posicao {
	   margin-top: 130px;
  }




}

</style>
