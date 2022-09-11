<template>
  <div class="container py-6" id="ourservices">
    <section class="gd_sectionheader has-text-centered">
      <h3 class="is-size-1">Our <span class="gd_headingred">Services</span></h3>
      <p>
Beragam kategori video mulai dari company profile, explainer video, tutorial video, elearning, motion grafis sampai kepada webseries telah kami produksi dari tahun 2016 hingga saat ini.
      </p>
    </section>
    <section class="gd_servicelist my-6">
      <HomeServicesList />
    </section>
  </div>
</template>

<script>
export default {
    data(){
        return {
            arrow: true,
            arrowBoth: true,
            arrowHover: false,
            repeat: true,
            drag: true,
            gray: false,
            opacity: false,
            values: 1,
            perList: 4,
            carousels: [
                { text: 'Slide 1', color: 'primary' },
                { text: 'Slide 2', color: 'info' },
                { text: 'Slide 3', color: 'success' },
                { text: 'Slide 4', color: 'warning' },
                { text: 'Slide 5', color: 'danger' }
            ]
        }
    }
}
</script>


