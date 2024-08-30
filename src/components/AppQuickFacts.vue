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
                    <h1 class="text-white">Futio Quick Facts</h1>
                 </div>
               </div>
            </div>
            <div class="row py-5">
                <div class="col-3">
                  <div class="content-live text-center text-white py-2">
                     <h1>1135</h1>
                     <p class="green">Twitch streams</p>
                  </div>
                </div>
                <div class="col-3">
                    <div class="content-live text-center text-white py-2">
                        <h1>44</h1>
                        <p class="green">Total Games</p>
                    </div>
                </div>
                <div class="col-3">
                    <div class="content-live text-center text-white py-2">
                        <h1>982</h1>
                        <p class="green">YouTube Streams</p>
                    </div>
                </div>
                <div class="col-3">
                    <div class="content-live text-center text-white py-2">
                        <h1>40</h1>
                        <p class="green">Pro Teams</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
    .bg{
        background-color: black;
    }

    .width{
         max-width: 1000px;
    }

    .content-live{
        border: 1px solid white;
        border-radius: 20px;
        margin-top: 20px;
    }

    .green {
        color: rgb(148, 203, 83)
    }
</style>