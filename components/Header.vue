<template>
  <nav class="navbar gd_navbar" role="navigation" aria-label="main navigation">
      <div class="container">
    <div class="navbar-brand">
      <a class="navbar-item" href="/">
        <img
          src="~/static/img/logo.webp"
          width="300px"
          height="auto"
        />
      </a>

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
        <a class="navbar-item"> About Us </a>
        <a class="navbar-item"> Our Clients</a>
        <a class="navbar-item"> Our Services </a>
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