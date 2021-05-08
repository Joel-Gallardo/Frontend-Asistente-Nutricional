<template>

    <div>
        <BarraNavHome />

         <div class="contenido">
            <div class="">
                <div class="texto-header">

                    <h3 class="h100">¿PROBLEMAS DE SALUD POR NO CUIDAR TU DIETA?</h3>
                    <br>
                    <h1 class="h1agendar">Agenda una cita con un NUTRIOLOGO PROFESIONAL</h1>
                    <br>
                   
                </div>
                <div>
                    <img class="img-nutri" src="../assets/nutrionline.jpg">
                </div>
            </div>

        </div>

        <div class="header-home" id="inicio">
            <div class="display-flex">
                <div class="col-xs-6">
                    <figure class="figure">
                        <img src="../assets/headerHome.png" class="figure-img">
                    </figure>
                </div>

                <div class="col-xs-6">
                    <h1 class="h1agendar">Agenda Tu Cita Facilmente<br> Registrate, Inicia sesion Y Agenda tu Cita</h1>
                    <br><br>
                    <p class="parrafo">¡Reserva tu cita desde la comodida de tu hogar
                        o donde te encuentres!</p>
                </div>
            </div>
        </div>

        <div class="contenido-home">
            <div class="display-flex">
                <div>
                    <h1>Controla tu Progreso Desde tu Dispositivo Movil!</h1>
                    <br>
                    <p>
                        Manten El control de tu salud desde tu dispositio Movil
                        para tu comodidad
                    </p>
                </div>
                <div>
                    <img class="img-app" src="../assets/celu.png" alt="">
                </div>
            </div>

        </div>
    </div>

</template>

<script>
    import BarraNavHome from '../components/BarraNavHome.vue'


    export default {
        name: 'Home',
        components: {
            BarraNavHome
        },
        
    }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Anton&display=swap');
.h100{
    font-family: 'Anton', sans-serif;
}
.texto-header{
    text-align: center;
}
.img-nutri{
    display:block;
    margin:auto;
    max-width: 100%;
}
.contenido{
    margin-top: 100px;
}
    .display-flex {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .header-home {
        margin-top: 70px;

        font-family: Impact;
        font-size: 15px;
        color: white;

    }
    .img-app{
        width: 600px;
        height: 300px;
        
    }
    .contenido-home {
        
        margin-bottom: 100px;
        margin-top: 50px;

    }

    /* .footerHome {
    background-image: url("../assets/footerHome.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    overflow-y: hidden;
    font-family: Impact;
    font-size: 15px;
    color: white;
    height: 400px;
  }



  .nosotros {
    height: 500px;
    font-family: Impact;
    background-color: white;
    width: auto;
  }

  .porque {
    height: 500px;
    width: auto;
    font-family: Impact;
    color: white;
    background-color: #01b287;
  }

  .figure-img {
    margin-top: 30px;
    width: 400px;
    height: 400px;
  }

  .figure-img-n {
    width: 100px;
    height: 100px;
    margin-left: 3rem !important;
  }

  

  .mx-sm-2 {
    margin-right: 3rem !important;
  } */
    .parrafo {
        font-family: sans-serif;
        color: #0a2239;
        text-align: center;
        font-size: 25px;
    }

    .h1agendar {
        color: #FF9800;
        text-align: center;
        font-size: 45px;
font-family: Impact;
    }
</style>