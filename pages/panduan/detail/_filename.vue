<template>
  <div>
    <nav class="navbar navbar-light bg-light">
      <div class="d-flex align-items-center my-2">
        <a class="btn btn-link" href="/" aria-label="Go Back">
          <i class="bi-arrow-left text-black fs-6"></i>
        </a>

        <h3 class="mb-0 px-3">Panduan {{ namaPanduan }}</h3>
      </div>
    </nav>

    <div>
      <iframe
          :src="pdfUrl"
          width="100%"
          style="border: none; height: 100vh !important;"
          frameborder="0"
      ></iframe>

      <iframe
          :src="googleViewerUrl"
          width="100%"
          style="border: none; height: 100vh !important;"
          frameborder="0"
      ></iframe>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      namaPanduan: '',
      pdfUrl: '',
      googleViewerUrl: ''
    };
  },
  created() {
    const filename = this.$route.params.filename;
    console.log(this.$route)
    console.log("Filename from route:", filename);
    const pdfUrl = `/assets/panduan/${filename}.pdf`;
    const googleViewerUrl = `https://docs.google.com/gview?url=${pdfUrl}&embedded=true`;

    console.log('Filename:', filename);
    console.log('PDF URL:', pdfUrl);
    console.log('Google Viewer URL:', googleViewerUrl);

    this.namaPanduan = filename;
    this.pdfUrl = pdfUrl;
    this.googleViewerUrl = googleViewerUrl;
  }
};

</script>

<style scoped>
iframe {
  margin-top: 20px;
}
</style>
