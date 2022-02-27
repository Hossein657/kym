<template>
  <form @submit.prevent="">
    <div class="test">
      <input type="text" class="form-input" placeholder="What are you looking for?">
      <button type="submit" class="form-btn">
        <img src="~/static/search.svg" alt="">
      </button>
    </div>
  </form>
</template>

<script>
export default {

}
</script>

<style>
form{
  position: relative;
  width: 95%;
  margin: 0 auto;
  margin-top: 5vh;
}

.form-input{
  border: 0;
  background-image: linear-gradient(to bottom, #fb531c, #f98c29);
  padding:13px;
  border-radius: 60px;
  width: 100%;
  filter: drop-shadow(-4px 0 10px rgb(23, 23, 23,0.25));
  padding-left: 20px;
  color: #fff;
}
.form-btn{
  background-color: #f2f2f2;
  border: 0;
  border-radius: 60px;
  padding: 13px 30px;
  /* filter: drop-shadow(-4px 0 10px rgb(46, 46, 46,0.25)); */
  position: absolute;
  right: 0px;
}
::placeholder{
    color: rgba(255, 255, 255, 0.5);
}
input:focus, button:focus{
  outline: none;
}
</style>