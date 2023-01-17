<template>
  <div>
    <!-- Main header-->
    <header class="main-header header-style-three">

        <!--Start Header--> 
        <div class="header header--style3">
            <div class="auto-container">
                <div class="outer-box">
                    <div class="header-left">
                        <div class="logo">
                            <a href="index.html"><img src="assets/images/resources/logo.png" alt="Awesome Logo" title=""></a>
                        </div>
                    </div>

                    <div class="header-middle">
                        <div class="nav-outer style1 clearfix">
                            <!--Mobile Navigation Toggler-->
                            <div class="mobile-nav-toggler">
                                <div class="inner">
                                    <span class="icon-bar"></span>
                                    <span class="icon-bar"></span>
                                    <span class="icon-bar"></span>
                                </div>
                            </div>
                            <!-- Main Menu -->
                            <nav class="main-menu style1 navbar-expand-md navbar-light">
                                <div class="collapse navbar-collapse show clearfix" id="navbarSupportedContent">

                                    <ul class="navigation clearfix scroll-nav">
                                        <li><a href="#banner">Home</a></li>
                                        <li><a href="#about">About Us</a></li>
                                        <li><a href="#projects">Projects</a></li>
                                        <li><a href="#blog">Blog</a></li>
                                        <li><a href="#contact">Contact</a></li>
                                        <li class="dropdown"><a href="#">Pages</a>
                                            <ul>
                                                <li><a href="index.html">Home Page 01</a></li>
                                                <li><a href="index-2.html">Home Page 02</a></li>
                                                <li><a href="index-3.html">Home Page 03</a></li>
                                                <li><a href="index-onepage.html">Home OnePage</a></li>
                                            </ul>
                                        </li>
                                    </ul>

                                </div>
                            </nav>                        
                            <!-- Main Menu End-->
                        </div>
                    </div> 

                    <div class="header-right">
                        <div class="serach-button-style1">
                            <button type="button" class="search-toggler"><i class="icon-search"></i></button>
                        </div>
                        <div class="thm-space-box-2"></div>
                        <div class="header-right_buttom">
                            <div class="btns-box">
                                <a class="btn-one" href="contact.html">
                                    <span class="txt">Get A Quote</span>
                                </a>
                            </div>
                        </div> 
                    </div>

                </div>
            </div>    
        </div> 
        <!--End header-->

        <!--Sticky Header-->
        <div class="sticky-header">
            <div class="container">
                <div class="clearfix">
                    <!--Logo-->
                    <div class="logo float-left">
                        <a href="index.html" class="img-responsive"><img src="assets/images/resources/sticky-logo.png" alt="" title=""></a>
                    </div>
                    <!--Right Col-->
                    <div class="right-col float-right">
                        <!-- Main Menu -->
                        <nav class="main-menu clearfix">
                        <!--Keep This Empty / Menu will come through Javascript-->
                        </nav>   
                    </div>
                </div>
            </div>
        </div>
        <!--End Sticky Header-->
        
        <!-- Mobile Menu  -->
        <div class="mobile-menu">
            <div class="menu-backdrop"></div>
            <div class="close-btn"><span class="icon fa fa-times-circle"></span></div>
            <nav class="menu-box">
                <div class="nav-logo"><a href="index.html"><img src="assets/images/resources/mobilemenu-logo.png" alt="" title=""></a></div>
                <div class="menu-outer"><!--Here Menu Will Come Automatically Via Javascript / Same Menu as in Header--></div>
                <!--Social Links-->
                <div class="social-links">
                    <ul class="clearfix">
                        <li><a href="#"><span class="fab fa fa-facebook-square"></span></a></li>
                        <li><a href="#"><span class="fab fa fa-twitter-square"></span></a></li>
                        <li><a href="#"><span class="fab fa fa-pinterest-square"></span></a></li>
                        <li><a href="#"><span class="fab fa fa-google-plus-square"></span></a></li>
                        <li><a href="#"><span class="fab fa fa-youtube-square"></span></a></li>
                    </ul>
                </div>
            </nav>
        </div>
        <!-- End Mobile Menu --> 
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>
