<template>
  <div>
    <header class="header container">
        <div class="header__left">
            <a href="index.html" class="header__logo"><img src="../src/assets/img/logo.jpg" alt="logo"> Bran<span>d</span></a>
            <form class="header__search">
                <div class="header__browse">Browse <i class="fas fa-caret-down"></i></div>
                <input name="search" type="text" placeholder="Search for Item...">
                <button><i class="fas fa-search"></i></button>
            </form>
        </div>
        <div class="header__right">
            <a href="#" class="header__cart"><img src="../src/assets/img/cart.jpg" alt="cart"></a>
            <a href="Checkout.html" class="header__account-bar">My account <i class="fas fa-caret-down"></i></a>
        </div>
    </header>
    <div class="header__line"></div>
    <div class="main__menu">
        <a href="index.html">Home</a>
        <a href="#">Man</a>
        <a href="#" class="main__menu-active">Women</a>
        <a href="#">Kids</a>
        <a href="#">Accoseriese</a>
        <a href="#">Featured</a>
        <a href="#">Hot Deals</a>
    </div>
    <div class="shoppingCart__topMenu">
        <div class="shoppingCart__topMenu-contente container">
            <div class="shoppingCart__topMenu-contente-left">New Arrivals</div>
            <div class="shoppingCart__topMenu-contente-right">
                <a href="#" class="">Home </a> /
                <a href="#">Men </a> /
                <div class="shoppingCart__topMenu-active"><a href="#">New Arrivals</a></div>
            </div>
        </div>
    </div>
    <div class="SinglePage__mainImg">
            <div class="SinglePage__mainImg-turn"><a href="#"><i class="fas fa-chevron-left"></i></a></div>
            <img src="../src/assets/img/SPmainImg2.jpg" alt="girl" class="SinglePage__mainImg-Img">
            <div class="SinglePage__mainImg-turn"><a href="#"><i class="fas fa-chevron-right"></i></a></div>
    </div>
    <div class="SinglePage__mainImg-information container">
            <div class="SinglePage__mainImg-information-slider-caption">WOMEN COLLECTION</div>
            <div class="SinglePage__mainImg-information-sliderbox">
                <a href="#" class="SinglePage__mainImg-information-slider"></a>
                <a href="#" class="SinglePage__mainImg-information-slider-main"></a>
                <a href="#" class="SinglePage__mainImg-information-slider"></a>
            </div>
            <div class="SinglePage__mainImg-information-caption">Moschino Cheap And Chic</div>
            <div class="SinglePage__mainImg-information-description-main">Compellingly actualize fully researched processes before proactive outsourcing. Progressively syndicate collaborative architectures before cutting-edge services. Completely visualize parallel core competencies rather than exceptional portals.</div>
            <div class="SinglePage__mainImg-information-description">
                <div class="SinglePage__mainImg-information-description-part">MATERIAL:<span> COTTON</span></div>
                <div class="SinglePage__mainImg-information-description-part">DESIGNER:<span> BINBURHAN</span></div>
            </div>
            <div class="SinglePage__mainImg-information-price">$561</div>
            <div class="SinglePage__mainImg-information-line"></div>
            <div class="SinglePage__mainImg-information-buttons">
                <div class="SinglePage__mainImg-information-buttons-form">CHOOSE COLOR
                    <div class="SinglePage__mainImg-information-buttons-form-long">
                        <div class="SinglePage__mainImg-information-buttons-form-box">
                            <div class="SinglePage__mainImg-information-buttons-form-colorbox"></div>
                        </div>
                        <select id="color" placeholder="Red">
                            <option label="Red" value="red"></option>
                            <option label="Green" value="green"></option>
                            <option label="Blue" value="blue"></option>
                            <option label="Darkbrown" value="darkbrown"></option>
                        </select>
                    </div>
                </div>
                <div class="SinglePage__mainImg-information-buttons-form">CHOOSE SIZE
                    <select id="size" placeholder="XXL">
                        <option label="XL" value="XL"></option>
                        <option label="L" value="L"></option>
                        <option label="M" value="M"></option>
                    </select>
                </div>
                <div class="SinglePage__mainImg-information-buttons-form-right">QUANTITY
                    <input type="text" id="itemsQuantity" placeholder="2">
                </div>
            </div>
            <button><img src="../src/assets/img/pinkcart.jpg" alt="cart"> <span>Add to Cart</span></button>
    </div>
    <div class="featuredItems container">
        <div class="featuredItems__title">you may like also</div>
        <div class="catalogBar container" id="catalog">
          
        </div>
        <div class="SinglePage__catalogBar-margin"></div>
    </div>
    <footer>
        <div class="subscribe">
            <div class="subscribe__contente container">
                <div class="subscribe__contente-left">
                    <div class="subscribe__icon"><img src="../src/assets/img/subscribe_icon.jpg" alt="author"></div>
                    <div class="subscribe__contente-left-text">
                        <div class="subscribe__contente-left-message">
                            “Vestibulum quis porttitor dui! Quisque viverra nunc mi, a pulvinar purus condimentum a. Aliquam condimentum mattis neque sed pretium”
                        </div>
                        <div class="subscribe__contente-left-author">
                            Bin Burhan <span>Dhaka, Bd</span>
                        </div>
                        <div class="subscribe__contente-left-lines">
                            <div class="subscribe__contente-left-line1"></div>
                            <div class="subscribe__contente-left-line2"></div>
                            <div class="subscribe__contente-left-line3"></div>
                        </div>
                    </div>
                </div>
                <div class="subscribe__contente-right">
                    <div class="subscribe__contente-right-formCapture">
                        <div class="subscribe__contente-right-formCaptureHeader">Subscribe</div>
                        <span>FOR OUR NEWLETTER AND PROMOTION</span>
                    </div>
                    <form class="subscribe__contente-right-form">
                        <input name="email" type="text" placeholder="Enter Your Email">
                        <button>Subscribe</button>
                    </form>
                </div>

            </div>

        </div>
        <div class="contacts">
            <div class="contacts__contente container">
                <div class="contacts__contente-left">
                    <a href="index.html" class="header__logo"><img src="../src/assets/img/logo.jpg" alt="logo"> Bran<span>d</span></a>
                    <div class="contacts__contente-left-text">
                        Objectively transition extensive data rather than cross functional solutions. Monotonectally syndicate multidisciplinary materials before go forward benefits. Intrinsicly syndicate an expanded array of processes and cross-unit partnerships. <br><br>
                        Efficiently plagiarize 24/365 action items and focused infomediaries.
                        Distinctively seize superior initiatives for wireless technologies. Dynamically optimize.<br>

                        Objectively strategize seamless relationships via resource sucking testing procedures. Proactively cultivate next-generation results for value-added methodologies. Dynamically plagiarize unique methodologies after performance based methodologies. Monotonectally empower stand-alone mindshare rather than ubiquitous opportunities. Dynamically orchestrate resource sucking scenarios after alternative synergy.

                        Compellingly envisioneer corporate methods of empowerment before standards compliant technologies. Objectively facilitate progressive.
                    </div>
                </div>
                <div class="contacts__contente-right">
                    <div class="contacts__contente-right-column">
                        <span>COMPANY</span>
                        <div class="contacts__contente-right-column-menu">
                            <a href="#">Home</a>
                            <a href="#">Shop</a>
                            <a href="#">About</a>
                            <a href="#">How It Works</a>
                            <a href="#">Contact</a>
                        </div>
                    </div>
                    <div class="contacts__contente-right-column">
                        <span>INFORMATION</span>
                        <div class="contacts__contente-right-column-menu">
                            <a href="#">Tearms &amp; Condition</a>
                            <a href="#">Privacy Policy</a>
                            <a href="#">How to Buy</a>
                            <a href="#">How to Sell</a>
                            <a href="#">Promotion</a>
                        </div>
                    </div>
                    <div class="contacts__contente-right-column">
                        <span>SHOP CATEGORY</span>
                        <div class="contacts__contente-right-column-menu">
                            <a href="#">Men</a>
                            <a href="#">Women</a>
                            <a href="#">Child</a>
                            <a href="#">Apparel</a>
                            <a href="#">Brows All</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="footer__contente container">
                <div class="footer__contente-left">
                    &copy; 2017  Brand  All Rights Reserved.
                </div>
                <div class="footer__contente-right">
                    <a href="#"><i class="fab fa-facebook-f"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    <a href="#"><i class="fab fa-pinterest-p"></i></a>
                    <a href="#"><i class="fab fa-google-plus-g"></i></a>
                </div>
            </div>
        </div>
    </footer>
</div>
</template>

<script>
// @ is an alias to /src
import Catalog from '@/components/Catalog.vue';
import Basket from '@/components/Basket.vue';

export default {
    name: 'Home',
    components: { Catalog, Basket },
    data() {
        return {
            showBasket: false
        }
    },
    methods: {
        get(url) {
            return fetch(url)
                .then(data => data.json())
        },
    },
    mounted() {
        console.log(this);
    }
}
</script>
