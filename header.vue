<template>
    <div id="app">
        <h1>{{ message }}</h1>
    </div>
</template>

<script>
    var app= new vue({
    el: '#app',
    data: {
    message: 'Hello World'
    }
    })
</script>

<style>
    h1 {
    color:#ff0000;
    }
</style>