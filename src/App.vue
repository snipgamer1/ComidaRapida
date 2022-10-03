<template>
  
  <nav class="navbar navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand">
        <img src="https://th.bing.com/th/id/R.b2993979e8528ce7c471cd9ae0c06270?rik=BHsCzXSLDjQuxQ&riu=http%3a%2f%2f4.bp.blogspot.com%2f-UBIrGp3wuJE%2fUb3lYkIbfEI%2fAAAAAAAAAKA%2fDRWAml_s7Hw%2fs1600%2futt%2blogo.jpg&ehk=b5stpKvWIqwCstjoAqkj%2f8XwJnan3SVPQ%2bb46uiNdP8%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1" height="50" alt="Logo" loading="lazy"/>
      </a>
    </div>
  </nav>

  <br>


  <div class="row row-cols-1 row-cols-md-3 g-4">
    
    <card nombre="Pizza Batman" descripsion="pizza de pepperoni,con sabor a parmesano y mantequilla."  precio="$129 MXN"  > <img src="https://s3.amazonaws.com/images.ecwid.com/images/34012076/1952063617.jpg" alt=""></card>
    <card nombre="Papas Fritas" descripsion="Nuestras Papitas Mundialmente Famosas® de McDonald's ." precio="$69.00 MXN." > <img src="https://th.bing.com/th/id/R.a8bd0dd350fc1b856492b2727d940c9d?rik=tQh930btyyrv4g&pid=ImgRaw&r=0" alt=""> </card>
    <card nombre="Hamburguesa"  descripsion="Viene cubierta con pepinillos, crujiente lechuga, cebollas y queso americano" precio="$200 MXN." > <img src="https://th.bing.com/th/id/OIP.sIsMw2hsj9db3tHfRLBlHQHaE7?pid=ImgDet&rs=1" alt=""> </card>
    <card nombre="Spaghetti"  descripsion=" Tiene forma de delgada cuerda larga"  precio="$70.00 MXN." > <img src="https://th.bing.com/th/id/OIP.YixleAz2dzjXRd3FGfaIlwHaE7?pid=ImgDet&rs=1" alt=""> </card>
    <card nombre="Empanadas" descripsion="masa quebrada u hojaldre rellena con una preparación salada o dulce " precio="$35 MXN." > <img src="https://assets.tmecosys.com/image/upload/t_web600x528/img/recipe/ras/Assets/DEE1488A-5F7E-47DA-A275-BB109F03466D/Derivates/EF5F1AF3-FBB4-4151-AC52-D2C032884D17.jpg" alt=""> </card>
    <card nombre="Hot Dog" descripsion="Panecillo largo lleno con una salchicha de Frankfurt" precio="$55 MXN."> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Hot_dog_on_a_plate_-_Evan_Swigart.jpg/245px-Hot_dog_on_a_plate_-_Evan_Swigart.jpg" alt=""></card>
  </div>
  <br>
  
  <section class="">
    <footer class="text-center text-white" style="background-color: bisque;"> 
      <div class="container p-4 pb-0">
        <section class="">
          <p class="d-flex justify-content-center align-items-center">
            <span class="me-3">Gracias</span>
          </p>
        </section>
      </div>
      
    </footer>
  </section>

</template>



<script>
    import Card from "./components/Card.vue"
    export default {
      components: {
        Card,
      },
      
    };
</script>
       