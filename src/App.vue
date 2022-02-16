<template>
  <div id="app">
      
      <Navbar></Navbar>

      <div class="container">
        <div class="row">
            <div class="col-sm-9">
                <Inventory></Inventory>
            </div>
            <div class="col-sm-3 card-item">
                <Cart></Cart>
            </div>
        </div>
        
      </div>
  </div>
</template>

<script>
  import Navbar from './components/Navbar'
  import Inventory from './components/Inventory'
  import Cart from './components/Cart'

  export default {
    name: 'app',

    components:{
      Navbar,
      Inventory,
      Cart
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  .container, .card-item{
    padding-top: 10px;
  }
  .card{
    margin:10px;
  }
  

  @import'~bootstrap/dist/css/bootstrap.css'
</style>