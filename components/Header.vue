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
          <span class="navbar-burger" data-target="navbarGd">
            <span></span>
            <span></span>
            <span></span>
          </span>

    </div>

    <div id="navbarGd" class="navbar-menu">

      <div class="navbar-end gd_navbarlinks">
        <div class="navbar-item">
        <nuxt-link class="navbar-item" to="/"> Home </nuxt-link>          
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