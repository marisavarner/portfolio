<!-- components/Navbar.vue -->

<template>
  <div class="container">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="/">Marisa Varner | UX Developer</a>
        <button class="button navbar-burger">
          <span></span>
          <span></span>
          <span></span>
        </button>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">
          <nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link>
          <nuxt-link class="navbar-item" to="/about">About</nuxt-link>
          <nuxt-link class="navbar-item" to="/contact">Contact</nuxt-link>
          <nuxt-link class="navbar-item" to="/blog">Blog</nuxt-link>
        </div>
      </div>
    </nav>
  </div>
</template>