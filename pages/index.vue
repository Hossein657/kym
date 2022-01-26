<template>
  <div class="container">
    <header>
      <img src="~/static/logo.png" class="logo" alt="Logo">
      <h1>KYM | Know Your Music</h1>
      <img src="~/static/bulb.svg" class="bulb" alt="change dark mode">
    </header>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container{
  margin: 15px;
  font-family: 'Roboto', sans-serif;
}
header{
  display: flex;
  align-items: center;
}
h1{
  font-weight: normal;
  font-size: 16px;
}
.logo{
  width: 40px;
  margin-right: 10px;
}
.bulb{
  margin-left: auto;
}

</style>