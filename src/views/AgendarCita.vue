<template>
    <div>

        <div class="margen">
            
                <div class="calendario">
                    <b-calendar  block locale=""></b-calendar>
                </div>

                <div class="hora">

                    <label class="etihora" for="hora">Hora:</label>
                    <input class="inphora" id="hora" type="time" v-model="hora">
                    <button class="btnhora btn btn-primary">Agendar Cita</button>
                </div>

        </div>
    </div>

</template>

<script>
    export default {
        components: {

        },
        data() {
            return {
                fecha: '',
                hora: ''
            }
        },
        computed: {
            validarFecha() {
                if (this.fecha < new Date().toISOString().substr(0, 10))
                    return true
            }

        },

    }
</script>

<style scope>
    .calendario{
        width: 50%;
    }
     .hora{
        margin-top: 50px;
        width: 50%;
    }
    .etihora{
        font-size: 30px;
        margin-right: 30px;
    }
    .inphora{
        font-size: 25px;
    }
    .margen {
        margin-top: 50px;
    }

    .botonage{
        margin-top: 50px;
        margin-left: 2300px;
    }
    .btnhora{
        margin-left: 115px;
        margin-bottom: 13px;
    }

</style>