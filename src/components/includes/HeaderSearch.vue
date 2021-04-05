<template>
    <div class="header-search">
        <div class="bottom2 col-lg-7 col-md-6 col-sm-6">
            <div class="search-header-w">
                <div class="icon-search hidden-lg hidden-md hidden-sm"><i class="fa fa-search"></i></div>

                <div id="sosearchpro" class="sosearchpro-wrapper so-search ">
                    <form method="GET" action="https://demo.smartaddons.com/templates/html/emarket/index.html">
                        <div id="search0" class="search input-group form-group">
                            <div class="select_category filter_type  icon-select hidden-sm hidden-xs">
                                <select class="no-border" name="category_id">
                                    <option value="0">All Categories</option>
                                    <option value="78">Apparel</option>
                                    <option value="77">Cables &amp; Connectors</option>
                                    <option value="82">Cameras &amp; Photo</option>
                                    <option value="80">Flashlights &amp; Lamps</option>
                                    <option value="81">Mobile Accessories</option>
                                    <option value="79">Video Games</option>
                                    <option value="20">Jewelry &amp; Watches</option>
                                    <option value="76">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Earings</option>
                                    <option value="26">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Wedding Rings</option>
                                    <option value="27">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Men Watches</option>
                                </select>
                            </div>

                            <input class="autosearch-input form-control" type="text" value="" size="50" autocomplete="off" placeholder="Keyword here..." name="search">
                            <span class="input-group-btn">
                                        <button type="submit" class="button-search btn btn-primary" name="submit_search"><i class="fa fa-search"></i></button>
                                        </span>
                        </div>
                        <input type="hidden" name="route" value="product/search" />
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "HeaderSearch"
    }
</script>

<style scoped>

</style>