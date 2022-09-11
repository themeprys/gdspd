<template>
<div class="gd_portfoliowrap" id="ourportfolio">
  <div class="container py-6">
      <section class="gd_sectionheader has-text-centered">
      <h3 class="is-size-1">Our <span class="gd_headingred">Portfolio</span></h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem voluptates accusantium quibusdam, voluptas magni, dolor ipsum quod laborum aperiam assumenda vero maiores inventore provident quidem cum?</p>
      </section>
      <section class="py-6">
        <HomePortfolioTabs />
      </section>
  </div>
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
            perList: 2,
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

<style>

</style>