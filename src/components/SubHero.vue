<template>
  <div class="overflow-hidden mt-6">
    <div id="about"></div>
      <div class="container ">
        <div class="row justify-content-lg-between align-items-lg-center">

<!-- LEFT SIDE STYLING -->
          <div class="col-lg-6 mb-9 mb-lg-0">
            <div class="position-relative mx-auto" style="max-width: 22rem;">
              
<!-- IMAGE FOR ABOUT ME SECTION -->
              <figure class="device-mobile mx-auto">
                <div class="device-mobile-frame">
                  <img class="device-mobile-img" src="../assets/img/malick.jpeg" alt="Image Description">
                </div>
              </figure>
<!-- IMAGE ENDS -->

<!-- SVG SHAPE FOR ABOUT ME SECTION STYLING -->
              <div class="position-absolute bottom-0 end-0 zi-n1 mx-auto" style="width: 20rem;">
                <img class="img-fluid" src="../assets/svg/components/shape-1.svg" alt="SVG">
              </div>
<!-- END SHAPE FOR ABOUT ME SECTION STYLING -->
            </div>
          </div>   
<!-- END LEFT SIDE STYLING -->

<!-- START RIGHT SIDE OF ABOUT ME SECTION -->
          <div class="col-lg-5">
            <!-- Heading -->
            <div class="mb-5" >
              <h2>About Me</h2>
            </div>
            <!-- End Heading -->

            <!-- More details about me -->
            <ul class="step step-dashed mb-7">
              <li class="step-item">
                <div class="step-content-wrapper">
                  <div class="step-content">
                    <p><strong>Highly motivated to create and support quality products that meet your organization and clients' needs.</strong></p>
                    <p>Thank you for visiting my portfolio. I am a Certified Full Stack Developer based in Arlington, Virginia. 
                    While my work in tech focuses on the Front End, I do possess a good working knowledge of the Back End. 
                    Previously, I worked in International Security sector in the Washington, DC area and gained a solid experience in 
                    Project Management, which provides a unique perspective when working in development teams using Agile methodology.
                    I love solving problems, debugging, troubleshooting, designing and implementing solutions to complex issues.</p>
                    <p>I speak four languages fluently, including French. My hobbies include cinema, soccer, and camping. If you have any questions, do not hesitate to send me a message. I would be happy to hear from you.</p>
                  </div>
                </div>
                <a class="btn btn-primary btn-transition" href="#contact">Contact</a>
              </li>
            </ul>
          </div>
      </div>

<!-- KEEPING THIS SECTION FOR POTENTIAL DISPLAY OF SKILLS IN LATER-->
          <!-- <div class="step-content">
            <h4 class="step-title">Technical Skills</h4>
          </div> -->
      <!-- <li class="step-item"> -->
        <!-- <div class="step-content-wrapper">
          <span class="step-icon step-icon-xs step-icon-soft-primary"></span>
          <div class="step-content">
            <h4 class="step-title">HTML</h4>
          </div>
        </div> -->
      <!-- </li>
      <li class="step-item"> -->
        <!-- <div class="step-content-wrapper">
          <span class="step-icon step-icon-xs step-icon-soft-primary"></span>
          <div class="step-content">
            <h4 class="step-title">CSS</h4>
          </div>
        </div> -->
      <!-- </li> -->
      <!-- <li class="step-item"> -->
        <!-- <div class="step-content-wrapper">
          <span class="step-icon step-icon-xs step-icon-soft-primary"></span>
          <div class="step-content">
            <h4 class="step-title">JavaScript</h4>
            <img src="../assets/img/js.png" alt="Logo" class="icon"> 
          </div> 
        </div> -->
      <!-- </li> -->
            <!-- End Skills -->
<!-- END SKILLS LIST -->

    </div>
  </div>
</template>
<script>
export default {
name: 'SubHeroHome',
}
</script>
<style>
</style>