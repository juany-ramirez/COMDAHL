<template>
  <div class="container">
    <div class="section"></div>
    <main>
      <center>
        <div class="section"></div>
        <div class="container">

          <div class="z-depth-1 grey lighten-4 row" style="display: inline-block; padding: 32px 48px 0px 48px; border: 1px solid #EEE;">
            <form class="col s12" method="post">
              <div class='row'>
                <div class='col s12'>
                </div>
              </div>
              <div class='row'>
                <div class='input-field col s12'>
                  <input class='validate' type='email' name='email' id='email' />
                  <label for='email'>Usuario</label>
                </div>
              </div>
              <div class='row'>
                <div class='input-field col s12'>
                  <input class='validate' type='password' name='password' id='password' />
                  <label for='password'>Contraseña</label>
                </div>
                <label  style='float: right;'>
                  <a class='registro'><router-link to="/registrar"><b>Crear cuenta nueva</b></router-link></a>
  							</label>
              </div>
              <br>
              <center>
                <div class='row'>
                  <button type='submit' name='btn_login' class='col s12 btn btn-large waves-effect -green'>Login</button>
                </div>
              </center>
            </form>
          </div>
        </div>
      </center>

      <div class="section"></div>
      <div class="section"></div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'login'
}
</script>

<style scoped>
.registro{
  font-size: 15px;
  font-family: 'Source Sans Pro', sans-serif;
  color: #CCCC52;
}
.registro:hover{
  color: #06152F !important;
}
.-white{
  background-color: #FFFFC4;
  color: black;
}
.-green{
  background-color: #8FB259;
  color: black;
}
.-lightgreen{
  background-color: #CCCC52;
  color: #FFFFC4;
}
.-blue{
  background-color: #192B33;
  color: #FFFFC4;
}
.-yellow{
  background-color: #FFD933;
  color: #FFFFC4;
}
.-black{
  background-color: #212121;
  color: #FFFFC4;
}

</style>
