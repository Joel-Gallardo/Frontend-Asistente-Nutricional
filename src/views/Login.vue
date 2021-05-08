<template>
    <div>

        <div class="login">
            <h1 class="margen">Inicia Sesion</h1>


            <div class="modal-dialog text-center">
                <div class="col-sm-8 main-section">
                    <div class="modal-content">
                        <div class="col-12 user-img">
                            <img src="../assets/logoUsuario.png"/>
                        </div>
                        <form class="col-12" th:action="@{/login}" method="get">
                            <div class="form-group" id="user-group">
                                
                                <input type="text" class="form-control" placeholder="Nombre de usuario"
                                    name="username"/>
                            </div>
                            <div class="form-group" id="contrasena-group">
                                <input type="password" class="form-control" placeholder="Contrasena" name="password" />
                               
                            </div>
                            <button type="submit" class="btn btn-primary"> Ingresar
                            </button>
                        </form>
                        <!-- <div class="col-12 forgot">
                            <a href="#">Recordar contrasena?</a>
                        </div> -->
                        <!-- <div th:if="${param.error}" class="alert alert-danger" role="alert">
                            Usuario y Contraseña Invalidos.
                        </div>
                        <div th:if="${param.logout}" class="alert alert-success" role="alert">
                            Te has desconectado.
                        </div> -->
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>



<style scope>

    .login {
        height: 516px;
        background-image: url("../assets/fondoLogin.jpeg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center center;
        overflow-y: hidden;
    }

    .margen {
        font-family: 'Questrial', sans-serif;
        margin-top: 35px;
    }


    .main-section {
        margin: 0 auto;
        margin-top: 10%;
        padding: 0;
    }

    .modal-content {
        background-color: #3b4652;
        opacity: .85;
        padding: 0 20px;
        box-shadow: 0px 0px 3px #848484;
    }

    .user-img {
        margin-top: -50px;
        margin-bottom: 35px;
    }

    .user-img img {
        width: 100xp;
        height: 100px;
        box-shadow: 0px 0px 3px #848484;
        border-radius: 50%;
    }

    .form-group input {
        height: 42px;
        font-size: 18px;
        border: 0;
        padding-left: 54px;
        border-radius: 5px;
    }

    .form-group::before {
        font-family: "Font Awesome\ 5 Free";
        position: absolute;
        left: 28px;
        font-size: 22px;
        padding-top: 4px;
    }

    .form-group#user-group::before {
        content: "\f007";
    }

    .form-group#contrasena-group::before {
        content: "\f023";
    }

    button {
        width: 60%;
        margin: 10px 0 25px;
    }

    .forgot {
        padding: 5px 0;
    }

    .forgot a {
        color: white;
    }
</style>