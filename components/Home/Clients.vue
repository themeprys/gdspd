<template>
<div>
  <div class="container py-6">
      <section class="gd_sectionheader has-text-centered">
      <h3 class="is-size-1">Our <span class="gd_headingred">Clients</span></h3>
      <p>Godspeed telah bekerjasama dengan klien UMKM hingga Korporasi besar, yang memberikan kami berbagai tantangan dan insight berbeda di setiap proyek sehingga memberikan nilai tambah bagi kualitas hasil pekerjaan kami.</p>
      </section>
  </div>
  <div class="gd_ourclientsmap pb-6">
      <section class="gd_maps container is-medium">
        <div class="columns">
          <div class="column">
            <img src="@/static/img/client/bpjs_kesehatan.png" width="300px"/>
          </div>
          <div class="column">
            <img src="@/static/img/client/bukalapak.png" width="300px"/>
          </div>
          <div class="column">
            <img src="@/static/img/client/campina.png" width="300px"/>
          </div>
          <div class="column">
            <img src="@/static/img/client/kawasaki.png" width="300px"/>
          </div>                              
        </div>

        <div class="columns">
          <div class="column">
            <img src="@/static/img/client/nestle.png" width="300px"/>
          </div>
          <div class="column">
            <img src="@/static/img/client/holcim.png" width="300px"/>
          </div>
          <div class="column">
            <img src="@/static/img/client/matanajwa.png" width="300px"/>
          </div>
          <div class="column">
            <img src="@/static/img/client/freeport.png" width="300px"/>
          </div>                              
        </div>

      </section>
      <section class="gd_maps is-medium has-text-centered py-6">
        <nuxt-link to="/our-clients" class="gd_btnmaps button is-large is-dark ">See More</nuxt-link>    
      </section>

  </div>
</div>
</template>

<script>
export default {

}
</script>

<style>

</style>