<template>
    <div>

        <div class="login">



            <h1 class="margen">Registro Nuevo Usuario</h1>

            <div class="modal-dialog text-center">
                <div class="col-sm-12">
                    <div class="modal-content">

                        <form>
                            <input type="text" placeholder="Nombre" class="form-control my-2" v-model.trim="nombre">
                            <input type="text" placeholder="Apellido" class="form-control my-2" v-model.trim="apellido">
                            <input type="e-mail" placeholder="Correo" class="form-control my-2" v-model.trim="email">
                            <input type="password" placeholder="Contraseña" class="form-control my-2" v-model.trim="contraseña">
                            <button type="submit" class="margenboton btn btn-primary" :disabled="bloquear"><i class="fas fa-sign-in-alt"></i> Registrarse
                            </button>
                        </form>

                    </div>
                </div>
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
                nombre: '',
                apellido: '',
                email: '',
                contraseña: ''
            }
        },
        computed: {
            bloquear() {
                if (!this.email.includes('@')) {
                    return true
                }
            }
        },

    }
</script>

<style scope>
    .margen {
        margin-top: 50px;
    }

    .login {
        height: 516px;
        background-image: url("../assets/fondoLogin.jpeg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center center;
        overflow-y: hidden;
    }

    .modal-content {
        background-color: #3b4652;
        opacity: .85;
        padding: 0 20px;
        box-shadow: 0px 0px 3px #848484;
    }

    .margenboton {
        margin-bottom: 10px;
    }
</style>