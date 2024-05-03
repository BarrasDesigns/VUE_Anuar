<template>
  <div class="component">
    <div class="objectfit">

      <img src="../assets/nene1.jpeg" class="fotoNene" alt="fotoNene">
    </div>
    <div class="title">

      <h1>Anuar Barrera</h1>
      <h2 class="fuzzy-bubbles-regular">Autismo</h2>
    </div>
  </div>
</template>
<style>
.title{
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
h1 {
  background-color: red;
  color: yellow;
  padding: 20px;
  border-radius: 7px;
}

h2 {
  background-color: blue;
  color: white;
  padding: 20px;
  border-radius: 7px;
}

/* CUSTOM FOTO */
.objectfit {
  display: flex;
  justify-content: center;
}

.objectfit>.fotoNene {
  width: 11rem;
  height: 11rem;
  object-fit: cover;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
  border-radius: 50%;
  background-color: black;
  border: 3px solid #b20000;
}

.nombre_puesto {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>