<template>
  <div class="home-primary">
    <!-- Main Container  -->
    <div class="main-container container">
      <div id="content">
        <MobileSlider/>
        <div class="row">
          <div class="col-lg-2 col-md-3 col-sm-4 col-xs-12 main-left sidebar-offcanvas">
            <div class="module col1 hidden-sm hidden-xs"></div>
            <div class="module">
              <div class="banners banners2">
                <div class="banner">
                  <a href="#">
                    <img src="image/catalog/banners/banner4.jpg" alt="image">
                  </a>
                </div>
              </div>
            </div>
            <LatestProductSlider/>
            <BlockInfo/>
            <div class="module">
              <div class="banners banners4">
                <div class="banner">
                  <a href="#">
                    <img src="image/catalog/banners/banner5.jpg" alt="image">
                  </a>
                </div>
              </div>
            </div>
            <LatestBlog/>
            <TopRatedProductSlider/>
            <div class="module">
              <div class="banners banners5">
                <div class="banner">
                  <a href="#">
                    <img src="image/catalog/banners/banner6.jpg" alt="image">
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-10 col-md-9 col-sm-8 col-xs-12 main-right">
            <div class="slider-container row">
              <div class="col-lg-9 col-md-8 col-sm-8 col-xs-12 col2">
                <HomeSlider/>
              </div>
              <div class="col-lg-3 col-md-4 col-sm-4 col-xs-12 col3">
                <SliderBanner/>
              </div>
            </div>
            <CouponBanner/>
            <!-- Deals -->
            <DailyDeals/>
            <!-- End Deals -->
            <OfferBanner/>
            <!-- Listing tabs -->
            <TrendingItem/>
            <!-- end Listing tabs -->
            <!--banners 7-->
            <Banner/>
            <!-- Listing tabs custom -->
            <NewItem/>
            <!-- end Listing tabs custom -->
          </div>
          <HomeBrand/>
        </div>
      </div>
    </div>
    <!-- //Main Container -->
  </div>
</template>

<script>
// @ is an alias to /src


import HomeBrand from "../components/home/HomeBrand";
import NewItem from "../components/home/NewItem";
import Banner from "../components/home/Banner";
import TrendingItem from "../components/home/TrendingItem";
import OfferBanner from "../components/home/OfferBanner";
import DailyDeals from "../components/home/DailyDeals";
import CouponBanner from "../components/home/CouponBanner";
import SliderBanner from "../components/home/SliderBanner";
import HomeSlider from "../components/home/HomeSlider";
import TopRatedProductSlider from "../components/home/TopRatedProductSlider";
import LatestBlog from "../components/home/LatestBlog";
import BlockInfo from "../components/home/BlockInfo";
import LatestProductSlider from "../components/home/LatestProductSlider";
import MobileSlider from "../components/home/MobileSlider";
export default {
  name: 'Home',
  components: {
    MobileSlider,
    LatestProductSlider,
    BlockInfo,
    LatestBlog,
    TopRatedProductSlider,
    HomeSlider,
    SliderBanner,
    CouponBanner,
    DailyDeals,
    OfferBanner,
    TrendingItem,
    Banner,
    NewItem,
    HomeBrand

  }
}
</script>
