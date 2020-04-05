<template>
  <div class="container-fluid">
    <section id="cont" class="pb-5">
      <h1 class="display-3 text-center"><b>Contato</b></h1>
    </section>
    <form action="#" id="contato" method="post">
    <fieldset>
        <fieldset class="grupo">
            <div class="campo">
                <label for="nome">Nome</label>
                <input type="text" id="nome" name="nome" style="width: 10em" value="">
            </div>
            <div class="campo">
                <label for="snome">Sobrenome</label>
                <input type="text" id="sobrenome" name="snome" style="width: 10em" value="">
            </div>
        </fieldset>
        <div class="campo">
            <label for="email">E-mail</label>
            <input type="text" id="email" name="email" style="width: 20em" value="">
        </div>
        <div class="campo">
            <label for="telefone">Telefone</label>
            <input type="text" id="telefone" name="telefone" style="width: 15em" value="">
        </div>
        <div class="campo">
            <label for="mensagem">Mensagem</label>
            <textarea rows="6" style="width: 20em" id="mensagem" name="mensagem"></textarea>
        </div>
        <button type="submit" class="btn btn-dark" name="envia">Enviar</button>
        <button type="reset" class="btn btn-dark" name="apaga">Limpar</button>
    </fieldset>
</form>
  </div>
</template>
<style>
* {
    margin:initial;
}

body, input, select, textarea, button {
    font-family:sans-serif;
    font-size:larger;
}
.campo {
    margin-bottom: 2em;
}

.campo label {
    margin-bottom: 0.2em;
    color: rgb(109, 107, 107);
    display:inline-block;
}

fieldset.grupo .campo {
    float: left;
    margin-right: 2em;
}

.campo input[type="text"],
.campo input[type="email"],
.campo input[type="tel"],
.campo textarea {
    padding: 0.2em;
    border: 2px solid rgb(197, 193, 193);
    box-shadow: 2px 2px 2px rgba(0,0,0,0.2);
    display: block;
}
.campo input:focus, .campo textarea:focus {
    background: #FFC;
}
</style>
