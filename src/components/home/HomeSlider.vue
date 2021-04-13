<template>
    <div class="home-slider">
        <div class="module sohomepage-slider ">
            <div class="yt-content-slider" data-rtl="yes" data-autoplay="no" data-autoheight="no" data-delay="4" data-speed="0.6" data-margin="0" data-items_column0="1" data-items_column1="1" data-items_column2="1" data-items_column3="1" data-items_column4="1" data-arrows="no" data-pagination="yes" data-lazyload="yes" data-loop="no" data-hoverpause="yes">
                <div class="yt-content-slide">
                    <a href="#">
                        <img src="image/catalog/slideshow/home1/slider-1.jpg" alt="slider1" class="img-responsive">
                    </a>
                </div>
                <div class="yt-content-slide">
                    <a href="#">
                        <img src="image/catalog/slideshow/home1/slider-2.jpg" alt="slider2" class="img-responsive">
                    </a>
                </div>
                <div class="yt-content-slide">
                    <a href="#">
                        <img src="image/catalog/slideshow/home1/slider-3.jpg" alt="slider3" class="img-responsive">
                    </a>
                </div>
            </div>
            <div class="loadeding"></div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "HomeSlider",
        mounted() {
            /* ---------------------------------------------------
	Owl carousel - Slider
-------------------------------------------------- */
            // $(document).ready(function ($) {
            //     "use strict";
                // Content slider
                $('.yt-content-slider').each(function () {
                    var $slider = $(this),
                        $panels = $slider.children('div'),
                        data = $slider.data();
                    // Remove unwanted br's
                    //$slider.children(':not(.yt-content-slide)').remove();
                    // Apply Owl Carousel

                    $slider.owlCarousel2({
                        responsiveClass: true,
                        mouseDrag: true,
                        video:true,
                        lazyLoad: (data.lazyload == 'yes') ? true : false,
                        autoplay: (data.autoplay == 'yes') ? true : false,
                        autoHeight: (data.autoheight == 'yes') ? true : false,
                        autoplayTimeout: data.delay * 1000,
                        smartSpeed: data.speed * 1000,
                        autoplayHoverPause: (data.hoverpause == 'yes') ? true : false,
                        center: (data.center == 'yes') ? true : false,
                        loop: (data.loop == 'yes') ? true : false,
                        dots: (data.pagination == 'yes') ? true : false,
                        nav: (data.arrows == 'yes') ? true : false,
                        dotClass: "owl2-dot",
                        dotsClass: "owl2-dots",
                        margin: data.margin,
                        navText: ['',''],

                        responsive: {
                            0: {
                                items: data.items_column4
                            },
                            480: {
                                items: data.items_column3
                            },
                            768: {
                                items: data.items_column2
                            },
                            992: {
                                items: data.items_column1
                            },
                            1200: {
                                items: data.items_column0
                            }
                        }
                    });
                });
            // });
        }
    }
</script>

<style scoped>

</style>