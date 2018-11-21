<template>
  <div>
    <header>
      <nav class="navbar navbar-dark navbar-expand-lg main-navbar fixed-top">
        <div class="container">
          <nuxt-link
            class="navbar-brand d-flex align-items-center"
            to="/">
            <img
              src="~/assets/img/limberbits-logo.svg"
              height="36"
              class="d-inline-block align-top brand-logo"
              alt="Logo">
            <h1 class="h4 mb-0 ml-2">LimberBits</h1>
          </nuxt-link>
          <button
            class="navbar-toggler border-0"
            type="button"
            aria-controls="main-navbar"
            aria-expanded="false"
            aria-label="Toggle navigation">
            <span class="navbar-toggler-icon" />
          </button>
          <div
            id="main-navbar"
            class="collapse navbar-collapse">
            <div class="navbar-nav ml-auto">
              <nuxt-link
                class="nav-item nav-link"
                to="/">Home
              </nuxt-link>
              <nuxt-link
                class="nav-link nav-link"
                to="/about">About</nuxt-link>
              <nuxt-link
                class="nav-link nav-link"
                to="/services">Services</nuxt-link>
              <nuxt-link
                class="nav-link nav-link"
                to="/blog">Blog</nuxt-link>
              <nuxt-link
                class="nav-link nav-link"
                to="/contact">Contact</nuxt-link>
            </div>
          </div>
        </div>
      </nav>
    </header>
    <nuxt/>
  </div>
</template>

<style lang="scss">
@import './assets/scss/app';
$logo-height: 2.25rem;
$nav-paddings: $navbar-padding-y + $navbar-brand-padding-y;
$body-padding-top: $nav-paddings * 2 + $logo-height;

body {
  padding-top: $body-padding-top;
}
.main-navbar {
  background: $body-color;
}
</style>
