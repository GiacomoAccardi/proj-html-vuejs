<script>
export default {
    
}
</script>

<template>
<main>
    
    <!--new arrival's-->
    <div>
        <div class="container1200">
            <div class="content d-flex flex-column h-400 layout-db"></div>
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

</style>