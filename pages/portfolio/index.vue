<template>
<div class="lightbox-wrapper animated portfolio-on fadeIn" id="portfolio" data-simplebar="init" style="position: fixed; width: 100%; height: 100%; top: 0px; left: 0px; z-index: 9999; opacity: 1; animation-duration: 0s; animation-delay: 0.5s; animation-fill-mode: none;">
    <div class="simplebar-wrapper" style="margin: 0px;">
        <div class="simplebar-height-auto-observer-wrapper">
            <div class="simplebar-height-auto-observer"></div>
        </div>
        <div class="simplebar-mask">
            <div class="simplebar-offset" style="right: -15px; bottom: 0px;">
                <div class="simplebar-content-wrapper" style="height: 100%; overflow: hidden scroll;">
                    <div class="simplebar-content" style="padding: 0px;">
                        <div class="container">
                            <div class="lightbox-close">
                                <nuxt-link to="/">
                                    <div class="close-btn" data-modal-close=""><span class="btn-line"></span></div>
                                </nuxt-link>
                            </div>
                            <div class="row">
                                <div class="col-12">
                                    <div class="lightbox-content">
                                        <div class="row">
                                            <div class="col-12">
                                                <div class="section-heading page-heading">
                                                    <p class="section-description">Showcasing some of my best work</p>
                                                    <h2 class="section-title">Portfolio</h2>
                                                    <div class="animated-bar"></div>
                                                </div>
                                            </div>
                                        </div>
                                        <!-- Portfolio section-->

                                        <el-tabs v-model="activeName">
                                            <el-tab-pane label="Laravel & Vue js" name="first">
                                                <myLaravel />

                                            </el-tab-pane>
                                            <el-tab-pane label="Wordpress" name="second">
                                                <myWordpress />
                                            </el-tab-pane>
                                            <el-tab-pane label="Nuxt Js" name="third">
                                                <myNuxtapp />
                                            </el-tab-pane>
                                        </el-tabs>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="simplebar-placeholder" style="width: auto; height: 1223px;"></div>
    </div>
    <div class="simplebar-track simplebar-horizontal" style="visibility: hidden;">
        <div class="simplebar-scrollbar simplebar-visible" style="width: 25px; transform: translate3d(0px, 0px, 0px); display: none;"></div>
    </div>
    <div class="simplebar-track simplebar-vertical" style="visibility: visible;">
        <div class="simplebar-scrollbar simplebar-visible" style="transform: translate3d(0px, 0px, 0px); display: block; height: 184px;"></div>
    </div>
</div>
</template>

<script>
import myLaravel from '../../components/potfolio/laravel'
import myWordpress from '../../components/potfolio/wordpress'
import myNuxtapp from '../../components/potfolio/nuxtapp'
export default {
    components: {
        myLaravel,
        myWordpress,
        myNuxtapp
    },
    data() {
        return {
            activeName: 'first'
        }
    },
}
</script>

<style lang="scss">
.el-tabs__item:hover {
    color: #009e66;
    cursor: pointer;
}

.el-tabs__item {
    color: #fff;
    cursor: pointer;
}

.el-tabs__item.is-active {
    color: #009e66;
}
</style>
