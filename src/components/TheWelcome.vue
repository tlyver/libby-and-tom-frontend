<script setup lang="ts">

</script>

<template>
  <div class="home">
    <div class="names">Libby & Tom</div>
    <div class="info">Aug 17, 2024</div>
    <div class="info">Brooklyn, NY</div>
  </div>

  <div class="img-container">
    <img alt="Libby and Tom" class="image" src="@/assets/libby-and-tom-pic.jpg" />
  </div>
</template>

<style>
.home {
  min-height: 90vh;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
}


.info {
  font-size: 30px;
}

.names {
  font-size: 50px;
}

.img-container {
  text-align: center;
}

.image {
  width: -webkit-fill-available
}

@media (min-width: 769px) {
  .names {
    font-size: 75px;
  }
}

@media (min-width: 1024px) {
  .names {
    font-size: 90px;
  }
}

</style>

