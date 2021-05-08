<template>
  <div>
    <nav class="navbar fixed-top navbar-expand-lg navbar-light">
      
        <img src="../assets/logoBarraNav.png" class="d-inline-block align-top navbar-logo" alt="">
      
     
      <div class="collapse navbar-collapse " id="navbarSupportedContent">
        <a class="nav-link" href="/">Inicio</a>
      </div>
        
    </nav>
     
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
    width: auto;
    background-color: #00C853;
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

  .iniciasesion {
    color: #000000;
    border-color: #000000;
  }

  .iniciasesion:hover {
    
    background-color: #25D81B;
    border-color: #25D81B;
  }

  .iniciasesion:not(:disabled):not(.disabled):active, .iniciasesion:not(:disabled):not(.disabled).active,
  .show > .iniciasesion.dropdown-toggle {
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

