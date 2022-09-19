<script></script>
<template>

    <form>
        
<div class="container" >
    <div>
        <h2> 
            Cadastro
        </h2>
    </div>

  <div class="form-group">
    <label for="name">Nome de usuário</label>
    <input type="name" class="form-control" id="name" aria-describedby="emailHelp" placeholder="Insira seu nome">
  </div>

  <div class="form-group">
    <label for="exampleInputEmail1">Endereço de email</label>
    <input type="email" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Seu email">
    <small id="emailHelp" class="form-text text-muted">Nunca vamos compartilhar seu email, com ninguém.</small>
  </div>

  <div class="form-group">
    <label for="exampleInputEmail1">Data de nascimento</label>
    <input type="date" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Seu email">
  </div>

  <div class="form-group">
    <label for="exampleInputPassword1">Senha</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Senha">
  </div>

  <div class="form-group form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Clique em mim</label>
  </div>
  <small id="btnHelper" class="form-text text-muted">Já tem uma conta?</small>
    <div >

        <button type="submit" class="btn btn-primary">Cadastre-se</button>
        <router-link to="/login">
            <button id="btnCadastro" type="link" class="btn btn-primary">Login</button>
        </router-link>

    </div>
</div>

</form>

</template>

<style scoped>
#btnHelper {
margin-left:250px;
}
input {
max-width:400px;
max-height:500px;
background-color: rgb(237, 248)223, ;
}

h2{
margin-left: 120px;
}

#btnCadastro{
margin-left: 168px;
}

form{
margin-top:100px;
}

.container {
background-color: #f7eccb;
max-width: 400px;
max-height:500px;
border-radius: 20px;
}

</style>
