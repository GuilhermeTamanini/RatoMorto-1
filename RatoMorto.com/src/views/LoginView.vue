<script></script>
<template>

    <form>
        
<div class="container" >
    <div>
        <h2> 
            Login
        </h2>
    </div>

  <div class="form-group">
    <label for="exampleInputEmail1">Endereço de email</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Seu email">
    <small id="emailHelp" class="form-text text-muted">Nunca vamos compartilhar seu email, com ninguém.</small>
  </div>

  <div class="form-group">
    <label for="exampleInputPassword1">Senha</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Senha">
  </div>

  <div class="form-group form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Clique em mim</label>
  </div>

  <small id="btnHelper" class="form-text text-muted">Não tem uma conta?</small>

  <div >

    <button type="submit" class="btn btn-primary">Enviar</button>

    <router-link to="/cadastro">
        <button id="btnCadastro" type="link" class="btn btn-primary">Cadastre-se</button>
    </router-link>

  </div>
</div>

</form>

</template>

<style scoped>
#btnHelper {
margin-left:240px;
}

input {
max-width:400px;
max-height:500px;
background-color: rgb(237, 248)223, ;
}

h2{
margin-left: 140px;
}

#btnCadastro{
margin-left: 185px;
}

form{
margin-top:100px;
padding-bottom: 1000px;
}

.container {
background-color: #f7eccb;
max-width: 400px;
max-height:500px;
border-radius: 20px;
}

</style>