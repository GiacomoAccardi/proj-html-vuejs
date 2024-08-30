<script>
export default {
    
}
</script>

<template>
<main>
    
    <!--new arrival's-->
    <div class="brand-jumbo">
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
    <div class="featured-products">
        <div class="container1200">
            <div class="content d-flex flex-column align-center">
                <h1>Featured Products</h1>
                <span>Must have products from our top sellers</span>
                <div class="selection-box d-flex">
                    <div class="cell br-mygrey bg-white">Man</div>
                    <div class="cell br-mygrey">Woman</div>
                    <div class="cell">Accessories</div>
                </div>
                <div class="prod-box d-flex">
                    <div class="cell">
                        <img src="../assets/images/black_elegant_leather_jacket.jpg" alt="p1">
                        <h4>Black Leather Jacket</h4>
                        <span>Men, Jackets, Jeans</span>
                        <p><span>$235 </span>$200</p>
                    </div>
                    <div class="cell">
                        <img src="../assets/images/black_leather_suit.jpg" alt="p2">
                        <h4>Black Leather suit</h4>
                        <span>Men, Jackets</span>
                        <p>$176</p>
                    </div>
                    <div class="cell">
                        <img src="../assets/images/blue_jacket_and_white_stripe_tee.jpg" alt="p3">
                        <h4>Blue Jacket & stripe tee</h4>
                        <span>Men, Jackets, Suits</span>
                        <p>$580</p>
                    </div>
                    <div class="cell">
                        <img src="../assets/images/modern_black_leather_suit.jpg" alt="p4">
                        <h4>Modern Black Leather suit</h4>
                        <span>Men, Jackets</span>
                        <p>$96</p>
                    </div>
                </div>
            </div>
        </div>
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

.featured-products{
    padding: 100px 0;
    position: relative;

    .content{
        border-top: 1px solid variables.$mylightgrey;

        h1{
            position: absolute;
            top: 80px;
            background-color: white;
            width:400px;
            text-align: center;
        }

        span{
            margin-top: 25px;
            color: variables.$mygrey;
        }

        .selection-box{
            width: 500px;
            height: 50px;
            margin-top: 50px;
            background-color: variables.$almostwhite;
            border: 1px solid variables.$mylightgrey;

            .cell{
                width: calc(100% / 3);
                display: flex;
                align-items: center;
                justify-content: center;
            }

            .br-mygrey{
                border-right: 1px solid variables.$mylightgrey;
            }

            .bg-white{
                background-color: white;
            }
        }

        .prod-box{
            width: 100%;
            margin-top: 50px;

            .cell{
                width: calc(100% / 4);
                display: flex;
                flex-direction: column;

                img{
                    object-fit: contain;
                }

                h4{
                    margin-top: 20px;
                }

                span {
                    margin-top: 10px;
                    color: variables.$mylightgrey;
                }

                p{
                    margin-top: 20px;
                    color: variables.$myblue;

                    span{
                        color: variables.$myblue;
                        text-decoration: line-through; 
                    }
                }
            }
        }
    }
}

</style>