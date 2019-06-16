<template>
<div class="container">
      <ul>comment</ul>
      <ul>information</ul>
      <ul>goods</ul>
      <img src="../assets/ICON.png">
      <ul>contact</ul>
      <ul>love</ul>
      <ul>shop cart</ul>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.container{
    width: 100%;
    height: 25vh;
    background-color: #f88e7b;
    display: flex;
    justify-content:space-around;
    align-items:center;
}

ul{
    list-style-type: none;
    margin: 4vw;
    padding: 0;
    font-family: 'Baskerville';
}

img{
    width: 5%;
}

/* -------------------rwd------------------- */

@media screen and (max-width: 400px){
.container{
    width: 100%;
    height: 10vh;
    background-color: #f88e7b;
    display: flex;
    justify-content:space-around;
    align-items:center;
}

ul{
    list-style-type: none;
    padding: 0;
    font-family: 'Baskerville';
    font-size: 8px;
}

img{
    width: 10%;
}


}
</style>
