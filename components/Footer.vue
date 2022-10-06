<template>
  <footer class="footer gd_footer">
    <div class="container">
      <div class="columns is-variable is-6">
        <div class="column is-3">
          <img src="~/static/img/logo.webp" />
          <p class="pt-3">Kami adalah perusahaan kreatif yang bergerak di bidang Production House, khususnya produksi Video.
          </p>
        </div>
        <div class="column p-6">
          <aside class="menu">
            <ul class="menu-list">
              <li><nuxt-link to="/#learnmore">Our Advantages</nuxt-link></li>
              <li><nuxt-link to="/#ourprocess">Our Process</nuxt-link></li>
              <li><nuxt-link to="/about-us">About Us</nuxt-link></li>
            </ul>
          </aside>
        </div>
        <div class="column p-6">
          <aside class="menu">
            <ul class="menu-list">
              <li><nuxt-link to="/our-clients">Our Clients</nuxt-link></li>
              <li><nuxt-link to="/our-services">Our Services</nuxt-link></li>
              <li><nuxt-link to="/#ourportfolio">Our Portfolio</nuxt-link></li>
            </ul>
          </aside>
        </div>
        <div class="column is-4">
          <aside class="menu">
            <p class="menu-label">Contacts</p>
            <ul class="menu-list gd_footercontact">
              <li>
                <a
                  ><b-icon icon="phone" size="is-small"> </b-icon
                  >&nbsp;0812-2259-7799</a
                >
              </li>
              <li>
                <a
                  ><b-icon icon="email" size="is-small"> </b-icon
                  >&nbsp;godspeedstation.id@gmail.com</a
                >
              </li>
            </ul>
            <div class="gd_followusmobile">
            <p class="menu-label">Follow Us</p>
            <a><b-icon icon="facebook" size="is-medium"> </b-icon></a>
            <a><b-icon icon="twitter" size="is-medium"> </b-icon></a>
            <a><b-icon icon="linkedin" size="is-medium"> </b-icon></a>
            </div>
          </aside>
        </div>
      </div>
      <div class="content has-text-centered">
        <p>
          <strong
            >Copyright &copy; 2022 by CV Berkah Imaji Sejahtera - All Right
            Reserved</strong
          >
        </p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
</style>