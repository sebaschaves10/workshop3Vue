<!-- src/components/InfoBar.vue -->

<template>
    <div class="info-bar">
      <p><strong>Nombre del trabajo:</strong> {{ trabajo }}</p>
      <p><strong>Empresa:</strong> {{ empresa }}</p>
      <p><strong>Ciudad:</strong> {{ ciudad }}</p>
      <p><strong>Pago:</strong> {{ pago }}</p>
      <p><strong>Vacante:</strong> {{ vacante }}</p>
      <p><strong>Fecha:</strong> {{ fecha }}</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'InfoBar',
    props: {
      trabajo: String,
      empresa: String,
      ciudad: String,
      pago: String,
      vacante: Number,
      fecha: String,
    },
  };
  </script>
  
  <style scoped>
  .info-bar {
    background-color: #f0f0f0;
    padding: 10px;
    border: 1px solid #ccc;
    margin: 10px;
  }
  </style>
  