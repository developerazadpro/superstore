<template>
  <div id="app">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">        
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Superstore <span class="sr-only">(current)</span></a>
            </li>
            
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
          </form>
        </div>
      </nav>


      <div class="container">
        <div class="row">
            <div class="col-sm-9">
              <div class="row">
                  <div class="card" style="width: 15rem;">
                      <img src="https://i1.adis.ws/i/canon/eos-r5_martin_bissig_lifestyle_05_c629aad3c2154f34b3d7d7ba5a509196?$70-30-header-4by3-dt-jpg$" class="card-img-top" alt="cart-img">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                      </div>
                  </div>

                  <div class="card" style="width: 15rem;">
                      <img src="https://i1.adis.ws/i/canon/eos-r5_martin_bissig_lifestyle_05_c629aad3c2154f34b3d7d7ba5a509196?$70-30-header-4by3-dt-jpg$" class="card-img-top" alt="cart-img">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                      </div>
                  </div>

                  <div class="card" style="width: 15rem;">
                      <img src="https://i1.adis.ws/i/canon/eos-r5_martin_bissig_lifestyle_05_c629aad3c2154f34b3d7d7ba5a509196?$70-30-header-4by3-dt-jpg$" class="card-img-top" alt="cart-img">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                      </div>
                  </div><div class="card" style="width: 15rem;">
                      <img src="https://i1.adis.ws/i/canon/eos-r5_martin_bissig_lifestyle_05_c629aad3c2154f34b3d7d7ba5a509196?$70-30-header-4by3-dt-jpg$" class="card-img-top" alt="cart-img">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                      </div>
                  </div>

                  <div class="card" style="width: 15rem;">
                      <img src="https://i1.adis.ws/i/canon/eos-r5_martin_bissig_lifestyle_05_c629aad3c2154f34b3d7d7ba5a509196?$70-30-header-4by3-dt-jpg$" class="card-img-top" alt="cart-img">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                      </div>
                  </div>

                  <div class="card" style="width: 15rem;">
                      <img src="https://i1.adis.ws/i/canon/eos-r5_martin_bissig_lifestyle_05_c629aad3c2154f34b3d7d7ba5a509196?$70-30-header-4by3-dt-jpg$" class="card-img-top" alt="cart-img">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                      </div>
                  </div>
              </div>
            </div>
            <div class="col-sm-3 card-item">
                <ul class="list-group">
                      <li class="list-group-item">Item - Price</li>
                      <li class="list-group-item">Item - Price</li>
                      <li class="list-group-item">Item - Price</li>
                </ul>
            </div>
        </div>
        
      </div>
  </div>
</template>

<script>
  export default {
    name: 'app'
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