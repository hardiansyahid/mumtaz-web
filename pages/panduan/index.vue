<template>
  <div>
    <div class="container">

      <div class="display-1 mt-4">
        Panduan
      </div>

      <div class="row gy-3 my-3">
        <div class="col-md-3" v-for="data in list">
          <nuxt-link :to="`/panduan/detail/${getNameFile(data)}`" class="text-decoration-none text-dark">
            <div class="info-box shadow-sm rounded-3 p-3 text-start bg-primary-subtle">
              <h3 class="px-2 mb-0">{{ getNameFile(data) }}</h3>
            </div>
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return{
      list : [
        "BANK.pdf",
        "BOOKING KELAS.pdf",
        "JADWAL.pdf",
        "KELAS.pdf",
        "LOG SISWA.pdf",
        "LOKASI.pdf",
        "REGISTRASI.pdf",
        "RESCHEDULE.pdf",
        "TRANSAKSI.pdf",
        "USER.pdf",
      ]
    }
  },
  methods:{
    getNameFile(filename){
      if (filename){
        return filename.replace(/\.[^/.]+$/, "");
      }

      return "-"
    }
  }
}
</script>