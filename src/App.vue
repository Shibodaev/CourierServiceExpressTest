<template lang="pug">
div( id="app" lang="pug")
    .container
        .row.column
            h1 {{hello}}


<script>

import Post from './components/BlogPost.vue'
import Counter from './components/Counter.vue'

export default {
    name: "App",
    components: {
    },
    data() {
        return {
            hello: "Hello world!!!",
            counter: 0
        }
    }
};
</script>

<style lang="scss">
@import "~normalize.css";

body {
    font-family: "Robobo";
    font-size: 16px;
    overflow-x: hidden;
}


@import '"https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap"';

#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}
</style>
