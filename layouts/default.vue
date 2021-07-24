<template>
  <div>
    <client-only>
      <Navbar />
      <Nuxt />
    </client-only>
  </div>
</template>

<script>
export default {
  created () {
    // eslint-disable-next-line no-console
    console.log('Created & Maintained by DwiiUnknown (https://dwii.my.id/).')
  }
}
</script>

<style>
:root {
    --color1: #101010;
    --color2: #181818;
    --color3: #202020;
    --color4: #303030;
    --color5: #8D0605;
    --color6: #9B0705;
    --color7: #AA0805;
    --text-color: #ffffff;
    --text-color-black: #000000;
}

body {
    font-family: 'Comic Neue', cursive;
}

.content-1 h1 {
    font-size: 3rem;
}

.blank-space1 {
    height: 14rem;
}
.blank-space2 {
    height: 12rem;
}
.blank-space3 {
    height: 10rem;
}
.blank-space4 {
    height: 8rem;
}
.blank-space5 {
    height: 6rem;
}
.blank-space6 {
    height: 4rem;
}

@media only screen and (max-width: 1700px) {
    .blank-space1 {
        height: 12rem;
    }
    .blank-space2 {
        height: 10rem;
    }
    .blank-space3 {
        height: 8rem;
    }
    .blank-space4 {
        height: 6rem;
    }
    .blank-space5 {
        height: 4rem;
    }
    .blank-space6 {
        height: 2rem;
    }
}

@media only screen and (max-width: 1400px) {
    .blank-space1 {
        height: 10rem;
    }
    .blank-space2 {
        height: 8rem;
    }
    .blank-space3 {
        height: 6rem;
    }
    .blank-space4 {
        height: 5rem;
    }
    .blank-space5 {
        height: 2rem;
    }
    .blank-space6 {
        height: 1rem;
    }
}

@media only screen and (max-width: 576px) {
    .main {
        font-size: 0.875rem;
    }
    p {
        font-size: 0.875rem;
    }
    .content-1 h1 {
        font-size: 2rem;
    }
    .lead {
        font-size: 1rem;
    }
}

.text-black {
  color: var(--text-color-black);
}

.text-white {
  color: var(--text-color);
}

.navbar {
  background-color: var(--color1);
}
.nav-link, .nav-link:active {
  font-size: 1.25rem;
  color: var(--color7) !important;
}
.nav-link:hover {
  color: var(--color5) !important;
}
.nuxt-link-exact-active {
  color: var(--color7) !important;
  font-weight: 700;
}

.content-1 {
    background-color: var(--color2);
    color: var(--text-color);
    min-height: 100vh;
    max-width: 100vw;
}
.content-2 {
    background-color: var(--color3);
    color: var(--text-color);
    max-width: 100vw;
}
.content-3 {
    background-color: var(--color4);
    color: var(--text-color);
    max-width: 100vw;
}
.content-4 {
    background-color: var(--color5);
    color: var(--text-color);
    max-width: 100vw;
}

.center-flex {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.center {
    display: flex;
    justify-content: center;
    align-items: center;
}

.btn {
    background-color: var(--color3);
    color: var(--text-color);
}

::-webkit-scrollbar {
    background-color: #202324;
    color: #aba499;
}
::-webkit-scrollbar-thumb {
    background-color: #454a4d;
}
* {
    scrollbar-color: #454a4d #202324;
}

#toTop {
    background-color: var(--color4);
    color: var(--text-color-black);
    display: none;
    z-index: 901;
    position: fixed;
    bottom: 2rem;
    right: 2rem;
}

.card {
    background-color: var(--color2);
    color: var(--text-color);
}

.project-btn {
    z-index: 801;
    position: absolute;
    right: 0.5rem;
    top: 0.5rem;
}

.footer {
    background-color: var(--text-color-black);
}
.footer a {
    color: var(--text-color);
    text-decoration: none;
}
</style>
