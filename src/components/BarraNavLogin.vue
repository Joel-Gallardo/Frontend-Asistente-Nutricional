<template>
  <div>
    <nav class="navbar fixed-top navbar-expand-lg navbar-light">
      
        <img src="../assets/logoBarraNav.png" class="d-inline-block align-top navbar-logo" alt="">
      
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse " id="navbarSupportedContent">
        <a class="nav-link" href="/Home">Inicio</a>
      </div>
      <!-- <router-link  class="btn btn-outline-success mx-sm-2"  to="/Login" style="float: center;" type="submit">Iniciar Sesión</router-link>
      <button class="btn btn-outline-success mx-sm-2"  data-toggle="modal" data-target="#modalRegistro" style="float: center;" type="submit">Registrarse</button>     -->
    </nav>
    <!-- <div class="modal fade" id="modalRegistro" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
      <div class="modal-dialog" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <router-link class="modal-title" id="exampleModalLabel">Registrarse</router-link>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            Selecciona el tipo de registro
          </div>
          <div class="modal-footer">
            <router-link class="btn btn-secondary" to="/RegistroCliente" data-dismiss="modal" >Soy Cliente</router-link>
            <router-link class="btn btn-primary" to="/RegistroEmpresa" data-dismiss="modal" >Soy Empresa</router-link>
          </div> 
        </div>
      </div>
    </div> -->
  </div>
</template>

<script>

  export default {
  }
</script>

<style scoped>
  .bc-background-redox-1 { background-color: #0a2239; }
  .bc-background-redox-2 { background-color: #01b287; }
  .bc-background-redox-3 { background-color: #ff9f1c; }
  .bc-background-redox-4 { background-color: #e5505a; }
  .bc-background-redox-5 { background-color: #854c9e; }
  
  .navbar{
    height: 70px;
    background-color: white;
  }
  
  .navbar-logo{
    margin-left: 4rem !important;
    width: 60px;
    height: 60px;
  }

  .navbar-icons{
    width: 20px;
    height: 20px;
    margin-left: 1.5rem !important;
    margin-right: 1.5rem !important;
  }

  .navbar-brand{
    margin-left: 2.5rem !important;
    margin-right: 2.5rem !important;
  }

  .nav-link
  {
    font-size: 20px;
    color:#000000;
  }

  .btn-primary {
    color: #25D81B;
    background-color: #f8f8f8;
    border-color: #25D81B;
  }

 .btn-primary:hover {
    color: #fff;
    background-color: #000000;
    border-color: #000000;
  }

  .btn-primary:not(:disabled):not(.disabled):active, .btn-primary:not(:disabled):not(.disabled).active,
  .show > .btn-primary.dropdown-toggle {
    color: #fff;
    background-color: #000000;
    border-color: #000000;
  }

  .btn-secondary {
    color: #000000;
    background-color: #f8f8f8;
    border-color: #000000;
  }

  .btn-secondary:hover {
    color: #fff;
    background-color: #25D81B;
    border-color: #25D81B;
  }

  .btn-secondary:not(:disabled):not(.disabled):active, .btn-secondary:not(:disabled):not(.disabled).active,
  .show > .btn-secondary.dropdown-toggle {
    color: #fff;
    background-color: #25D81B;
    border-color: #25D81B;
  }

  .btn-outline-success {
    color: #000000;
    border-color: #000000;
  }

  .btn-outline-success:hover {
    color: #fff;
    background-color: #25D81B;
    border-color: #25D81B;
  }

  .btn-outline-success:not(:disabled):not(.disabled):active, .btn-outline-success:not(:disabled):not(.disabled).active,
  .show > .btn-outline-success.dropdown-toggle {
    color: #fff;
    background-color: #000000;
    border-color: #000000;
  }

  .btn-outline-success:focus, .btn-outline-success.focus {
    box-shadow: 0 0 0 0.2rem #25D81B;
  }
  
  .mr-sm-2,
  .mx-sm-2 {
    margin-right: 0.5rem !important;
  }
</style>

