<script setup>
const incrementar (){
  
}
</script>

<template>
  <div class="wrapper">
    <svg id="icon" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
      stroke="currentColor" class="w-6 h-6">
      <path stroke-linecap="round" stroke-linejoin="round"
        d="M17.982 18.725A7.488 7.488 0 0012 15.75a7.488 7.488 0 00-5.982 2.975m11.963 0a9 9 0 10-11.963 0m11.963 0A8.966 8.966 0 0112 21a8.966 8.966 0 01-5.982-2.275M15 9.75a3 3 0 11-6 0 3 3 0 016 0z" />
    </svg>
    <div id="globito">
      10
    </div>
    
  </div>
  <br>

  <span class="button">
    -
  </span> 
  
  <span class="button">
    +
  </span>
  

</template>

<style scoped>
#icon {
  width: 60px;

}

#globito {
  background-color: brown;
  height: 24px;
  width: 24px;
  border-radius: 100%;
  text-align: center;
  position: absolute;
  top: -12px;
  right: -12px;

}

.wrapper {

  display: inline-block;
  position: relative;
}

.button {
  display: inline-block;
  background-color: rgb(7, 71, 49);
  color: rgb(43, 134, 15);
  width: 30 px;
  height: 30 px;
  text-align: center;
  border-radius: 20%;
  margin: 10px;
}
.button:hover{
  background-color: rgb(153, 14, 14);
  color: black;
  cursor: pointer;
}
.button:active{
  background-color: darkmagenta;
  color: black;
  cursor: pointer;
}
</style>
