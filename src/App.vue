<template>
  <header>
    <div class="header">
      <h1 style="text-align:left;">TITULO</h1>
    </div>
  </header>

  <body>

    <div class="box">
      <div class="test">
        <div class="box-inputs">
          <input class="input">
          <input class="input">
          <button class="button">sadad</button>
        </div>
      </div>
    </div>


  </body>
</template>



<script>
export default {
  name: 'CenteredText'
}

</script>


<style scoped>
.header {
  text-align: center;
  padding-top: 1px;
  background-color: darkgray;
}

.box-inputs {
  background-color: red;
  width: 500px;
  height: 600px;
  margin-top: 5%;
  margin-left: 23%;
  border-radius: 10%;
  display: flex;
  flex-direction: column;

}

.test {
  margin-top: 10px;
  background-color: aqua
}

.text {}

.input {
  margin-top: 20%;
  border-radius: 10px;
  height: 25px;
}

.button {
  height: 30px;
  margin-top: 30px;
}
</style>