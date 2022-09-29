<template>
  <div id="app" class="app">
    <div class="header">
      <h1>Tu Tienda</h1>
    </div>

    <div class="main-component">
      <router-vie>

      </router-vie>
    </div>


  </div>
  
</template>
<script>
export default {
  name: 'App',
  data: function() {

  },
  methods: {

  },
  crated: function() {

  }
}
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto');
  body {
    margin:0;
    font-family: 'Roboto', 'sans serif';
  }
  .header {
    margin:0;
    padding: 0;
    width: 100%;
    height: 10vh;
    min-height: 100px;
    background-color: #283747;
    color: #E5E7E9;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .header h1{
    width: 20%;
    text-align: center;
  }
</style>
