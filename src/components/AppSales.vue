<script>
export default {
    
}
</script>
<template>
    <div class="bg-black">
        <div class="container width">
            <div class="row">
                <div class="col-12">
                    <div class="content mt-5">
                        <img src="../assets/img/banner-item-bg.png">
                        <p class="text-white text-center position">Make offer</p>
                        <h1 class="text-white text-center position">Get 70% Offer Discount</h1>
                        <img class="position-phone" src="../assets/img/banner-item-obj1.png">
                        <img class="position-headphones" src="../assets/img/banner-item-obj2.png">
                        <button class="button position-button">GET OTHERS<i class="fa-solid fa-arrow-down ms-3"></i></button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.width{
    max-width: 1000px;
    overflow: hidden;
}

.content img{
    height: 275px;
    position: relative;
    
}

.position{
    position: relative;
    top: -205px;
}

.position-phone{
    position: relative;
    top: -370px;
    left: 80px;
    width: 15%;
}

.position-headphones{
    position: relative;
    top: -370px;
    left: 620px;
    width: 15%;
}

.position-button{
    position: relative;
    top: -315px;
    left: 85px;
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
    box-shadow: 0px 15px 20px rgba(229, 141, 46, 0.4);
    color: #fff;
    transform: translateY(-7px);
  }
</style>