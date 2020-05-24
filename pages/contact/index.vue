<template>
<div class="lightbox-wrapper animated contact-on fadeIn" id="contact" data-simplebar="init" style="position: fixed; width: 100%; height: 100%; top: 0px; left: 0px; z-index: 9999; opacity: 1; animation-duration: 0s; animation-delay: 0.5s; animation-fill-mode: none;"><div class="simplebar-wrapper" style="margin: 0px;"><div class="simplebar-height-auto-observer-wrapper"><div class="simplebar-height-auto-observer"></div></div><div class="simplebar-mask"><div class="simplebar-offset" style="right: -15px; bottom: 0px;"><div class="simplebar-content-wrapper" style="height: 100%; overflow: hidden scroll;"><div class="simplebar-content" style="padding: 0px;">
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
                  <p class="section-description">Feel free to contact me anytimes</p>
                  <h2 class="section-title">Get in Touch</h2>
                  <div class="animated-bar"></div>
                </div>
              </div>
            </div>
            <!-- Contact section-->
            <div class="contact-section single-section">
              <div class="row">
                <!-- Contact form-->
                <div class="col-12 col-lg-7">
                  <form class="contact-form" id="contact-form" action="php/contact.php">
                    <h4 class="content-title">Message Me</h4>
                    <div class="row">
                      <div class="col-12 col-md-6 form-group"><input class="form-control" id="contact-name" type="text" name="name" placeholder="Name" required=""></div>
                      <div class="col-12 col-md-6 form-group"><input class="form-control" id="contact-email" type="email" name="email" placeholder="Email" required=""></div>
                      <div class="col-12 form-group"><input class="form-control" id="contact-subject" type="text" name="subject" placeholder="Subject" required=""></div>
                      <div class="col-12 form-group form-message"><textarea class="form-control" id="contact-message" name="message" placeholder="Message" rows="5" required=""></textarea></div>
                      <div class="col-12 form-submit"><button class="btn button-main button-scheme" id="contact-submit" type="submit">Send Message</button>
                        <p class="contact-feedback"></p>
                      </div>
                    </div>
                  </form>
                </div>
                <!-- Contact info-->
                <div class="col-12 col-lg-5">
                  <div class="contact-info">
                    <h4 class="content-title">Contact Info</h4>
                    <p class="info-description">Always available for freelance work if the right project comes along, Feel free to contact me!</p>
                    <ul class="list-unstyled list-info">
                      <li>
                        <div class="media align-items-center"><span class="info-icon"><i class="icon ion-logo-ionic"></i></span>
                          <div class="media-body info-details">
                            <h6 class="info-type">Name</h6><span class="info-value">Emma Smith</span>
                          </div>
                        </div>
                      </li>
                      <li>
                        <div class="media align-items-center"><span class="info-icon"><i class="icon ion-md-map"></i></span>
                          <div class="media-body info-details">
                            <h6 class="info-type">Location</h6><span class="info-value">4155 Mann Island, Liverpool, United Kingdom.</span>
                          </div>
                        </div>
                      </li>
                      <li>
                        <div class="media align-items-center"><span class="info-icon"><i class="icon ion-md-call"></i></span>
                          <div class="media-body info-details">
                            <h6 class="info-type">Call Me</h6><span class="info-value"><a href="tel:+254731090832">+254731 090 832</a></span>
                          </div>
                        </div>
                      </li>
                      <li>
                        <div class="media align-items-center"><span class="info-icon"><i class="icon ion-md-send"></i></span>
                          <div class="media-body info-details">
                            <h6 class="info-type">Email Me</h6><span class="info-value"><a href="mailto:jimkiarie8@gmail.com">jimkiarie8@gmail.com</a></span>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div></div></div></div><div class="simplebar-placeholder" style="width: auto; height: 749px;"></div></div><div class="simplebar-track simplebar-horizontal" style="visibility: hidden;"><div class="simplebar-scrollbar" style="width: 25px; transform: translate3d(0px, 0px, 0px); display: none;"></div></div><div class="simplebar-track simplebar-vertical" style="visibility: visible;"><div class="simplebar-scrollbar" style="transform: translate3d(0px, 0px, 0px); display: block; height: 321px;"></div></div></div>
</template>
