<script>
export default {
    
}
</script>
<template>
    <div class="bg">
        <div class="container width position-streaming ">
            <div class="row">
                <div class="col-12">
                    <div class="content text-center">
                        <h3 class="green mt-2">Live streaming</h3>
                        <h1 class="text-white fs">Watch the streams</h1>
                        <p class="text-white">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Mollitia architecto tempora assumenda molestiae soluta eligendi expedita ducimus. Similique tempora impedit consectetur.</p>
                        <img class="video" src="../assets/img/video-bg.png">
                        <button class="button-play mx-4"><img src="../assets/img/icon/play-icon.png" alt=""></button>
                        <h4 class="position text-white">League of Legends</h4>
                        <button class="btn position-live"> <i class="fa-solid fa-podcast"></i>Live</button>
                         <div class="d-flex position-like">
                            <p class="green me-2">356,599</p>
                            <p class="text-white me-3">Viewers</p>
                            <p class="green me-2">23,789</p>
                            <p class="text-white">Likes</p>
                         </div>
                    </div>
                </div>
              </div>
           </div>
      </div>
</template>
<style lang="scss" scoped>
    .bg {
        background-image: url(../assets/img/live-streaming-bg.png);
        background-position-x: center;
    }

    .green {
        color: rgb(148, 203, 83)
    }

    .text-white{
        color: rgb(219, 223, 224);
    }

    .width{
        max-width: 1000px;
        overflow: hidden;
    }

    .fs{
        font-size: 35px;
    }

    .video{
        width: 80%;
        position: relative;
        right: -55px;
        top: 30px;
    }

    .button-play img{
        width: 20px;
        left: 2px;
        bottom: 0px;
        position: relative;
      }

      button {
        padding: 0.5em 2em;
        font-size: 12px;
        text-transform: uppercase;
        letter-spacing: 2.5px;
        font-weight: 500;
        color: #000;
        background-color:rgb(255, 154, 47);
        border: none;
        border-radius: 45px;
        box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
        transition: all 0.3s ease 0s;
        cursor: pointer;
        outline: none;
      }
      
    
      .button-play{
        left: -375px;
        bottom: 15px;
        position: relative;
        cursor: pointer;
        border-radius: 100px;
        background-color: #ffffff;
        padding: 1.3em 1.6em;
        transition: all 0.3s ease 0s;
      }
    
      .button-play:hover{
        background-color: white;
        box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
        color: #23c483;
        transform: translateY(-7px);
      }
      
      button:hover {
        background-color: rgb(255, 154, 47);
        box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
        color: #fff;
        transform: translateY(-7px);
      }

      .position{
        position: relative;
        left: 20px;
        bottom: 200px;
      }

    .position-live{
        left: 335px;
        bottom: 430px;
        position: relative;
    }

    
    .position-like{
        left: 135px;
        bottom: 90px;
        position: relative;
    }

    .position-streaming{
        position: relative;
        bottom: -70px;
    }
</style>