<template>
<img class="logo" src="../assets/logo.png" />
<h1>Sign Up</h1>

<div class="register">
    <input type="text" placeholder="Enter Name" />
    <input type="email" placeholder="Enter Email" />
    <input type="password" placeholder="Enter Password" />
    <button>Sign Up</button>

</div>
</template>

<script>
export default {
    name: 'SignUp'
}
</script>

<style>
.logo {
    width: 200px;
}
.register input {
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-left: auto;
    margin-right: auto;
    border: 1px solid skyblue;
}

.register button {
    width: 320px;
    height: 40px;
    border: 1px solid skyblue;
    background: skyblue;
    color: #fff;
    cursor: pointer;
}
</style>