<template>
<div class="lightbox-wrapper animated resume-on fadeIn" id="resume" data-simplebar="init" style="position: fixed; width: 100%; height: 100%; top: 0px; left: 0px; z-index: 9999; opacity: 1; animation-duration: 0s; animation-delay: 0.5s; animation-fill-mode: none;"><div class="simplebar-wrapper" style="margin: 0px;"><div class="simplebar-height-auto-observer-wrapper"><div class="simplebar-height-auto-observer"></div></div><div class="simplebar-mask"><div class="simplebar-offset" style="right: -15px; bottom: 0px;"><div class="simplebar-content-wrapper" style="height: 100%; overflow: hidden scroll;"><div class="simplebar-content" style="padding: 0px;">
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
                  <p class="section-description">Check out my Resume</p>
                  <h2 class="section-title">Resume</h2>
                  <div class="animated-bar"></div>
                </div>
              </div>
            </div>
            <!-- Resume section-->
            <div class="resume-section single-section">
              <div class="row">
                <!-- Education part-->
                <div class="col-12 col-md-6">
                  <div class="col-block education">
                    <h3 class="col-title">Education</h3>
                    <div class="resume-item"><span class="item-arrow"></span>
                      <h5 class="item-title">Computer Science</h5><span class="item-details">Machakos University / 2004 - 2007</span>
                      <p class="item-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio quo repudiandae.</p>
                    </div>
                    <div class="resume-item"><span class="item-arrow"></span>
                      <h5 class="item-title">Bachelor Degree</h5><span class="item-details">University of Tokyo / 2008 - 2010</span>
                      <p class="item-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio quo repudiandae.</p>
                    </div>
                    <div class="resume-item"><span class="item-arrow"></span>
                      <h5 class="item-title">Master Degree</h5><span class="item-details">Harvard University / 2012 - 2015</span>
                      <p class="item-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio quo repudiandae.</p>
                    </div>
                  </div>
                </div>
                <!-- Experience part-->
                <div class="col-12 col-md-6">
                  <div class="col-block experience">
                    <h3 class="col-title">Experience</h3>
                    <div class="resume-item"><span class="item-arrow"></span>
                      <h5 class="item-title">Software Engineer</h5><span class="item-details">Adobe / 2015 - 2017</span>
                      <p class="item-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio quo repudiandae.</p>
                    </div>
                    <div class="resume-item"><span class="item-arrow"></span>
                      <h5 class="item-title">Back-End Developer</h5><span class="item-details">Google / 2017 - 2018</span>
                      <p class="item-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio quo repudiandae.</p>
                    </div>
                    <div class="resume-item"><span class="item-arrow"></span>
                      <h5 class="item-title">UI/UX Designer</h5><span class="item-details">Discord / 2019 - Present</span>
                      <p class="item-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio quo repudiandae.</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!-- Skills section-->
            <div class="skills-section single-section">
              <div class="row">
                <div class="col-12">
                  <div class="section-heading">
                    <p class="section-description">My level of knowledge in some tools</p>
                    <h2 class="section-title">My Skills</h2>
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-12 col-md-6">
                  <div class="single-skill" data-percentage="95">
                    <div class="skill-info"><span class="skill-name">HTML/CSS</span><span class="skill-percentage" style="margin-right: 28.5px;">95%</span></div>
                    <div class="progress skill-progress">
                      <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="95" style="width: 95%;"></div>
                    </div>
                  </div>
                  <div class="single-skill" data-percentage="90">
                    <div class="skill-info"><span class="skill-name">Vue JS</span><span class="skill-percentage" style="margin-right: 57px;">90%</span></div>
                    <div class="progress skill-progress">
                      <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="90" style="width: 90%;"></div>
                    </div>
                  </div>
                  <div class="single-skill" data-percentage="80">
                    <div class="skill-info"><span class="skill-name">Nuxt js</span><span class="skill-percentage" style="margin-right: 114px;">80%</span></div>
                    <div class="progress skill-progress">
                      <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="80" style="width: 80%;"></div>
                    </div>
                  </div>

                  <div class="single-skill" data-percentage="90">
                    <div class="skill-info"><span class="skill-name">Flutter</span><span class="skill-percentage" style="margin-right: 230px;">60%</span></div>
                    <div class="progress skill-progress">
                      <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="60" style="width: 60%;"></div>
                    </div>
                    </div>
                </div>
                <div class="col-12 col-md-6">
                  <div class="single-skill" data-percentage="95">
                    <div class="skill-info"><span class="skill-name">Laravel</span><span class="skill-percentage" style="margin-right: 28.5px;">95%</span></div>
                    <div class="progress skill-progress">
                      <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="95" style="width: 95%;"></div>
                    </div>
                  </div>
                  <div class="single-skill" data-percentage="80">
                    <div class="skill-info"><span class="skill-name">Wordpress</span><span class="skill-percentage" style="margin-right: 114px;">80%</span></div>
                    <div class="progress skill-progress">
                      <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="80" style="width: 80%;"></div>
                    </div>
                  </div>
                  <div class="single-skill" data-percentage="90">
                    <div class="skill-info"><span class="skill-name">Rest API</span><span class="skill-percentage" style="margin-right: 57px;">90%</span></div>
                    <div class="progress skill-progress">
                      <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="90" style="width: 90%;"></div>
                    </div>
                  </div>
                  <div class="single-skill" data-percentage="90">
                    <div class="skill-info"><span class="skill-name">Django</span><span class="skill-percentage" style="margin-right: 340px;">40%</span></div>
                    <div class="progress skill-progress">
                      <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="40" style="width: 40%;"></div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
  </div></div></div></div><div class="simplebar-placeholder" style="width: auto; height: 1866px;"></div></div><div class="simplebar-track simplebar-horizontal" style="visibility: hidden;"><div class="simplebar-scrollbar simplebar-visible" style="width: 25px; transform: translate3d(0px, 0px, 0px); display: none;"></div></div><div class="simplebar-track simplebar-vertical" style="visibility: visible;"><div class="simplebar-scrollbar simplebar-visible" style="transform: translate3d(0px, 0px, 0px); display: block; height: 129px;"></div></div></div>

</template>
