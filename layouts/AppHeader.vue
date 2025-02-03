<template>
  <div>
    <!-- ======= Header ======= -->
    <header id="header" class="header fixed-top">
      <div class="container-fluid container-xl d-flex align-items-center justify-content-between">

        <a href="/" class="logo d-flex align-items-center">
          <img src="/assets/img/logo.png" alt="">
          <span>Mumtaz</span>
        </a>

        <nav id="navbar" class="navbar">
          <ul>
            <li><a class="nav-link scrollto active" href="#hero">Home</a></li>
            <li><a class="nav-link scrollto" href="#about">Tentang</a></li>
            <li><a class="nav-link scrollto" href="#services">Layanan</a></li>
            <li><a class="nav-link scrollto" href="#faq">FAQ</a></li>
            <li><a class="nav-link scrollto" href="#contact">Kontak</a></li>
            <li><a class="getstarted scrollto" href="#features">Download Aplikasi</a></li>
          </ul>
          <i class="bi bi-list mobile-nav-toggle"></i>
        </nav>

      </div>
    </header>
    <!-- End Header -->
  </div>
</template>

<script>
export default {
  name: "AppHeader",
}
</script>