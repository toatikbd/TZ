<template>
    <div class="footer">
        <!-- Footer Container -->
        <footer class="footer-container typefooter-1">
            <!-- Footer Top Container -->
            <TopFooter/>
            <!-- /Footer Top Container -->

            <MiddleFooter/>

            <!-- Footer Bottom Container -->
            <div class="footer-bottom ">
                <div class="container">
                    <div class="copyright">
                        eMarket © 2021 Demo Store. All Rights Reserved. Designed by <a href="#" target="_blank">e-Store</a>
                    </div>
                </div>
            </div>
            <!-- /Footer Bottom Container -->

            <!--Back To Top-->
            <div class="back-to-top"><i class="fa fa-angle-up"></i></div>
            <!--Back To Top-->
            <div class="back-to-top"><i class="fa fa-angle-up"></i></div>
        </footer>
        <!-- //end Footer Container -->

    </div>
</template>

<script>
    import TopFooter from "../components/includes/TopFooter";
    import MiddleFooter from "../components/includes/MiddleFooter";
    export default {
        name: "Footer",
        components: {MiddleFooter, TopFooter}
    }
</script>

<style scoped>

</style>