<template>
  <div>
    <BarraNavPaciente/>

    <div class="home">
      <b-row class="mt-5">
        <b-col cols="12" md="9">
          <div>
            <b-carousel id="carousel-fade" style="text-shadow: 0px 0px 2px #000" fade indicators img-width="100%"
              img-height="480">
              <b-carousel-slide caption="Nutrición - Amamos lo que hacemos"
                img-src="https://www.mutuauniversal.net/export/sites/webpublica/.galleries/Promocion_salud/dieta-saludable-habitos.jpg">
              </b-carousel-slide>
              <b-carousel-slide caption="Nutrición - Te decimos que comer"
                img-src="https://www.revistamoi.com/wp-content/uploads/2018/09/fit-mitos-.png"></b-carousel-slide>
              <b-carousel-slide caption="Nutrición - Asesorías todos los días"
                img-src="https://www.ula.edu.mx/images/modalidades/presencial/licenciaturas/ula_licenciatura_nutricion_tradicional.jpg">
              </b-carousel-slide>
              <b-carousel-slide caption="Nutrición - Adelgaza en pocos meses"
                img-src="https://www.nestle-centroamerica.com/sites/g/files/pydnoa521/files/Untitled%20design%20%2833%29.png">
              </b-carousel-slide>
              <b-carousel-slide caption="Nutrición - Sientete mas libre"
                img-src="https://thefoodtech.com/wp-content/uploads/2020/05/alimentaci%C3%B3n-y-nutrici%C3%B3n.jpg">
              </b-carousel-slide>
            </b-carousel>
          </div>
        </b-col>
        <b-col cols="12" md="3" class="mt-md-0 mt-3">
          <div>
            <b-card title="¡Agenda con Nosotros!"
              img-src="https://uvm.cdn-capital.digital/img/2019/01/consejos-de-los-nutri%C3%B3logos.jpg" img-alt="Image"
              img-top tag="article" style="width: 100%; text-align:center;" class="mb-2">
              <b-card-text class="justify-text">
                ¿Buscas un nutriólogo en Culiacán? Nuestros nutriologos cuentan con la preparación académica adecuada
                para atender todas las edades y a toda tu familia y llevar acabo un plan alimenticio adecuado para su
                desarrollo.
              </b-card-text>
              <b-button :to="{name: 'AgendarCita' }" variant="success" class="w-100">¡Haz una cita!</b-button>
            </b-card>
          </div>
        </b-col>
      </b-row>
      <hr>
      <b-row class="mt-4">
        <b-col cols="12">
          <h3 class="mt-2">¡Agenda tu cita!</h3>
        </b-col>
      </b-row>
      <b-row class="mt-4 mb-5">
        <b-col cols="12" md="3">
          <b-button squared variant="primary" class="w-100 btn-height mt-md-0 mt-3">
            <b-icon icon="check2-square" scale="2" aria-hidden="true"></b-icon><br /><span class="separacion-iconos">
              Consulta tus resultados</span>
          </b-button>
        </b-col>
        <b-col cols="12" md="3">
          <b-button squared variant="success" class="w-100 btn-height mt-md-0 mt-3">
            <b-icon icon="calendar2-date" scale="2" aria-hidden="true"></b-icon><br /><span class="separacion-iconos">
              Realiza tu cita ahora</span>
          </b-button>
        </b-col>
        <b-col cols="12" md="3">
          <b-button squared variant="info" class="w-100 btn-height mt-md-0 mt-3">
            <b-icon icon="credit-card" scale="2" aria-hidden="true"></b-icon><br /><span class="separacion-iconos">
              Cotiza tus estudios</span>
          </b-button>
        </b-col>
        <b-col cols="12" md="3">
          <b-button squared variant="danger" class="w-100 btn-height mt-md-0 mt-3">
            <b-icon icon="clipboard-data" scale="2" aria-hidden="true"></b-icon><br /><span class="separacion-iconos">
              Realiza tu seguimiento</span>
          </b-button>
        </b-col>
      </b-row>

    </div>
  </div>
</template>

<script>
  import BarraNavPaciente from '../components/BarraNavPaciente.vue'

  export default {


    components: {
      BarraNavPaciente
    }
  }
</script>

<style scoped>
.home{
  margin-top: 100px;
}
</style>