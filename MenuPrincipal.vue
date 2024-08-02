<template>
    <div id="app">
      <router-view></router-view>
    </div>
  </template>
  
  <script>
  export default {
    name: 'App'
  };
  </script>
  
  <style>
  /* estilos do seu app */
  </style>
  /** */
  <template>
    <nav>
      <router-link to="/videos">Vídeos Diversos</router-link>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'NavigationComponent'
  };
  </script>
  
  <style>
  /* estilos do componente de navegação */
  </style>