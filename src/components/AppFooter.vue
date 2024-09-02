<script>
export default {
    props: {
    footerMenu: {
      type: Array,
      required: true
    }
  }  
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
    <div class="bg-darkgrey">

        <div class="container1200">

            <div class="foot-content d-flex align-center">
                <div class="col-3 d-flex flex-column">
                    <img src="../../public/assets/images/classic_shop_logo2x.png" class="colored" alt="logo">
                    <p>
                        12345 Nort Main Street,<br>
                        New York, NY 555555 <br>
                        Phone:1.800.555.6789 <br>
                        Email: info@company.com <br>
                        Web: Theme-fusion.com
                    </p>
                    <div class="icon-box d-flex">
                        <i class="fa-brands fa-facebook-f"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-youtube"></i>
                    </div>
                </div>
    
                <div class="col-3 featured mr-20">
                    <div class="content">
                        <div class=""><span class="title">TOP RATED</span></div>
    
                    <div class="prod-cell">
                        <div class="d-flex flex-column">
                            <span>Leather Gloves</span>
                            <div class="stars d-flex">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </div>
                            <span class="price">$45</span>
                        </div>
                        <img src="../../public/assets/images/leather_gloves-120x156.jpg" alt="">
                    </div>
    
                    <div class="prod-cell">
                        <div class="d-flex flex-column">
                            <span>Black Leather Jacket</span>
                            <div class="stars d-flex">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </div>
                            <span class="price"><span class="line-through">$235 </span>$200</span>
                        </div>
                        <img src="../../public/assets/images/black_elegant_leather_jacket-120x156.jpg" alt="">
                    </div>
    
                    <div class="prod-cell">
                        <div class="d-flex flex-column">
                            <span>spring Printed Dress</span>
                            <div class="stars d-flex">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </div>
                            <span class="price">$47</span>
                        </div>
                        <img src="../../public/assets/images/spring_printed_dress-120x156.jpg" alt="">
                    </div>
                    </div>
                </div>
    
                <div class="col-3 flex-column featured mr-20">
                    <div class="content">
                        <div class="mb-40"><span class="title">RECENT POSTS</span></div>
    
                        <div class="item">
                            <a>> Lorem ipsum dolor sit amet consec</a>
                        </div>
                        <div class="item">
                            <a>> Lorem ipsum dolor sit amet consec</a>
                        </div>
                        <div class="item">
                            <a>> Lorem ipsum dolor sit amet consec</a>
                        </div>
                        <div class="item">
                            <a>> Lorem ipsum dolor sit amet consec</a>
                        </div>
                        <div class="item">
                            <a>> Lorem ipsum dolor sit amet consec</a>
                        </div>
                        <div class="item">
                            <a>> Lorem ipsum dolor sit amet consec</a>
                        </div>
                    </div>
                </div>
    
                <div class="col-3 d-flex flex-column featured mb-40">
                    <div class="content">
                        <div class="mb-20"><span class="title">TAGS</span></div>
                        <div class="tags d-flex wrap">
                            <div class="lable">Black</div>
                            <div class="lable">boots</div>
                            <div class="lable">Brown</div>
                            <div class="lable">D&G</div>
                            <div class="lable">Flower</div>
                            <div class="lable">grey</div>
                            <div class="lable">Hat</div>
                            <div class="lable">hipster</div>
                            <div class="lable">lines</div>
                            <div class="lable">Multi-purpose</div>
                            <div class="lable">New York</div>
                            <div class="lable">Outdoors</div>
                            <div class="lable">red</div>
                            <div class="lable">responsive</div>
                            <div class="lable">summer</div>
                            <div class="lable">sweater</div>
                            <div class="lable">sweater</div>
                            <div class="lable">Travel</div>
                            <div class="lable">Warm</div>
                            <div class="lable">White</div>
                            <div class="lable">winter</div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>
    <!-- bottom footer -->
    <div class="bg-darker d-flex flex-column align-center justify-center">
        
        <div class="d-flex mt-40 mb-20">
            <div v-for="link in footerMenu">
                <a :href="link.url">{{ link.name }}</a>
            </div>
        </div>

        <div>
            <img src="../../public/assets/images/payment_cards_footer.png" alt="ddd">
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
            border: none;
        }

        .blue-btn{
            padding: 5px 30px;
        }
    }
}

.bg-darkgrey{
    background-color: #2B2E32;
    height: 400px;

    .container1200{

        .foot-content{
            height: 400px;
            margin-left: 50px;

            .colored{
            width: 150px;
            filter: invert(1) brightness(5);
            margin-bottom: 40px;
        }
        p{
            font-size: 10pt;
            color: variables.$almostwhite;
            line-height: 1.8;
            margin-bottom: 40px;
        }
        i{
            color: variables.$almostwhite;
        }

        .featured{
            .content{

                span{
                    color: variables.$almostwhite;
                }
        
                .price{
                    font-weight: bolder;
                }
        
                .line-through{
                    text-decoration: line-through;
                }

                .prod-cell{
                    display: flex;
                    border-bottom: 1px solid variables.$mygrey;
                    justify-content: space-between;
                    padding-bottom: 10px;
                    margin: 15px 0;
        
                    img{
                        width: 50px
                    }

                    i{
                        color: variables.$myblue;
                    }
                }

                .item{
                    border-bottom: 1px solid variables.$mygrey;
                    padding: 11px 0;
                    width: 200px;

                    a{
                        color: variables.$almostwhite;
                        font-size: 9pt;
                        margin: 20px 0;
                    }
                }

                .lable{
                    color: variables.$almostwhite;
                    border: 1px solid variables.$mygrey;
                    padding: 5px;
                    font-size: 10pt;
                }
                .tags{
                    gap: 5px;
                    width: 200px;
                }
            }
        }
            .colored{
                width: 150px;
                filter: invert(1) brightness(5);
                margin-bottom: 40px;
            }
            p{
                font-size: 10pt;
                color: variables.$almostwhite;
                line-height: 1.8;
                margin-bottom: 40px;
            }
            i{
                color: variables.$almostwhite;
            }
    
            .featured{
                .content{
    
                    span{
                        color: variables.$almostwhite;
                    }
            
                    .price{
                        font-weight: bolder;
                    }
            
                    .line-through{
                        text-decoration: line-through;
                    }
    
                    .prod-cell{
                        display: flex;
                        border-bottom: 1px solid variables.$mygrey;
                        justify-content: space-between;
                        padding-bottom: 10px;
                        margin: 15px 0;
            
                        img{
                            width: 50px
                        }
    
                        i{
                            color: variables.$myblue;
                        }
                    }
    
                    .item{
                        border-bottom: 1px solid variables.$mygrey;
                        padding: 11px 0;
                        width: 200px;
    
                        a{
                            color: variables.$almostwhite;
                            font-size: 9pt;
                            margin: 20px 0;
                        }
                    }
    
                    .lable{
                        color: variables.$almostwhite;
                        border: 1px solid variables.$mygrey;
                        padding: 5px;
                        font-size: 10pt;
                    }
                    .tags{
                        gap: 5px;
                        width: 200px;
                    }
                }
            }
        }
    }
}

.bg-darker{
    background-color: #1D1F22;
    padding: 20px 0;

    a{
        color: white;
        margin-right: 10px;
        text-decoration: none;
    }

    .mt-40{
        margin-top: 40px;
    }
}


</style>