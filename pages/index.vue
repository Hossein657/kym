<template>
  <div class="container">
    <header>
      <img src="~/static/logo.png" class="logo" alt="Logo">
      <h1>KYM | Know Your Music</h1>
      <img src="~/static/bulb.svg" class="bulb" alt="change dark mode">
    </header>
    <main>
      <form>
      <div>

        <input type="text" class="form-input" placeholder="What are you looking for?">
        <button type="submit" class="form-btn">
          <img src="~/static/search.svg" alt="">
        </button>
      </div>
      </form>
    </main>
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
/* header styles */
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

/* form styles */
form{
  /* position: absolute;
  top: 40%; */
  margin: 0 auto;

}
form > div{
  background-color:black;
  /* display: inline-block; */
  /* width: 80vw; */
  text-align: center;
}
.form-input{
  border: 0;
  background-image: linear-gradient(to bottom, #fb531c, #f98c29);
  padding:13px;
  border-radius: 60px;
  width: 80vw;
  filter: drop-shadow(-4px 0 10px rgb(23, 23, 23,0.25));
}
.form-btn{
  background-color: #f2f2f2;
  border: 0;
  border-radius: 60px;
  padding: 13px 30px;
  filter: drop-shadow(-4px 0 10px rgb(46, 46, 46,0.25));
  position: absolute;
  right: -10px;
}
::placeholder{
    color: rgba(255, 255, 255, 0.5);
}
</style>