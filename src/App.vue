<template>
  <div id="app">
    <h1>Hello World</h1>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
  }

  body {
    color: #ffffff;
    background: linear-gradient(to right, rgb(21, 153, 87), rgb(21,87,153))
  }

  #app {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #app h1 {
    border: 1px solid #000;
    background-color: #0004;
    padding: 20px;
    margin-bottom: 68px;
  }
</style>
