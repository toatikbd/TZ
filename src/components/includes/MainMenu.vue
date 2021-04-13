<template>
    <div class="main-menu-primary">
        <div class="main-menu col-lg-6 col-md-7 ">
            <div class="responsive so-megamenu megamenu-style-dev">
                <nav class="navbar-default">
                    <div class=" container-megamenu  horizontal open ">
                        <div class="navbar-header">
                            <button type="button" id="show-megamenu" data-toggle="collapse" class="navbar-toggle">
                                <span class="icon-bar"></span>
                                <span class="icon-bar"></span>
                                <span class="icon-bar"></span>
                            </button>
                        </div>
                        <div class="megamenu-wrapper">
                            <span id="remove-megamenu" class="fa fa-times"></span>
                            <div class="megamenu-pattern">
                                <div class="container-mega">
                                    <ul class="megamenu" data-transition="slide" data-animationtime="250">
                                        <li class="">
                                            <p class="close-menu"></p>
                                            <router-link to="/" class="clearfix">
                                                <strong>Home</strong>
                                            </router-link>
                                        </li>
                                        <li class="">
                                            <p class="close-menu"></p>
                                            <router-link to="/" class="clearfix">
                                                <strong>Features</strong>
                                            </router-link>
                                        </li>
                                        <li class="">
                                            <p class="close-menu"></p>
                                            <router-link to="/" class="clearfix">
                                                <strong>Pages</strong>
                                            </router-link>
                                        </li>
                                        <li class="with-sub-menu hover">
                                            <p class="close-menu"></p>
                                            <a href="#" class="clearfix">
                                                <strong>Categories</strong>
                                                <img class="label-hot" src="image/catalog/menu/hot-icon.png" alt="icon items">
                                                <b class="caret"></b>
                                            </a>
                                            <div class="sub-menu" style="width: 100%; display: none;">
                                                <div class="content">
                                                    <div class="row">
                                                        <div class="col-sm-12">
                                                            <div class="row">
                                                                <div class="col-md-3 img img1">
                                                                    <a href="#"><img src="image/catalog/menu/megabanner/image-1.jpg" alt="banner1"></a>
                                                                </div>
                                                                <div class="col-md-3 img img2">
                                                                    <a href="#"><img src="image/catalog/menu/megabanner/image-2.jpg" alt="banner2"></a>
                                                                </div>
                                                                <div class="col-md-3 img img3">
                                                                    <a href="#"><img src="image/catalog/menu/megabanner/image-3.jpg" alt="banner3"></a>
                                                                </div>
                                                                <div class="col-md-3 img img4">
                                                                    <a href="#"><img src="image/catalog/menu/megabanner/image-4.jpg" alt="banner4"></a>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-3">
                                                            <a href="#" class="title-submenu">Automotive</a>
                                                            <div class="row">
                                                                <div class="col-md-12 hover-menu">
                                                                    <div class="menu">
                                                                        <ul>
                                                                            <li><a href="#"  class="main-menu">Car Alarms and Security</a></li>
                                                                            <li><a href="#"  class="main-menu">Car Audio &amp; Speakers</a></li>
                                                                            <li><a href="#"  class="main-menu">Gadgets &amp; Auto Parts</a></li>
                                                                            <li><a href="#"  class="main-menu">More Car Accessories</a></li>
                                                                        </ul>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="col-md-3">
                                                            <a href="#" class="title-submenu">Funitures</a>
                                                            <div class="row">
                                                                <div class="col-md-12 hover-menu">
                                                                    <div class="menu">
                                                                        <ul>
                                                                            <li><a href="#"  class="main-menu">Bathroom</a></li>
                                                                            <li><a href="#"  class="main-menu">Bedroom</a></li>
                                                                            <li><a href="#"  class="main-menu">Decor</a></li>
                                                                            <li><a href="#"  class="main-menu">Living room</a></li>
                                                                        </ul>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="col-md-3">
                                                            <a href="#" class="title-submenu">Jewelry &amp; Watches</a>
                                                            <div class="row">
                                                                <div class="col-md-12 hover-menu">
                                                                    <div class="menu">
                                                                        <ul>
                                                                            <li><a href="#"  class="main-menu">Earings</a></li>
                                                                            <li><a href="#"  class="main-menu">Wedding Rings</a></li>
                                                                            <li><a href="#"  class="main-menu">Men Watches</a></li>
                                                                        </ul>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="col-md-3">
                                                            <a href="#" class="title-submenu">Electronics</a>
                                                            <div class="row">
                                                                <div class="col-md-12 hover-menu">
                                                                    <div class="menu">
                                                                        <ul>
                                                                            <li><a href="#"  class="main-menu">Computer</a></li>
                                                                            <li><a href="#"  class="main-menu">Smartphone</a></li>
                                                                            <li><a href="#"  class="main-menu">Tablets</a></li>
                                                                            <li><a href="#"  class="main-menu">Monitors</a></li>
                                                                        </ul>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </li>
                                        <li class="">
                                            <p class="close-menu"></p>
                                            <router-link :to="{name: 'categoryProduct'}" class="clearfix">
                                                <strong>Accessories</strong>
                                            </router-link>
                                        </li>
                                        <li class="">
                                            <p class="close-menu"></p>
                                            <router-link :to="{name: 'blogPage'}" class="clearfix">
                                                <strong>Blog</strong>
                                                <span class="label"></span>
                                            </router-link>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
    </div>
</template>

<script>

    export default {
        name: "MainMenu",
        mounted() {
            // let mapScript = document.createElement('script')
            // mapScript.setAttribute('src', 'http://192.168.1.27:8080/public/js/themejs/so_megamenu.js')
            // document.head.appendChild(mapScript)
            // L.map()
        }
    }
</script>

<style scoped>

</style>