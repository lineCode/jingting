<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
  export default {
    name: 'jingting'
  }
</script>

<style>
  /* CSS */
* {
  transition: all 0.3s ease;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

::selection {
  background-color: #17a2b8;
  color: #fff;
}

::-webkit-scrollbar {
  width: 0.3rem;
}

html,
body,
#app {
  height: 100%;
  overflow: hidden;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Microsoft YaHei";
  user-select: none;
  -webkit-app-region: drag;
  overflow: hidden;
}

input,
a,
button {
  -webkit-app-region: no-drag;
}

a {
  text-decoration: none;
}
</style>
