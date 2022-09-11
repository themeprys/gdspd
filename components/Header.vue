<template>
  <nav class="navbar gd_navbar" role="navigation" aria-label="main navigation">
      <div class="container">
    <div class="navbar-brand">
      <nuxt-link class="navbar-item" to="/">
        <img
          src="~/static/img/logo.webp"
          width="300px"
          height="auto"
        />
      </nuxt-link>

      <a
        role="button"
        class="navbar-burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasic"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="navbarBasic" class="navbar-menu">

      <div class="navbar-end gd_navbarlinks">
        <div class="navbar-item">
        <nuxt-link class="navbar-item" to="/about-us"> About Us </nuxt-link>
        <nuxt-link class="navbar-item" to="/our-clients"> Our Clients</nuxt-link>
        <nuxt-link class="navbar-item" to="/our-services"> Our Services </nuxt-link>
        </div>
      </div>
    </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style>
</style>