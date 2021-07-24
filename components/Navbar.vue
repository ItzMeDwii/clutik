<template>
  <div>
    <nav class="navbar fixed-top navbar-expand-lg">
      <div class="container">
        <nuxt-link class="navbar-brand" to="/">
          <img width="54" height="48" src="/icon.png">
        </nuxt-link>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarToggler"
          aria-controls="navbarToggler"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars fa-lg text-white" />
        </button>
        <div id="navbarToggler" class="collapse navbar-collapse">
          <ul class="navbar-nav ms-auto my-2 my-lg-0">
            <li class="nav-item me-lg-2 mb-lg-0 mb-2">
              <nuxt-link class="nav-link active" to="/">
                Beranda
              </nuxt-link>
            </li>
            <li class="nav-item me-lg-2 mb-lg-0 mb-2">
              <nuxt-link class="nav-link active" to="/kegiatan">
                Kegiatan
              </nuxt-link>
            </li>
            <li class="nav-item me-lg-2 mb-lg-0 mb-2">
              <nuxt-link class="nav-link active" to="/blog">
                Blog
              </nuxt-link>
            </li>
            <li class="nav-item me-lg-2 mb-lg-0 mb-2">
              <nuxt-link class="nav-link active" to="/tentang">
                Tentang
              </nuxt-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
