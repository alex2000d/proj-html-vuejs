<script>
export default {

}
</script>
<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="col-3">
                    <div class=" ms-5 align-middle logo-img mt-4 ">
                        <img src="../assets/img/logo.png">
                    </div>

                </div>
                <div class="col-6">
                    <ul class="list-unstyled d-flex mt-3">
                        <li class="green">Home</li>
                        <li>Games</li>
                        <li>Shop</li>
                        <li>Pages</li>
                        <li>Blog</li>
                        <li>Contact</li>
                    </ul>
                </div>
                <div class="col-3">
                    <div class="p-3  align-middle cart-img ">
                        <img src="../assets/img/icon/cart-icon.png" />
                        <button class="btn ms-3">Live streaming</button>
                    </div>

                </div>
            </div>
        </div>
        <div class="container container-one">
            <div class="row">
                <div class="col-5">
                    <div class="content mt">
                       <h3 class="green">Game with live streaming</h3>
                       <h1 class="white fs">Future of <br> Esport</h1>
                       <p class="white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, repudiandae vero sed harum impedit in saepe illo aut tenetur tempore praesentium distinctio ad nesciunt.</p>
                       <img src="../assets/img/game-controler.png" alt="">
                       <button class="button-two">EXPLORE GAMES<i class="fa-solid fa-angles-right ms-3"></i></button>
                       <button class="button-play mx-4"><img src="../assets/img/icon/play-icon.png" alt=""></button>
                    </div>
                </div>
                <div class="col-7">
                    <div class="content-soldier">
                     <img src="../assets/img/index-banner-illus.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>
<style lang="scss" scoped>
.logo-img img {
    max-width: 80px;
}

.cart-img img {
    max-width: 20px;
}

ul {
    li {
        padding: 10px 20px;
        color: white;
        cursor: pointer;
    }
}

.green {
    color: rgb(148, 203, 83)
}

header {
    background-image: url(../assets/img/index-banner-bg.png);
}

.container{
    max-width: 1200px;
}

.container-one{
    max-width: 1100px;
}

.white{
    color: white;
}

.content-soldier img{
    width: 120%;
    object-fit: cover;
}

.content img {
  left: -190px;
 bottom: 130px;
 position: relative;
 width: 300px;
 
}

.mt{
    margin-top: 150px;
}

.fs{
    font-size: 75px;
}

/* From Uiverse.io by cssbuttons-io */ 
button {
    padding: 1.3em 3em;
    font-size: 12px;
    text-transform: uppercase;
    letter-spacing: 2.5px;
    font-weight: 500;
    color: #000;
    background-color: #23c483;
    border: none;
    border-radius: 45px;
    box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease 0s;
    cursor: pointer;
    outline: none;
  }

  .button-two {
    padding: 1.3em 3em;
    font-size: 12px;
    text-transform: uppercase;
    letter-spacing: 2.5px;
    font-weight: 500;
    color: #000;
    background-color: #23c483;
    border: none;
    border-radius: 45px;
    box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease 0s;
    cursor: pointer;
    outline: none;
    left: 18px;
    bottom: 225px;
    position: relative;
  }

  .button-play img{
    width: 20px;
    left: 2px;
    bottom: 0px;
    position: relative;
  }
  

  .button-play{
    left: 18px;
    bottom: 225px;
    position: relative;
    cursor: pointer;
    border-radius: 100px;
    background-color: #ffffff;
    padding: 1.3em 1.6em;
  }

  .button-play:hover{
    background-color: white;
    box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
    color: #23c483;
    transform: translateY(-7px);
  }
  
  button:hover {
    background-color: #23c483;
    box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
    color: #fff;
    transform: translateY(-7px);
  }

  .button-two:hover {
    background-color: #23c483;
    box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
    color: #fff;
  }
    
  
  button:active {
    transform: translateY(-1px);
  }


  .button-two:active {
    transform: translateY(-1px);
  }
</style>