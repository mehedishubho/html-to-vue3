<script setup>
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";
import Slider from "./components/Slider.vue";
</script>

<template>
  <div class="hero_area">
    <div class="hero_bg_box">
      <img src="/images/hero-bg.png" alt="" />
    </div>

    <!-- header section strats -->
    <Header />
    <!-- end header section -->
    <!-- slider section -->
    <Slider />
    <!-- end slider section -->
  </div>

  <!-- department section -->

  <section class="department_section layout_padding">
    <div class="department_container">
      <div class="container">
        <div class="heading_container heading_center">
          <h2>Our Departments</h2>
          <p>
            Asperiores sunt consectetur impedit nulla molestiae delectus
            repellat laborum dolores doloremque accusantium
          </p>
        </div>
        <div class="row">
          <div class="col-md-3">
            <div class="box">
              <div class="img-box">
                <img src="/images/s1.png" alt="" />
              </div>
              <div class="detail-box">
                <h5>Cardiology</h5>
                <p>
                  fact that a reader will be distracted by the readable page
                  when looking at its layout.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="box">
              <div class="img-box">
                <img src="/images/s2.png" alt="" />
              </div>
              <div class="detail-box">
                <h5>Diagnosis</h5>
                <p>
                  fact that a reader will be distracted by the readable page
                  when looking at its layout.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="box">
              <div class="img-box">
                <img src="/images/s3.png" alt="" />
              </div>
              <div class="detail-box">
                <h5>Surgery</h5>
                <p>
                  fact that a reader will be distracted by the readable page
                  when looking at its layout.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="box">
              <div class="img-box">
                <img src="/images/s4.png" alt="" />
              </div>
              <div class="detail-box">
                <h5>First Aid</h5>
                <p>
                  fact that a reader will be distracted by the readable page
                  when looking at its layout.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="btn-box">
          <a href=""> View All </a>
        </div>
      </div>
    </div>
  </section>

  <!-- end department section -->

  <!-- about section -->

  <section class="about_section layout_margin-bottom">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="img-box">
            <img src="/images/about-img.jpg" alt="" />
          </div>
        </div>
        <div class="col-md-6">
          <div class="detail-box">
            <div class="heading_container">
              <h2>About <span>Us</span></h2>
            </div>
            <p>
              There are many variations of passages of Lorem Ipsum available,
              but the majority have suffered alteration in some form, by
              injected humour, or randomised words which don't look even
              slightly believable. If you are going to use a passage of Lorem
              Ipsum, you need to be sure there isn't anything embarrassing
              hidden in the middle of text. All
            </p>
            <a href=""> Read More </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- end about section -->

  <!-- doctor section -->

  <section class="doctor_section layout_padding">
    <div class="container">
      <div class="heading_container heading_center">
        <h2>Our Doctors</h2>
        <p class="col-md-10 mx-auto px-0">
          Incilint sapiente illo quo praesentium officiis laudantium nostrum, ad
          adipisci cupiditate sit, quisquam aliquid. Officiis laudantium fuga ad
          voluptas aspernatur error fugiat quos facilis saepe quas fugit, beatae
          id quisquam.
        </p>
      </div>
      <div class="row">
        <div class="col-sm-6 col-lg-4 mx-auto">
          <div class="box">
            <div class="img-box">
              <img src="/images/d1.jpg" alt="" />
            </div>
            <div class="detail-box">
              <div class="social_box">
                <a href="">
                  <i class="fa fa-facebook" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-twitter" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-youtube" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-linkedin" aria-hidden="true"></i>
                </a>
              </div>
              <h5>Elina Josh</h5>
              <h6 class="">Doctor</h6>
            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mx-auto">
          <div class="box">
            <div class="img-box">
              <img src="/images/d2.jpg" alt="" />
            </div>
            <div class="detail-box">
              <div class="social_box">
                <a href="">
                  <i class="fa fa-facebook" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-twitter" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-youtube" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-linkedin" aria-hidden="true"></i>
                </a>
              </div>
              <h5>Adam View</h5>
              <h6 class="">Doctor</h6>
            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mx-auto">
          <div class="box">
            <div class="img-box">
              <img src="/images/d3.jpg" alt="" />
            </div>
            <div class="detail-box">
              <div class="social_box">
                <a href="">
                  <i class="fa fa-facebook" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-twitter" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-youtube" aria-hidden="true"></i>
                </a>
                <a href="">
                  <i class="fa fa-linkedin" aria-hidden="true"></i>
                </a>
              </div>
              <h5>Mia Mike</h5>
              <h6 class="">Doctor</h6>
            </div>
          </div>
        </div>
      </div>
      <div class="btn-box">
        <a href=""> View All </a>
      </div>
    </div>
  </section>

  <!-- end doctor section -->

  <!-- contact section -->
  <section class="contact_section layout_padding">
    <div class="container">
      <div class="heading_container">
        <h2>Get In Touch</h2>
      </div>
      <div class="row">
        <div class="col-md-6">
          <div class="form_container contact-form">
            <form action="">
              <div class="form-row">
                <div class="col-lg-6">
                  <div>
                    <input type="text" placeholder="Your Name" />
                  </div>
                </div>
                <div class="col-lg-6">
                  <div>
                    <input type="text" placeholder="Phone Number" />
                  </div>
                </div>
              </div>
              <div>
                <input type="email" placeholder="Email" />
              </div>
              <div>
                <input type="text" class="message-box" placeholder="Message" />
              </div>
              <div class="btn_box">
                <button>SEND</button>
              </div>
            </form>
          </div>
        </div>
        <div class="col-md-6">
          <div class="map_container">
            <div class="map">
              <div id="googleMap">
                <iframe
                  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2582.575444053939!2d90.40750970175158!3d23.73620751715753!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755b8f49dbf166f%3A0x62ce432ec54d3013!2zUENQNStSNTYsIOCmsOCni-CmoSwgRGhha2EgMTIwNQ!5e0!3m2!1sen!2sbd!4v1709534977068!5m2!1sen!2sbd"
                  width="600"
                  height="450"
                  style="border: 0"
                  allowfullscreen=""
                  loading="lazy"
                  referrerpolicy="no-referrer-when-downgrade"
                ></iframe>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- end contact section -->

  <!-- client section -->

  <section class="client_section layout_padding-bottom">
    <div class="container">
      <div class="heading_container heading_center">
        <h2>Testimonial</h2>
      </div>
      <div
        id="carouselExample2Controls"
        class="carousel slide"
        data-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="row">
              <div class="col-md-11 col-lg-10 mx-auto">
                <div class="box">
                  <div class="img-box">
                    <img src="/images/client.jpg" alt="" />
                  </div>
                  <div class="detail-box">
                    <div class="name">
                      <h6>Alan Emerson</h6>
                    </div>
                    <p>
                      Enim consequatur odio assumenda voluptas voluptatibus esse
                      nobis officia. Magnam, aspernatur nostrum explicabo,
                      distinctio laudantium delectus deserunt quia quidem magni
                      corporis earum inventore totam consectetur corrupti!
                      Corrupti, nihil sunt? Natus.
                    </p>
                    <i class="fa fa-quote-left" aria-hidden="true"></i>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row">
              <div class="col-md-11 col-lg-10 mx-auto">
                <div class="box">
                  <div class="img-box">
                    <img src="/images/client.jpg" alt="" />
                  </div>
                  <div class="detail-box">
                    <div class="name">
                      <h6>Alan Emerson</h6>
                    </div>
                    <p>
                      Enim consequatur odio assumenda voluptas voluptatibus esse
                      nobis officia. Magnam, aspernatur nostrum explicabo,
                      distinctio laudantium delectus deserunt quia quidem magni
                      corporis earum inventore totam consectetur corrupti!
                      Corrupti, nihil sunt? Natus.
                    </p>
                    <i class="fa fa-quote-left" aria-hidden="true"></i>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row">
              <div class="col-md-11 col-lg-10 mx-auto">
                <div class="box">
                  <div class="img-box">
                    <img src="/images/client.jpg" alt="" />
                  </div>
                  <div class="detail-box">
                    <div class="name">
                      <h6>Alan Emerson</h6>
                    </div>
                    <p>
                      Enim consequatur odio assumenda voluptas voluptatibus esse
                      nobis officia. Magnam, aspernatur nostrum explicabo,
                      distinctio laudantium delectus deserunt quia quidem magni
                      corporis earum inventore totam consectetur corrupti!
                      Corrupti, nihil sunt? Natus.
                    </p>
                    <i class="fa fa-quote-left" aria-hidden="true"></i>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel_btn-container">
          <a
            class="carousel-control-prev"
            href="#carouselExample2Controls"
            role="button"
            data-slide="prev"
          >
            <i class="fa fa-long-arrow-left" aria-hidden="true"></i>
            <span class="sr-only">Previous</span>
          </a>
          <a
            class="carousel-control-next"
            href="#carouselExample2Controls"
            role="button"
            data-slide="next"
          >
            <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- end client section -->

  <!-- footer section -->
  <Footer />
  <!-- footer section -->
</template>

<style></style>
