<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
* {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-family: Verdana, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    color: #000;
}

html {
    scroll-behavior: smooth;
}

ul {
    list-style: none;
}

a {
    text-decoration: none;
}

img {
    max-width: 100%;
    display: block;
}

.container {
    max-width: 1150px;
    margin: 0 auto;
    padding: 0 10px;
}

#app {
    display: flex;
    /* min-height: 105vh; */
    flex-direction: column;
}
</style>
