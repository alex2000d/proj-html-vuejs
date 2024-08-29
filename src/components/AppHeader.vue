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
                        <li class="active">Home</li>
                        <li>Games</li>
                        <li>Shop</li>
                        <li>Pages</li>
                        <li>Blog</li>
                        <li>Contact</li>
                    </ul>
                </div>
                <div class="col-3">
                    <div class="p-3  align-middle cart-img mt-2">
                        <img src="../assets/img/icon/cart-icon.png" />
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
    }
}

.active {
    color: rgb(148, 203, 83)
}

header {
    background-image: url(../assets/img/index-banner-bg.png);
}
</style>