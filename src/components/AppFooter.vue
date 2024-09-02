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
    <div class="bg-grey1">
        <div class="container1200">
            <div class="content d-flex align-center">
                <div class="d-flex align-center">
                    <div class="icon d-flex align-center">
                        <i class="fa-regular fa-envelope"></i>
                    </div>
                    <h2>Subscribe now and get special offers</h2>
                </div>
                <div>
                    <input type="email" class="email" placeholder="Insert your email">
                    <button class="blue-btn">SEND</button>
                </div>
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

.bg-grey1{
    background-color: #303337;
    height: 175px;

    .content{
        height: 175px;
        justify-content: space-around;

        .icon{
            height: 50px;
            width: 50px;
            background-color: #2B2E32;
            border-radius: 30px;
            margin-right: 25px;

            i{
                color: variables.$mylightgrey;
                font-size: 18pt;
                margin-left: 13px;
            }
            
        }

        h2{
            color: white;
        }

        .email{
            border-radius: 20px;
            padding: 5px;
            width: 200px;
            margin-top: 10px;
            margin-right: 20px;
        }

        .blue-btn{
            padding: 5px 30px;
        }
    }
}
</style>