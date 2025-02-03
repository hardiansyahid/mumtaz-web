<template>
  <div>
    <AppHeader/>

    <!-- ======= Hero Section ======= -->
    <section id="hero" class="hero d-flex align-items-center">

      <div class="container">
        <div class="row">
          <div class="col-lg-6 d-flex flex-column justify-content-center">
            <h1 data-aos="fade-up">Kami menawarkan solusi mudah untuk belajar berenang</h1>
            <h2 data-aos="fade-up" data-aos-delay="400">Kami tim berpengalaman dalam melatih berenang anak-anak dan dewasa</h2>
            <div data-aos="fade-up" data-aos-delay="600">
              <div class="text-center text-lg-start">
                <a href="#features" class="btn-get-started scrollto d-inline-flex align-items-center justify-content-center align-self-center">
                  <span>Download Aplikasi</span>
                  <i class="bi bi-arrow-right"></i>
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-6 hero-img" data-aos="zoom-out" data-aos-delay="200">
            <img src="/assets/img/mumtaz.png" class="img-fluid" alt="">
          </div>
        </div>
      </div>

    </section><!-- End Hero -->

    <main id="main">
      <!-- ======= About Section ======= -->
      <section id="about" class="about">

        <div class="container" data-aos="fade-up">
          <div class="row gx-0">

            <div class="col-lg-6 d-flex flex-column justify-content-center" data-aos="fade-up" data-aos-delay="200">
              <div class="content">
                <h3>Tentang Kami</h3>
                <h2>Mumtaz Swimming Course</h2>
                <p>
                  Mumtaz Swimming Course adalah platform pelatihan berenang untuk anak-anak ataupun dewasa. dengan aplikasi yang intuitif memudahkan peserta didik dalam menjalankan pelatihan berenangnya.
                </p>
              </div>
            </div>

            <div class="col-lg-6 d-flex align-items-center justify-content-center" data-aos="zoom-out" data-aos-delay="200">
              <img src="/assets/img/mumtaz.png" class="img-fluid" alt="">
            </div>

          </div>
        </div>

      </section><!-- End About Section -->

      <!-- ======= Services Section ======= -->
      <section id="services" class="services">

        <div class="container" data-aos="fade-up">

          <header class="section-header">
            <h2>Layanan</h2>
            <p>Pilihan variasi kelas berenang</p>
          </header>

          <div class="row gy-4">

            <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="200">
              <div class="service-box blue">
                <i class="ri-user-2-line icon"></i>
                <h3>Private</h3>
                <p>Latihan berenang lebih fokus dengan jumlah siswa maksimal 3 dalam satu sesi latihan</p>
              </div>
            </div>

            <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="300">
              <div class="service-box orange">
                <i class="ri-user-add-line icon"></i>
                <h3>Group</h3>
                <p>Latihan berenang lebih asik dengan jumlah siswa minimal 5 dalam satu sesi latihan</p>
              </div>
            </div>

            <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="400">
              <div class="service-box green">
                <i class="ri-user-search-line icon"></i>
                <h3>Trial</h3>
                <p>Latihan berenang lebih seru karna kamu bisa uji coba terlebih dahulu sebelum membeli kelas</p>
              </div>
            </div>

          </div>

        </div>

      </section><!-- End Services Section -->

      <!-- ======= Values Section ======= -->
      <section id="values" class="values">

        <div class="container" data-aos="fade-up">

          <header class="section-header">
            <p>Semua kegiatan dalam satu aplikasi</p>
          </header>

          <div class="row">

            <div class="col-lg-4" data-aos="fade-up" data-aos-delay="200">
              <div class="box">
                <img src="/assets/img/values-1.png" class="img-fluid" alt="">
                <h3>Transaksi Kelas</h3>
                <p>
                  Beli kelas lebih mudah dan cepat lewat aplikasi
                </p>
              </div>
            </div>

            <div class="col-lg-4 mt-4 mt-lg-0" data-aos="fade-up" data-aos-delay="400">
              <div class="box">
                <img src="/assets/img/values-2.png" class="img-fluid" alt="">
                <h3>Reschedule Kelas</h3>
                <p>
                  Jadwalkan ulang latihan kamu tanpa perlu kontak pelatih, lebih cepat lebih, mudah lewat aplikasi
                </p>
              </div>
            </div>

            <div class="col-lg-4 mt-4 mt-lg-0" data-aos="fade-up" data-aos-delay="600">
              <div class="box">
                <img src="/assets/img/values-3.png" class="img-fluid" alt="">
                <h3>Presensi Kelas</h3>
                <p>Pantau presensi kamu dan sisa sesi kelas kamu lewat aplikasi, praktis serba otomatis</p>
              </div>
            </div>

          </div>

        </div>

      </section><!-- End Values Section -->

      <!-- ======= Features Section ======= -->
      <section id="features" class="features">

        <div class="container" data-aos="fade-up">

          <header class="section-header">
            <h2>Download</h2>
            <p>Download Aplikasi Mumtaz Swimming Course Sekarang Juga</p>
          </header>

          <div class="row">

            <div class="col-xl-4 text-center" data-aos="fade-right" data-aos-delay="100">
              <img src="/assets/img/features-3.png" class="img-fluid p-4" alt="">
            </div>

            <div class="col-xl-8 d-flex content justify-content-center flex-column">
              <div class="align-self-center text-center">
                <div style="cursor: pointer;" @click="downloadAndroid()">
                  <img width="50%" height="auto" src="/assets/img/google-play-badge.png" class="img-fluid p-4" alt="">
                </div>
              </div>
              <div class="align-self-center text-center">
                <div style="cursor: pointer;" onclick="downloadIOS()">
                  <img width="50%" height="auto" src="/assets/img/app-store-badge.svg" class="img-fluid p-4" alt="">
                </div>
              </div>
            </div>

          </div>

        </div>

      </section><!-- End Features Section -->

      <!-- ======= F.A.Q Section ======= -->
      <section id="faq" class="faq">

        <div class="container" data-aos="fade-up">

          <header class="section-header">
            <h2>F.A.Q</h2>
            <p>Frequently Asked Questions</p>
          </header>

          <div class="row">
            <div class="col-lg-12">
              <!-- F.A.Q List 1-->
              <div class="accordion accordion-flush" id="faqlist1">
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq-content-1">
                      Apakah aplikasi tersedia untuk platform iOS
                    </button>
                  </h2>
                  <div id="faq-content-1" class="accordion-collapse collapse" data-bs-parent="#faqlist1">
                    <div class="accordion-body">
                      Ya, Aplikasi tersedia untuk platform iOS
                    </div>
                  </div>
                </div>

                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq-content-2">
                      Apa aplikasi ini khusus Membership Mumtaz Swimming Course ?
                    </button>
                  </h2>
                  <div id="faq-content-2" class="accordion-collapse collapse" data-bs-parent="#faqlist1">
                    <div class="accordion-body">
                      Ya, Aplikasi ini diperuntukan untuk mempermudah siswa mumtaz swimming course
                    </div>
                  </div>
                </div>

                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq-content-3">
                      Bagaimana cara berlangganan Membership Mumtaz Swimming Course ?
                    </button>
                  </h2>
                  <div id="faq-content-3" class="accordion-collapse collapse" data-bs-parent="#faqlist1">
                    <div class="accordion-body">
                      Download aplikasi dan register sebagai siswa, lalu beli paket kelas yang kamu inginkan
                    </div>
                  </div>
                </div>

              </div>
            </div>


          </div>

        </div>

      </section><!-- End F.A.Q Section -->

      <!-- ======= Contact Section ======= -->
      <section id="contact" class="contact">

        <div class="container" data-aos="fade-up">

          <header class="section-header">
            <h2>Contact</h2>
            <p>Contact Us</p>
          </header>

          <div class="row gy-4">

            <div class="col-lg-12">

              <div class="row gy-4">
                <div class="col-md-3">
                  <div class="info-box">
                    <i class="bi bi-geo-alt"></i>
                    <h3>Alamat</h3>
                    <p>Kolam Renang Nadya Jati Murni</p>
                  </div>
                </div>
                <div class="col-md-3">
                  <div class="info-box">
                    <i class="bi bi-telephone"></i>
                    <h3>Telepon</h3>
                    <p>+6282149837733</p>
                  </div>
                </div>
                <div class="col-md-3">
                  <div class="info-box">
                    <i class="bi bi-instagram"></i>
                    <h3>Instagram</h3>
                    <p>mumtaz_swimmingcourse</p>
                  </div>
                </div>
                <div class="col-md-3">
                  <div class="info-box">
                    <i class="bi bi-clock"></i>
                    <h3>Jam Operasi</h3>
                    <p>Senin - Minggu, Jam 09:00 - 20:00</p>
                  </div>
                </div>
              </div>

            </div>

          </div>

        </div>

      </section>
      <!-- End Contact Section -->

    </main>
    <!-- End #main -->

    <app-footer/>
  </div>
</template>

<script>
import AppHeader from "~/layouts/AppHeader.vue";
import AppFooter from "~/layouts/AppFooter.vue";

export default {
  components: {AppFooter, AppHeader},
  data(){
    return{
      APP_IOS_URL : "https://apps.apple.com/id/app/mumtaz-swimming-course/id6469479589?l=id",
      APP_ANDROID_URL : "https://play.google.com/store/apps/details?id=com.skly.mumtaz"
    }
  },
  methods:{
    downloadAndroid(){
      window.open(this.APP_ANDROID_URL)
    },
    downloadIOS(){
      window.open(this.APP_IOS_URL)
    }
  }
}
</script>