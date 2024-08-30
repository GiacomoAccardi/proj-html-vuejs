<script>
export default {
    
}
</script>

<template>
<main>
    
    <!--new arrival's-->
    <div class="brand-jumbo ">
        <div class="container1200">
            <div class="content d-flex flex-column align-center">
                <h1>Brand New Arrivals</h1>
                <span>NEW COLLECTION FROM NEW YORK</span>
                <div class="d-flex">
                    <button class="btn-glassy mr-20">VIEW ALL</button>
                    <button class="btn-glassy">LOOKBOOK</button>
                </div>
            </div>
        </div>
    </div>

    <!-- fetured products -->
    <div class="container1200 layout-db">
        <div class="content d-flex flex-column h-400 layout-db mt-100 mb-100"></div>
    </div>

    <!-- collections -->
    <div>
        <div class="content h-400 d-flex">
            <div class="col-4 layout-db"></div>
            <div class="col-4 layout-db"></div>
            <div class="col-4 layout-db"></div>
        </div>
    </div>

    <!-- bestseller -->
    <div>
        <div class="container1200">
            <div class="content d-flex flex-column h-400 layout-db mt-100"></div>
        </div>
    </div>

    <!-- discount and free shipping -->
    <div>
        <div class="container1200 d-flex h-400 layout-db">
            <div class="col-12 d-flex align-center g-100">
                <div class="box layout-db"></div>
                <div class="box layout-db"></div>
            </div>
        </div>
    </div>

    <!-- new arrivals -->
    <div>
        <div class="layout-db">
            <div class="content d-flex flex-column h-400 layout-db mt-100 mb-100"></div>
        </div>
    </div>

    <!-- quote -->
    <div>
        <div class="container1200">
            <div class="content d-flex flex-column h-400 layout-db"></div>
        </div>
    </div>

    <!-- from our blog -->
    <div>
        <div>
            <div class="container1200">
                <div class="content d-flex flex-column h-400 layout-db mt-100"></div>
            </div>
        </div>
    </div>

    <!-- featured, on sale, top rated, latest reviews -->
                <!--popolerò dinamicamente questa sezione-->
    <div>
        <div class="container1200">
            <div class="content d-flex flex-column h-400 layout-db"></div>
        </div>
    </div>

</main>

</template>

<style lang="scss">
@use "../styles/partials/variables";

.p-updwn100{
    padding: 100px 0;
}

.box{
    height: 300px;
    width: calc(100% / 2);
}

.brand-jumbo{
    background-image: url(../assets/images/home1_slide_three_bg_2.jpg);
    background-size: contain;
    background-size: 100%;
    background-repeat: no-repeat;

    .content{
        padding: 185px 0;

        h1{
            color: white;
            font-size: 50pt ;
        }

        span {
            font-size: 16pt;
            margin: 10px 0 20px;
        }

        .btn-glassy{
            background-color: rgba(255, 255, 255, 0.158);
            color: white;
            padding: 10px 25px;
            border: 2px solid white;
            border-radius: 20px;
        }
    }


}

</style>