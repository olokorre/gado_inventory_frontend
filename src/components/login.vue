<template>
    <div id="login">
        <h1>Entre no sistema!</h1>
        <p>Entre com as suas credenciais</p>
        <input placeholder="Email" type="email" />
        <br />
        <input placeholder="Senha" type="password" />
        <br />
        <button v-on:click="alert('cu')">Entrar</button>
    </div>
</template>

<script>
export default {
    name: "Login"
}
</script>

<style scoped>
input, button {
    margin-top: 10px;
    position: relative;
    border-color: #b13030;
    border-radius: 2%;
}

button {
    background-color: #b13030;
    border:none;
    padding: 5px;
    color:white;
}

h1 { color: #b13030; }

#login {
    text-align: center;
    margin-top: 160px;
}
</style>