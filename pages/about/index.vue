<template>
<div class="lightbox-wrapper animated about-on fadeIn" id="about" data-simplebar="init" style="position: fixed; width: 100%; height: 100%; top: 0px; left: 0px; z-index: 9999; opacity: 1; animation-duration: 0s; animation-delay: 0.5s; animation-fill-mode: none;">
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
                                                    <p class="section-description">Get to know me</p>
                                                    <h1 class="section-title">About Me</h1>
                                                    <div class="animated-bar"></div>
                                                </div>
                                            </div>
                                        </div>
                                        <!-- Info section-->
                                        <div class="info-section single-section">
                                            <div class="row align-items-center">
                                                <!-- Picture part-->
                                                <div class="col-12 col-lg-5 info-img">
                                                    <img class="img-fluid img-thumbnail" src="/images/jimmy.jpg" alt="About Picture"></div>
                                                <!-- Content part-->
                                                <div class="col-12 col-lg-7 info-content">
                                                    <div class="content-block">
                                                        <h2 class="content-subtitle">Who am i?</h2>
                                                        <h6 class="content-title">I'm James Kiarie, a visual UX/UI Designer, Mobile app developer and Web Developer</h6>
                                                        <div class="content-description">
                                                            <p>Hi! My name is James Kiarie. I am a Web Developer, and I'm very passionate and dedicated to my work. With 4 years experience as a professional Web developer, I have acquired the skills and knowledge necessary to make your project a success. I enjoy every step of the design process, from discussion and collaboration to concept and execution, but I find the most satisfaction in seeing the finished product do everything for you that it was created to do.</p>
                                                        </div>
                                                        <address class="content-info">
                                                            <div class="row">
                                                                <div class="col-12 col-md-6 single-info"><span>Name:</span>
                                                                    <p>James Kiarie</p>
                                                                </div>
                                                                <div class="col-12 col-md-6 single-info"><span>Email:</span>
                                                                    <p>
                                                                        <a href="mailto:jimkiarie8@gmail.com" target="_blank">jimkiarie8@gmail.com</a>
                                                                    </p>
                                                                </div>
                                                            </div>
                                                            <div class="row">
                                                                <div class="col-12 col-md-6 single-info"><span>Age:</span>
                                                                    <p>24</p>
                                                                </div>
                                                                <div class="col-12 col-md-6 single-info"><span>From:</span>
                                                                    <p>Nairobi, Kenya</p>
                                                                </div>
                                                            </div>
                                                        </address>
                                                        <div class="d-block d-sm-flex align-items-center"><a class="btn content-download button-main button-scheme" href="https://drive.google.com/file/d/15l4JiLzTEJxE-kQMOI06gT8mXIfaNtXt/view?usp=sharing" target="_blank" role="button">Download CV</a>
                                                            <ul class="list-unstyled list-inline content-follow">
                                                                <li><a target="_blank" href="https://github.com/Jimmy-kiarie8"><i class="fab fa-github"></i></a></li>
                                                                <li><a target="_blank" href="https://stackoverflow.com/users/8415539/jimmy-kiarie"><i class="fab fa-stack-overflow"></i></a></li>
                                                                <li><a target="_blank" href="https://laracasts.com/@jimkiarie8"><i class="fab fa-laravel"></i></a></li>
                                                                <li><a target="_blank" href="https://www.linkedin.com/in/jimmy-kiarie-a1a3a2114/"><i class="fab fa-linkedin"></i></a></li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <!-- Services section-->
                                        <div class="services-section single-section" id="services">
                                            <div class="row">
                                                <div class="col-12">
                                                    <div class="section-heading">
                                                        <p class="section-description">Services I offer to my clients</p>
                                                        <h2 class="section-title">My Services</h2>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="row">
                                                <!-- Single service-->
                                                <div class="col-12 col-md-6 col-lg-4">
                                                    <div class="single-service">
                                                        <i class="fa fa-globe"></i>
                                                        <h6 class="service-title">Website Development</h6>
                                                        <p class="service-description">As an experienced web developer I am available to assist you in reaching your customers through the web. I will develop for you beautiful and interactive wesites that are SEO friendly so that you can get as many visitors as posible. I use the current web application platforms including Laravel, Vuejs, Nuxt js and Wordpress.</p>
                                                    </div>
                                                </div>
                                                <!-- Single service-->
                                                <div class="col-12 col-md-6 col-lg-4">
                                                    <div class="single-service">
                                                        <!-- <v-icon :color="color">code</v-icon> -->
                                                        <i class="fab fa-html5"></i>
                                                        <h6 class="service-title">Web application developent</h6>
                                                        <p class="service-description">As an experienced developer i am available to assist you in determining, targeting and solving your software application needs. I will develop for you high quality web applications that will enable your business processes run best. I use the current web application platforms including Laravel, Vuejs, Nuxt js.</p>
                                                    </div>
                                                </div>
                                                <!-- Single service-->
                                                <div class="col-12 col-md-6 col-lg-4">
                                                    <div class="single-service mb-lg-0">
                                                        <i class="fa fa-mobile"></i>
                                                        <h6 class="service-title">Moble app development</h6>
                                                        <p class="service-description">As consumer behaviour continues to evolve, businesses need to adapt their strategy to be ‘where their customers are’. As a result, companies are moving rapidly toward making mobile apps common-place as business tools and assets. I will develop for you high quality mobile app to stay ahead of competition</p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <!-- Testimonials section-->

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="simplebar-placeholder" style="width: auto; height: 3077px;"></div>
    </div>
    <div class="simplebar-track simplebar-horizontal" style="visibility: hidden;">
        <div class="simplebar-scrollbar simplebar-visible" style="width: 25px; transform: translate3d(0px, 0px, 0px); display: none;"></div>
    </div>
    <div class="simplebar-track simplebar-vertical" style="visibility: visible;">
        <div class="simplebar-scrollbar simplebar-visible" style="transform: translate3d(0px, 413px, 0px); display: block; height: 78px;"></div>
    </div>
</div>
</template>

<script>
export default {
    data() {
        return {
            color: '#009e66'
        }
    },
    head() {
        return {
            title: 'About',
            meta: [{
                hid: 'description',
                name: 'description',
                content: 'Web developer'
            }]
        }
    },
}
</script>

<style lang="scss">
#services .fab,
#services .fa {
    font-size: 58px;
    color: #009e66;
    margin-bottom: 10px;
}
</style>
