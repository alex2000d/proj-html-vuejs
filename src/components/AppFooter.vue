<script>
export default {

}
</script>
<template>
    <div class="bg-blue">
        <div class="container width position-input">
            <div class="row">
                <div class="col-12">
                    <div class="content bg-blues py-5">
                       <div class="row">
                        <div class="col-7">
                            <div class="content">
                               <h2 class="text-white mx-5">Subcsribe Newsletter</h2>
                               <p class="text-white mx-5">Lorem ipsum, dolor sit amet consectetur<br> adipisicing elit. Quidem voluptate</p>
                            </div>
                        </div>
                        <div class="col-5">
                            <div class="content mt-4">
                                <input class="bg-blue p-3 width-input" type="email" placeholder="enter your mail">
                                <button class="button-play mx-4"><img src="../assets/img/icon/send-icon.png" alt=""></button>
                            </div>
                        </div>
                       </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container width">
            <div class="row">
                <div class="col-4 mt-3">
                    <div class="content margin">
                       <img src="../assets/img/logo.png">
                       <p class="text-white my-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt doloribus</p>
                       <i class="fa-brands fa-youtube mx-3" style="color: #ffffff;"></i>
                       <i class="fa-brands fa-twitch" style="color: #ffffff;"></i>
                       <i class="fa-brands fa-facebook mx-3" style="color: #ffffff;"></i>
                       <i class="fa-brands fa-instagram" style="color: #ffffff;"></i>
                    </div>
                </div>
                <div class="col-8 d-flex mt-3">
                    <div class="content mx-5 margin">
                         <ul class="text-white list-unstyled">
                            <li><h3>Quick Link</h3></li>
                            <li><p>Gamers</p></li>
                            <li><p>Latest Tournament</p></li>
                            <li><p>Shop</p></li>
                            <li><p>Blog</p></li>
                            <li><p>Contact</p></li>
                         </ul>
                    </div>
                    <div class="content margin">
                        <ul class="text-white list-unstyled">
                           <li><h3>Help</h3></li>
                           <li><p>Faqs</p></li>
                           <li><p>Terms & Conditions</p></li>
                           <li><p>Privacy</p></li>
                           
                        </ul>
                   </div>
                   <div class="content mx-4 margin">
                    <ul class="text-white list-unstyled">
                       <li><h3>Follow Us</h3></li>
                       <li><p>Facebook</p></li>
                       <li><p>Twitter</p></li>
                       <li><p>Instagram</p></li>
                       <li><p>YouTube</p></li>
                       <li><p>Github</p></li>
                    </ul>
               </div>
               <div class="content margin">
                <ul class="text-white list-unstyled">
                   <li><h3>Contact</h3></li>
                   <li><p class="green">Location:</p></li>
                   <li><p>4 Mayfield, Buckden, PE195SZ</p></li>
                   <li><p class="green">Phone:</p></li>
                   <li><p>(302)555-0107</p></li>
                </ul>
           </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
    .bg-blue{
        background-color:rgb(40, 52, 74);
    }

    .width{
        max-width: 1000px;
        overflow: hidden;
    }

    .green {
        color: rgb(148, 203, 83)
    }

    .margin{
        margin-top: 10px;
    }

    

    .bg-blues{
        background-color:rgb(48, 65, 94);
        border-radius: 20px;
        max-height: max-content;
    }

    
    .button-play{
        left: 270px;
        bottom: 50px;
        position: relative;
        cursor: pointer;
        border-radius: 100px;
        background-color: rgb(148, 203, 83);
        padding: 0.3em 0.5em;
        transition: all 0.3s ease 0s;
      }

      .button-play:hover{
        background-color: gray;
        box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
        color: #23c483;
        transform: translateY(-7px);
      }

      .width-input{
        width: 360px;
        border-radius: 10px;
    }

    .position-input{
        position: relative;
        top: -130px;
    }

   
</style>