<script>
export default {
    
}
</script>

<template>
<footer>
    <!-- brand logos -->
     <div class="bg-light">
        <div class="container1200">
            <div class="content d-flex flex-column">
                <span>BRAND LOGOS</span>
                <div class="d-flex around">
                    <img src="../../public/assets/images/b_logotype_6.png" alt="">
                    <img src="../../public/assets/images/b_logotype_7.png" alt="">
                    <img src="../../public/assets/images/b_logotype_1.png" alt="">
                    <img src="../../public/assets/images/b_logotype_2.png" alt="">
                    <img src="../../public/assets/images/b_logotype_3.png" alt="">
                </div>
            </div>
        </div>
     </div>
    <!-- subscribe! -->
    <div>
        <div class="container1200">
            <div class="content d-flex">
                <div class="col-12 h-100 layout-db"></div>
            </div>
        </div>
    </div>
    <!-- main footer -->
    <div>
        <div class="container1200">
            <div class="content d-flex">
                <div class="col-12 h-400 layout-db"></div>
            </div>
        </div>
    </div>
    <!-- bottom footer -->
    <div>
        <div class="container1200">
            <div class="content d-flex">
                <div class="col-12 h-75 layout-db"></div>
            </div>
        </div>
    </div>
</footer>
</template>

<style lang="scss">
@use "../styles/partials/variables";

.h-50{
    height: 50px;
}

.h-100{
    height: 150px;
}

.h-75{
    height: 75px;
}

.bg-light{
    background-color: variables.$almostwhite;
    height: 250px;

    .content{
        height: 250px;
        align-items: center;
        justify-content: center;

        span{
            color: variables.$mygrey;
            margin-bottom: 10px;
        }

        .around{
            width: 100%;
            justify-content: space-around;
        }
    }
}
</style>