<template>
    <!-- menu nav -->
    <div class="menu-nav">
        <span class="menu-header">Menu <i class="fa fa-bars"></i></span>
        <ul class="menu-list">
            <li><a href="#">Home</a></li>
            <li><a href="#">Shop</a></li>
            <li class="dropdown mega-dropdown"><a class="dropdown-toggle" data-toggle="dropdown" aria-expanded="true">Women <i class="fa fa-caret-down"></i></a>
                <div class="custom-menu">
                    <div class="row">
                        <div class="col-md-4">
                            <ul class="list-links">
                                <li>
                                    <h3 class="list-links-title">Categories</h3></li>
                                <li><a href="#">Women’s Clothing</a></li>
                                <li><a href="#">Men’s Clothing</a></li>
                                <li><a href="#">Phones & Accessories</a></li>
                                <li><a href="#">Jewelry & Watches</a></li>
                                <li><a href="#">Bags & Shoes</a></li>
                            </ul>
                            <hr class="hidden-md hidden-lg">
                        </div>
                        <div class="col-md-4">
                            <ul class="list-links">
                                <li>
                                    <h3 class="list-links-title">Categories</h3></li>
                                <li><a href="#">Women’s Clothing</a></li>
                                <li><a href="#">Men’s Clothing</a></li>
                                <li><a href="#">Phones & Accessories</a></li>
                                <li><a href="#">Jewelry & Watches</a></li>
                                <li><a href="#">Bags & Shoes</a></li>
                            </ul>
                            <hr class="hidden-md hidden-lg">
                        </div>
                        <div class="col-md-4">
                            <ul class="list-links">
                                <li>
                                    <h3 class="list-links-title">Categories</h3></li>
                                <li><a href="#">Women’s Clothing</a></li>
                                <li><a href="#">Men’s Clothing</a></li>
                                <li><a href="#">Phones & Accessories</a></li>
                                <li><a href="#">Jewelry & Watches</a></li>
                                <li><a href="#">Bags & Shoes</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="row hidden-sm hidden-xs">
                        <div class="col-md-12">
                            <hr>
                            <a class="banner banner-1" href="#">
                                <img :src="image_5" alt="image 5">
                                <div class="banner-caption text-center">
                                    <h2 class="white-color">NEW COLLECTION</h2>
                                    <h3 class="white-color font-weak">HOT DEAL</h3>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>
            </li>
            <li class="dropdown mega-dropdown full-width"><a class="dropdown-toggle" data-toggle="dropdown" aria-expanded="true">Men <i class="fa fa-caret-down"></i></a>
                <div class="custom-menu">
                    <div class="row">
                        <div class="col-md-3">
                            <div class="hidden-sm hidden-xs">
                                <a class="banner banner-1" href="#">
                                    <img :src="image_6" alt="image 6">
                                    <div class="banner-caption text-center">
                                        <h3 class="white-color text-uppercase">Women’s</h3>
                                    </div>
                                </a>
                                <hr>
                            </div>
                            <ul class="list-links">
                                <li>
                                    <h3 class="list-links-title">Categories</h3></li>
                                <li><a href="#">Women’s Clothing</a></li>
                                <li><a href="#">Men’s Clothing</a></li>
                                <li><a href="#">Phones & Accessories</a></li>
                                <li><a href="#">Jewelry & Watches</a></li>
                                <li><a href="#">Bags & Shoes</a></li>
                            </ul>
                        </div>
                        <div class="col-md-3">
                            <div class="hidden-sm hidden-xs">
                                <a class="banner banner-1" href="#">
                                    <img :src="image_7" alt="image 7">
                                    <div class="banner-caption text-center">
                                        <h3 class="white-color text-uppercase">Men’s</h3>
                                    </div>
                                </a>
                            </div>
                            <hr>
                            <ul class="list-links">
                                <li>
                                    <h3 class="list-links-title">Categories</h3></li>
                                <li><a href="#">Women’s Clothing</a></li>
                                <li><a href="#">Men’s Clothing</a></li>
                                <li><a href="#">Phones & Accessories</a></li>
                                <li><a href="#">Jewelry & Watches</a></li>
                                <li><a href="#">Bags & Shoes</a></li>
                            </ul>
                        </div>
                        <div class="col-md-3">
                            <div class="hidden-sm hidden-xs">
                                <a class="banner banner-1" href="#">
                                    <img :src="image_8" alt="image 8">
                                    <div class="banner-caption text-center">
                                        <h3 class="white-color text-uppercase">Accessories</h3>
                                    </div>
                                </a>
                            </div>
                            <hr>
                            <ul class="list-links">
                                <li>
                                    <h3 class="list-links-title">Categories</h3></li>
                                <li><a href="#">Women’s Clothing</a></li>
                                <li><a href="#">Men’s Clothing</a></li>
                                <li><a href="#">Phones & Accessories</a></li>
                                <li><a href="#">Jewelry & Watches</a></li>
                                <li><a href="#">Bags & Shoes</a></li>
                            </ul>
                        </div>
                        <div class="col-md-3">
                            <div class="hidden-sm hidden-xs">
                                <a class="banner banner-1" href="#">
                                    <img :src="image_9" alt="image 9">
                                    <div class="banner-caption text-center">
                                        <h3 class="white-color text-uppercase">Bags</h3>
                                    </div>
                                </a>
                            </div>
                            <hr>
                            <ul class="list-links">
                                <li>
                                    <h3 class="list-links-title">Categories</h3></li>
                                <li><a href="#">Women’s Clothing</a></li>
                                <li><a href="#">Men’s Clothing</a></li>
                                <li><a href="#">Phones & Accessories</a></li>
                                <li><a href="#">Jewelry & Watches</a></li>
                                <li><a href="#">Bags & Shoes</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </li>
            <li><a href="#">Sales</a></li>
            <li class="dropdown default-dropdown"><a class="dropdown-toggle" data-toggle="dropdown" aria-expanded="true">Pages <i class="fa fa-caret-down"></i></a>
                <ul class="custom-menu">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="products.html">Products</a></li>
                    <li><a href="product-page.html">Product Details</a></li>
                    <li><a href="checkout.html">Checkout</a></li>
                </ul>
            </li>
        </ul>
    </div>
    <!-- menu nav -->

</template>

<script>
export default {
    name: "Menu",
    data(){
        return {
            image_5 : "assets/img/banner05.jpg",
            image_6 : "assets/img/banner06.jpg",
            image_7 : "assets/img/banner07.jpg",
            image_8 : "assets/img/banner08.jpg",
            image_9 : "assets/img/banner09.jpg"
        }
    }
}
</script>

<style scoped>

</style>
