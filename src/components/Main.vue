<template>
  <main >
      <div class="background">
          <div class="container">

          </div>
      </div>
      <div class="background-2">
          <div class="container lista-main">

            <ul>
              <li>
                  <a href="#">
                      <img src="@/assets/img/buy-comics-digital-comics.png" alt="Digital Comics">     
                  </a>
                  <p>Digital Comics</p>
              </li>

              <li>
                  <a href="#">
                      <img src="@/assets/img/buy-comics-merchandise.png" alt="Merchandise">     
                  </a>
                  <p>Dc Merchandise</p>
              </li>

               <li>
                  <a href="#">
                      <img src="@/assets/img/buy-comics-subscriptions.png" alt="Subscription">     
                  </a>
                  <p>Dc Merchandise</p>
              </li>

               <li>
                  <a href="#">
                      <img src="@/assets/img/buy-comics-shop-locator.png" alt="Locator">     
                  </a>
                  <p>Comic Shop Locator</p>
              </li>

              <li>
                  <a href="#">
                      <img src="@/assets/img/buy-dc-power-visa.svg" alt="Visa">     
                  </a>
                  <p>Comic Shop Locator</p>
              </li>
            </ul>

          </div>
      </div>
  </main>
</template>

<script>
export default {
    name: 'Main',
}
</script>

<style>
.container{
    max-width: 1170px;
}

.background{
    width: 100%;
    background: #000;
    height: 150px;
    display: block;
}

.background-2{
    width: 100%;
    background: #0c7cec;
    height: 150px;
    font-family: sans-serif;
}

.lista-main ul{
    display: flex;
    justify-content: center;
    padding: 2rem;
}


.lista-main ul li{
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
    text-transform: uppercase;
}

.lista-main ul li a{
    display: flex;

}


.lista-main ul li a img{
    width: 50px;
    
}

.lista-main p{
    margin-left: 1rem;
    margin-right: 1rem;
    font-size: 14px;
}




</style>