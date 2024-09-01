<script>
export default {
    
}
</script>
<template>
    <div class="bg-black">
        <div class="container position width">
            <div class="row">
                <div class="col-12">
                    <div class="content text-center mt-5">
                        <h3 class="green">Latest News</h3>
                        <h1 class="text-white fs">Stay Update With Our</h1>
                        <h1 class="text-white fs">Latest News Articles</h1>
                        <p class="text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laborum aspernatur porro dolorem doloremque hic id, libero, quis repellat sint praesentium tempore dolorum. Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-6">
                    <div class="bg-blue mt-5">
                      <img class="content-gamers" src="../assets/img/blog-item-10.png">
                      <div class="p-4">
                        <img src="../assets/img/icon/clock.png">
                        <span class="green mx-2 me-4">10 min</span>
                        <img src="../assets/img/icon/eye.png">
                        <span class="green mx-2 me-4">240</span>
                        <img src="../assets/img/icon/calendar.png">
                        <span class="green mx-2">11 Aprli,2022</span>
                        <h2 class="text-white fs-text mt-3">Secret To An Amazing Role Playing Game</h2>
                      </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="content mt-5">
                        <div class="row">
                            <div class="col-12 feature-icon bg-blue d-flex">
                                <img class="content-gamer position-img" src="../assets/img/blog-item-2.png">
                                    <div class="p-2 fsi">
                                        <img src="../assets/img/icon/clock.png">
                                        <span class="green mx-2 me-3">10 min</span>
                                        <img src="../assets/img/icon/eye.png">
                                        <span class="green mx-2 me-3">240</span>
                                        <img src="../assets/img/icon/calendar.png">
                                        <span class="green mx-2">11 Aprli,2022</span>
                                        <h4 class="text-white mt-3">Top 5 Most Important Aspect Of Your Game</h4>
                                   </div>
                            </div>
                            <div class="col-12 feature-icon bg-blue d-flex mt-2">
                                <img class="content-gamer position-img" src="../assets/img/blog-item-3.png">
                                <div class="p-2 fsi">
                                     <img src="../assets/img/icon/clock.png">
                                     <span class="green mx-2 me-3">10 min</span>
                                     <img src="../assets/img/icon/eye.png">
                                     <span class="green mx-2 me-3">240</span>
                                     <img src="../assets/img/icon/calendar.png">
                                     <span class="green mx-2">11 Aprli,2022</span>
                                     <h4 class="text-white mt-3">The Rise Of Fantasy Sport And Online Games</h4>
                                </div>
                            </div>
                            <div class="col-12 feature-icon bg-blue d-flex mt-2">
                                <img class="content-gamer position-img" src="../assets/img/blog-item-4.png">
                                <div class="p-2 fsi">
                                    <img src="../assets/img/icon/clock.png">
                                    <span class="green mx-2 me-3">10 min</span>
                                    <img src="../assets/img/icon/eye.png">
                                    <span class="green mx-2 me-3">240</span>
                                    <img src="../assets/img/icon/calendar.png">
                                    <span class="green mx-2">11 Aprli,2022</span>
                                    <h4 class="text-white mt-3">Benefits Of Gaming - PC And Video Games</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
    .position{
        position: relative;
        top: -330px;
    }

    .width{
        max-width: 1000px;
        overflow: hidden;
    }

    .green {
        color: rgb(148, 203, 83)
    }

    .fs{
        font-size: 60px;
    }

    .fsi{
        font-size: 13px;
        margin-top: 10px;
    }

    .fs-text{
        font-size: 27px;
    }

    .bg-blue{
        background-color:rgb(40, 52, 74);
        border-radius: 20px;
        max-height: max-content;
    }

    .content-gamers{
        width: 100%;
        object-fit: fill;
        border-radius: 20px;
    }

    .content-gamer{
        width: 35%;
        object-fit: fill;
        border-radius: 20px;
    }
    
    .position-img{
        left: -12px;
        position: relative;
    }

</style>