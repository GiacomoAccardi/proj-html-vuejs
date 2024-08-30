
<script>
export default {
  props: {
    //trasmnetto di dati dell'array in App.vue qui per poter popolare dinamicamente le voci del menu 
    headerMenu: {
      type: Array,
      required: true
    }
  }
}
</script>

<template>
<header>
    <!--sezione superiore dell'header-->
    <div class="header-head">
        <div class="container1200 d-flex">
            <div class="content d-flex">
                <div class="col-8 d-flex flex-row align-center ps-10">
                    <div class="icon-box d-flex">
                        <i class="fa-brands fa-facebook-f"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-youtube"></i>
                    </div>
                    <span>Shopping Cart</span>
                </div>
                <div class="col-4 d-flex">
                    <div class="ps-10 d-flex cell-20 align-center simple-box">
                        <span class="mr-10">My Account</span>
                        <span>&#9013;</span>
                    </div>
                    <div class="d-flex cell-80 align-center">
                        <i class="fa-solid fa-cart-shopping"></i>
                        <p class="mr-10">CART</p>
                        <span>&#9013;</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!--sezioneinferiore dell'header che conterrà logo e menù-->
    <div class="header-bottom">
        <div class="container1200 d-flex">
            <div class="content d-flex">
                <div class="col-4 d-flex align-center">
                    <img src="../../public/assets/images/classic_shop_logo1x.png" alt="logo-hdr">
                </div>
                <div class="col-8">
                    <div class="h-70 d-flex align-center">

                        <ul class="d-flex" v-for="link in headerMenu">
                            <li><a :href="link.url">{{ link.name }}</a></li>
                            <span class="margin-menu-10">&#9013;</span>
                        </ul>
                        
                        <button class="blue-btn">SHOP NOW!</button>

                        <i class="fa-solid fa-magnifying-glass"></i>

                    </div>
                </div>
            </div>
        </div>
    </div>
</header>
</template>

<style lang="scss">
@use "../styles/partials/variables";

span{
    font-size: 10pt;
    color: variables.$mylightgrey;
}

.cell-80{
    padding: 0 88px;
    background-color: variables.$almostwhite;
} 

.cell-20 {
    border-right: 1px solid variables.$mylightgrey;
    border-left: 1px solid variables.$mylightgrey;
}

i{
    margin-right: 10px;
    color: variables.$mygrey;
}

.header-head{
    border: 1px solid variables.$mylightgrey;
    .container1200{
        height: 40px;

        .col-8{
            justify-content: space-between;
        }

        .col-4{
            p{
                color: variables.$mygrey;
            }
        }
    }
}

.header-bottom{

    .margin-menu-10 {
        margin: 0 30px 0 5px;
    }

    .h-70{
        height: 70px;
    }

    .container1200{
        height: 70px;

        ul{
            list-style: none;

            a{
                text-decoration: none;
                color: variables.$mylightgrey;
                font-size: 10pt;
            }
        }

        i{
            font-size: 10pt;
        }
        
        button{
            margin: 0 55px;
        }
    }
}

</style>