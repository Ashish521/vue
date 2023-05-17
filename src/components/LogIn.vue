<template>
    <img src="../assets/logo1.png">
    <h3>LogIn</h3>
    <div class="authentication">
        <input type="text" placeholder="Enter Email">
        <input type="password" placeholder="Enter Password">
        <button>Log In</button>
    </div>
</template>
<script>
export default {
    name: 'LogIn'
} 
</script>

<style>
 .authentication input{
    width: 300px;
    height: 40px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 20px;
 }

 .authentication button{
    width: 250px;
    height: 40px;
    background-color:  brown;
 }
</style>