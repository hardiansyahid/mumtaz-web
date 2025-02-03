<script setup>
import { useHead } from "#imports";

useHead({
  title: "Mumtaz Swimming Course",
  meta: [
    { name: "viewport", content: "width=device-width, initial-scale=1.0" },
    { name: "description", content: "" },
    { name: "keywords", content: "" },
  ],
  link: [
    { rel: "icon", href: "/assets/img/logo-mumtaz.png" },
    { rel: "apple-touch-icon", href: "/assets/img/apple-touch-icon.png" },
    {
      rel: "stylesheet",
      href: "https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Nunito:300,300i,400,400i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i",
    },
    { rel: "stylesheet", href: "/assets/vendor/aos/aos.css" },
    { rel: "stylesheet", href: "/assets/vendor/bootstrap/css/bootstrap.min.css" },
    { rel: "stylesheet", href: "/assets/vendor/bootstrap-icons/bootstrap-icons.css" },
    { rel: "stylesheet", href: "/assets/vendor/glightbox/css/glightbox.min.css" },
    { rel: "stylesheet", href: "/assets/vendor/remixicon/remixicon.css" },
    { rel: "stylesheet", href: "/assets/vendor/swiper/swiper-bundle.min.css" },
    { rel: "stylesheet", href: "/assets/css/style.css" },
  ],
  script: [
    { src: "/assets/vendor/purecounter/purecounter_vanilla.js", defer: true },
    { src: "/assets/vendor/aos/aos.js", defer: true },
    { src: "/assets/vendor/bootstrap/js/bootstrap.bundle.min.js", defer: true },
    { src: "/assets/vendor/glightbox/js/glightbox.min.js", defer: true },
    { src: "/assets/vendor/isotope-layout/isotope.pkgd.min.js", defer: true },
    { src: "/assets/vendor/swiper/swiper-bundle.min.js", defer: true },
    { src: "/assets/vendor/php-email-form/validate.js", defer: true },
    { src: "/assets/js/main.js", defer: true },
  ],
});
</script>

<template>
  <div>
    <header>
      <h1>Mumtaz Swimming Course</h1>
    </header>

    <main>
      <slot />
    </main>

    <footer>
      <p>© 2024 Mumtaz Swimming Course</p>
    </footer>

    <a href="#" class="back-to-top d-flex align-items-center justify-content-center">
      <i class="bi bi-arrow-up-short"></i>
    </a>
  </div>
</template>
