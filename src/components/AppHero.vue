<script>
export default {
  name: "AppHero"
}
</script>

<template>

  <div class="hero">
    <h2>
      questo è un JUMBOTRON!
    </h2>
  </div>

</template>

<style scoped>
.hero {
  background-image: url(../assets/faccie-sfondo.jpg);
  background-position: center;
  background-repeat: repeat;
  background-size: contain;

  height: 100px;
  font-size: 50px;
  line-height: 90px;
}

h2{
  color: chocolate;
  animation: muovi 1s linear infinite;
}

@keyframes muovi {
    0% {
        font-size: 50px;
      }
      50% {
        font-size: 60px;
    }
    100% {
      font-size: 50px;
    }
}






</style>
