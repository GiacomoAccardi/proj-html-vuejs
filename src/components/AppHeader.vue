
<script>
export default {
    
}
</script>

<template>
<header>
    <!--sezione superiore dell'header-->
    <div class="header-head">
        <div class="container1200 d-flex layout-db">
            <div class="content d-flex">
                <div class="col-8 layout-db"></div>
                <div class="col-4 layout-db"></div>
            </div>
        </div>
    </div>
    <!--sezioneinferiore dell'header che conterrà logo e menù-->
    <div class="header-bottom">
        <div class="container1200 d-flex layout-db">
            <div class="content d-flex">
                <div class="col-4 layout-db"></div>
                <div class="col-8 layout-db"></div>
            </div>
        </div>
    </div>
</header>
</template>

<style lang="scss">
@use "../styles/partials/variables";

.header-head{
    .container1200{
        height: 40px;
    }
}

.header-bottom{
    .container1200{
        height: 70px;
    }
}

</style>