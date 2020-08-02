<template>
    <h1 class="message">{{message}}</h1>
</template>

<script>
export default {
    name: "myname",
    props:{
        message: String,
    }
}
</script>

<style>

body{
    box-sizing: border-box;
    height: 100vh;
    padding: auto;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: center;
}

</style>