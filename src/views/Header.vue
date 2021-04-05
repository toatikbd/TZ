<template>
    <div class="header">
        <!-- Header Container  -->
        <header id="header" class=" typeheader-1">
            <!-- Header Top -->
            <TopHeader/>
            <!-- //Header Top -->
            <!-- Header center -->
            <div class="header-middle">
                <div class="container">
                    <div class="row">
                        <!-- Logo -->
                        <div class="navbar-logo col-lg-2 col-md-2 col-sm-12 col-xs-12">
                            <div class="logo">
                                <router-link to="/"><img src="image/catalog/logo.png" title="Your Store" alt="Your Store" /></router-link>
                            </div>
                        </div>
                        <!-- //end Logo -->
                        <!-- Main menu -->
                        <MainMenu/>
                        <!-- //end Main menu -->
                        <LoginRegister/>
                    </div>
                </div>
            </div>
            <!-- //Header center -->
            <!-- Header Bottom -->
            <div class="header-bottom hidden-compact">
                <div class="container">
                    <div class="row">
                        <!-- Header Megamenu-->
                        <HeaderMegamenu/>
                        <!-- //end Header Megamenu-->
                        <!-- Search -->
                        <HeaderSearch/>
                        <!-- //end Search -->
                        <!-- Secondary menu -->
                        <div class="bottom3 col-lg-3 col-md-3 col-sm-3">
                            <!--cart-->
                            <ShoppingCart/>
                            <!--//cart-->
                            <WishList/>
                        </div>
                    </div>
                </div>
            </div>
        </header>
        <!-- //Header Container  -->
    </div>
</template>

<script>
    import TopHeader from "../components/includes/TopHeader";
    import MainMenu from "../components/includes/MainMenu";
    import LoginRegister from "../components/includes/LoginRegister";
    import HeaderSearch from "../components/includes/HeaderSearch";
    import HeaderMegamenu from "../components/includes/HeaderMegamenu";
    import ShoppingCart from "../components/includes/ShoppingCart";
    import WishList from "../components/includes/WishList";
    export default {
        name: "Header",
        components:{
            WishList,
            ShoppingCart,
            HeaderMegamenu,
            HeaderSearch,
            LoginRegister,
            MainMenu,
            TopHeader
        },
        mounted() {

        }
    }
</script>

<style scoped>

</style>