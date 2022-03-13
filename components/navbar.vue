<template>
  <header>
      <img src="~/static/logo.png" class="logo" alt="Logo">
      <h1>KYM | Know Your Music</h1>
      <img src="~/static/bulb.svg" class="bulb" alt="change dark mode">
  </header>
</template>

<style>
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
@media (min-width: 481px){
  h1{
    font-size: 20px;
  }
  .logo{
    width: 60px;
  }
  .bulb{
    width: 40px;
  }
}

</style>