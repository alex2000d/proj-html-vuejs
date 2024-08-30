<script>
export default {
    
}
</script>
<template>
    <div class="bg">
        <div class="container width">
            <div class="row">
                <div class="col-12">
                    <div class="content text-center mt-5">
                        <h3 class="green">Treding Battle</h3>
                        <h1 class="text-white">Keep Eyes & Manage</h1>
                        <h1 class="text-white">Upcoming Battle</h1>
                        <p class="text-white">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Mollitia architecto tempora assumenda molestiae soluta eligendi expedita ducimus. Similique tempora impedit consectetur eaque fugit, a molestiae obcaecati placeat nobis</p>
                    </div>
                </div>
            </div>
            <div class="container">
                <div class="row">
                    <div class="col-6">
                       <div class="content-battle">
                         <img class=" padding img " src="../assets/img/battle-team-4.png">
                         <img class="px-4" src="../assets/img/verus-icon.png">
                         <img class="p-3 img-two" src="../assets/img/game-img-2.png">
                         <div class="content-information pd-15 text-center ">
                          <h3 class="text-white">Call of Deauty</h3>
                          <p class="green">December 25, 2022 4:00 PM</p>
                         </div>
                         <div class="content-social pd-15 text-center ">
                            <img src="../assets/img/icon/youtube-icon.png">
                            <span class="text-white pe-4">YouTube</span>
                            <img src="../assets/img/icon/twitch-icon.png">
                            <span class="text-white">Twitch</span>
                           </div>
                       </div>
                    </div>
                    <div class="col-6">
                        <div class="content-battle">
                            <img class=" padding img " src="../assets/img/game-img-3.png">
                            <img class="px-4" src="../assets/img/verus-icon.png">
                            <img class="p-3 img-two" src="../assets/img/game-img-4.png">
                            <div class="content-information pd-15 text-center ">
                             <h3 class="text-white">Legendary Battle</h3>
                             <p class="green">December 25, 2022 4:00 PM</p>
                            </div>
                            <div class="content-social pd-15 text-center ">
                               <img src="../assets/img/icon/youtube-icon.png">
                               <span class="text-white pe-4">YouTube</span>
                               <img src="../assets/img/icon/twitch-icon.png">
                               <span class="text-white">Twitch</span>
                              </div>
                        </div>
                    </div>
                 </div>
             </div>
             <div class="container mt-4">
                <div class="row">
                    <div class="col-6">
                       <div class="content-battle">
                         <img class=" padding img " src="../assets/img/game-img-5.png">
                         <img class="px-4" src="../assets/img/verus-icon.png">
                         <img class="p-3 img-two" src="../assets/img/game-img-6.png">
                         <div class="content-information pd-15 text-center ">
                          <h3 class="text-white">Nay Corral Gundown</h3>
                          <p class="green">December 25, 2022 4:00 PM</p>
                         </div>
                         <div class="content-social pd-15 text-center ">
                            <img src="../assets/img/icon/youtube-icon.png">
                            <span class="text-white pe-4">YouTube</span>
                            <img src="../assets/img/icon/twitch-icon.png">
                            <span class="text-white">Twitch</span>
                           </div>
                       </div>
                    </div>
                    <div class="col-6">
                        <div class="content-battle">
                            <img class=" padding img " src="../assets/img/game-img-7.png">
                            <img class="px-4" src="../assets/img/verus-icon.png">
                            <img class="p-3 img-two" src="../assets/img/game-img-8.png">
                            <div class="content-information pd-15 text-center ">
                             <h3 class="text-white">League of Legends</h3>
                             <p class="green">December 25, 2022 4:00 PM</p>
                            </div>
                            <div class="content-social pd-15 text-center ">
                               <img src="../assets/img/icon/youtube-icon.png">
                               <span class="text-white pe-4">YouTube</span>
                               <img src="../assets/img/icon/twitch-icon.png">
                               <span class="text-white">Twitch</span>
                              </div>
                        </div>
                    </div>
                    <div class="button-center py-5">
                        <button class="btn">View all match</button>
                    </div>
                 </div>
             </div>
         </div>
     </div>
     
</template>
<style lang="scss" scoped>
    .bg{
        background-color: rgb(33, 39, 51);
    }

    .green {
        color: rgb(148, 203, 83)
    }

    .content-battle{
        border: 1px solid rgb(159, 157, 157);
        border-radius: 20px;
        background-color: rgb(40, 52, 74);
        height: 350px;
    }

    .img{
        width: 40%;
    }

    .img-two{
        width: 23%;
    }
    

    .content-information{
        background-color: rgb(48, 65, 95);
    }

    .content-social{
        background-color: rgb(40, 52, 74);
    }

    .padding{
        padding: 15px 10px 20px 65px;
    }

    .width{
        max-width: 1000px;
    }
    
    .button-center{
        align-items: center;
        justify-content: center;
        display: flex;
    }

    .pd-15{
        padding: 15px;
    }

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

      button:hover {
        background-color: #23c483;
        box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
        color: #fff;
        transform: translateY(-7px);
      }

      button:active {
        transform: translateY(-1px);
      }
</style>