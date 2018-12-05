<template>
  <div class="layout-wrapper">
    <header>
      <nav class="navbar navbar-dark bg-dark navbar-expand-lg fixed-top">
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
          <!-- <button
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
              <a
                class="nav-link nav-link"
                href="#about">About</a>
              <a
                class="nav-link nav-link"
                href="#services">Services</a>
              <nuxt-link
                class="nav-link nav-link"
                to="/blog">Blog</nuxt-link>
              <a
                class="nav-link nav-link"
                href="#contact">Contact</a>
            </div>
          </div> -->
        </div>
      </nav>
    </header>

    <nuxt/>

    <footer class="bg-secondary section main-footer text-center">
      <div class="container">
        2018 &copy; LimberBits | Tel:
        <a
          class="text-dark"
          href="tel:+36/30-636-0775">+36/30-636-0775</a> | Email:
        <a
          class="text-dark"
          href="mailto:info@limberbits.com">info@limberbits.com</a>
      </div>
    </footer>
  </div>
</template>

<style lang="scss">
@import './assets/scss/app';
$logo-height: 2.25rem;
$nav-paddings: $navbar-padding-y + $navbar-brand-padding-y;
$body-padding-top: $nav-paddings * 2 + $logo-height;

body {
  padding-top: $body-padding-top;
  min-height: 100vh;
}

.layout-wrapper {
  display: flex;
  flex-direction: column;
}

.main-footer {
  margin-top: auto;
}

.section {
  padding: 4rem 0;
}
</style>
