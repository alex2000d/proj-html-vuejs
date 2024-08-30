<script>
export default {

}
</script>
<template>
    <div class="container-fluid container-one bg-black">
        <div class="row">
            <div class="col-6">
                <div class="content-feature">
                 <img src="../assets/img/features-illus.png" alt="">
                </div>
            </div>
            <div class="col-5">
                <div class="content mt">
                    <h4 class="green">The Ultimate competitive gaming platform</h4>
                    <h3 class="white fs">Make your mark on <br> the battle field</h3>
                    <p class="white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, repudiandae vero sed harum impedit in saepe illo aut tenetur tempore praesentium distinctio.</p>
                    <div class="row">
                        <div class="col-2 mt-3 feature-icon">
                            <img src="../assets/img/icon/features-icon-1.png">
                        </div>
                        <div class="col-10">
                            <h3 class="white">Live streaming</h3>
                            <p class="white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, repudiandae vero sed harum impedit in saepe illo aut tenetur.</p>
                        </div>
                        <div class="col-2 mt-3 feature-icon">
                            <img src="../assets/img/icon/features-icon-2.png">
                        </div>
                        <div class="col-10">
                            <h2 class="white">Great tournament</h2>
                            <p class="white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, repudiandae vero sed harum impedit in saepe illo aut tenetur.</p>
                        </div>
                        <div class="col-2 mt-3 feature-icon">
                            <img src="../assets/img/icon/features-icon-3.png">
                        </div>
                        <div class="col-10">
                            <h2 class="white">Gaming news</h2>
                            <p class="white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, repudiandae vero sed harum impedit in saepe illo aut tenetur.</p>
                            <button class="btn">PLAY NOW</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>


.content-feature img{
    width: 100%;
    position: relative;
    right: 35px;
    padding: 70px 0px;
    
}

.feature-icon img{
    width: 60px;
}

.mt{
    margin-top: 40px;
}

.green {
    color: rgb(148, 203, 83)
}

.white{
    color: white;
}

.fs{
    font-size: 60px;
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