<template>
            <footer id="footer" class="section section-grey">
                <div class="container" >
                    <div class="row">
                        <div class="col-md-3 col-sm-6 col-xs-6">
                            <div class="footer">
                                <div class="footer-logo">
                                    <a class="logo" href="#">
                                        <img @click="divolte" :src="image_logo" alt="">
                                    </a>
                                </div>

                                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna</p>

                                <ul class="footer-social">
                                   <li><a href="#"><i class="fa fa-facebook"></i></a></li>
                                    <li><a href="#"><i class="fa fa-twitter"></i></a></li>
                                    <li><a href="#"><i class="fa fa-instagram"></i></a></li>
                                    <li><a href="#"><i class="fa fa-google-plus"></i></a></li>
                                    <li><a href="#"><i class="fa fa-pinterest"></i></a></li>
                                </ul>
                            </div>
                        </div>

                        <div class="col-md-3 col-sm-6 col-xs-6">
                            <div class="footer">
                                <h3 class="footer-header">My Account</h3>
                                <ul class="list-links">
                                    <li><a href="#">My Account</a></li>
                                    <li><a href="#">My Wishlist</a></li>
                                    <li><a href="#">Compare</a></li>
                                    <li><a href="#">Checkout</a></li>
                                    <li><a href="#">Login</a></li>
                                </ul>
                            </div>
                        </div>

                        <div class="clearfix visible-sm visible-xs"></div>

                        <div class="col-md-3 col-sm-6 col-xs-6">
                            <div class="footer">
                                <h3 class="footer-header">Customer Service</h3>
                                <ul class="list-links">
                                    <li><a href="#">About Us</a></li>
                                    <li><a href="#">Shiping & Return</a></li>
                                    <li><a href="#">Shiping Guide</a></li>
                                    <li><a href="#">FAQ</a></li>
                                </ul>
                            </div>
                        </div>

                        <div class="col-md-3 col-sm-6 col-xs-6">
                            <div class="footer">
                                <h3 class="footer-header">Stay Connected</h3>
                                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor.</p>
                                <form>
                                    <div class="form-group">
                                        <input class="input" placeholder="Enter Email Address">
                                    </div>
                                    <button class="primary-btn">Join Newslatter</button>
                                </form>
                            </div>
                        </div>
                    </div>


                </div>

            </footer>
</template>

<script>
export default {
    name: "Footer",
    data(){
      return {
          image_logo : "assets/img/logo.png"
      }
    },
    methods : {
        divolte(){
          divolte.signal('event',{"title": "click start","type":"iyi"});
          console.log("test deneme");
        },
    }
}
</script>

<style scoped>

</style>
