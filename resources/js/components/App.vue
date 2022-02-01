<template>
  <div id="app">
    <loading ref="loading" />

    <transition name="page" mode="out-in">
      <component :is="layout" v-if="layout" />
    </transition>
  </div>
</template>

<script>
import Loading from './Loading'

// Load layout components dynamically.
const requireContext = require.context('~/layouts', false, /.*\.vue$/)

const layouts = requireContext.keys()
  .map(file =>
    [file.replace(/(^.\/)|(\.vue$)/g, ''), requireContext(file)]
  )
  .reduce((components, [name, component]) => {
    components[name] = component.default || component
    return components
  }, {})

export default {
  el: '#app',

  components: {
    Loading
  },

  data: () => ({
    layout: null,
    defaultLayout: 'default'
  }),

  metaInfo () {
    const { appName } = window.config

    return {
      title: appName,
      titleTemplate: `%s · ${appName}`
    }
  },

  mounted () {
    this.$loading = this.$refs.loading
  },

  methods: {
    /**
     * Set the application layout.
     *
     * @param {String} layout
     */
    setLayout (layout) {
      if (!layout || !layouts[layout]) {
        layout = this.defaultLayout
      }

      this.layout = layouts[layout]
    }
  }
}
</script>
<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap');
@import url('https://unicons.iconscout.com/release/v4.0.0/css/line.css');

:root {
    --header-height: 3rem;
    --main-transition: .3s;
    /*========== Colors ==========*/
    /* Change favorite color */
    --hue-color: 203; /*Purple 250 - Green 142 - Blue 230 - Pink 340*/

    /* HSL color mode */
    --first-color: hsl(var(--hue-color), 69%, 61%);
    --first-color-second: hsl(var(--hue-color), 69%, 61%);
    --first-color-alt: hsl(var(--hue-color), 57%, 53%);
    --first-color-lighter: hsl(var(--hue-color), 92%, 85%);
    --title-color: hsl(var(--hue-color), 8%, 15%);
    --text-color: hsl(var(--hue-color), 8%, 45%);
    --text-color-light: hsl(var(--hue-color), 8%, 65%);
    --input-color: hsl(var(--hue-color), 70%, 96%);
    --body-color: hsl(var(--hue-color), 60%, 99%);
    --scroll-bar-color: hsl(var(--hue-color), 12%, 90%);
    --scroll-thumb-color: hsl(var(--hue-color), 12%, 80%);

    --container-color: #FFF;
    --swiper-theme-color: var(--first-color);
    /*========== Font and typography ==========*/
    --body-font: 'Poppins', sans-serif;

    /* .5rem = 8px, 1rem = 16px, 1.5rem = 24px ... */
    --big-font-size: 2rem;
    --h1-font-size: 1.5rem;
    --h2-font-size: 1.25rem;
    --h3-font-size: 1.15rem;
    --normal-font-size: .938rem;
    --small-font-size: .813rem;
    --smaller-font-size: .75rem;

    /*========== Font weight ==========*/
    --font-medium: 50;
    --font-semi-bold: 600;

    /*========== Margenes Bottom ==========*/
    /* .25rem = 4px, .5rem = 8px, .75rem = 12px ... */
    --mb-0-25: .25rem;
    --mb-0-5: .5rem;
    --mb-0-75: .75rem;
    --mb-1: 1rem;
    --mb-1-5: 1.5rem;
    --mb-2: 2rem;
    --mb-2-5: 2.5rem;
    --mb-3: 3rem;

    /*========== z index ==========*/
    --z-tooltip: 10;
    --z-fixed: 100;
    --z-modal: 1000;
}
/* @media screen and (min-width: 968px) {
    :root {
        --big-font-size: 3rem;
        --h1-font-size: 2.25rem;
        --h2-font-size: 1.5rem;
        --h3-font-size: 1.25rem;
        --normal-font-size: 1rem;
        --small-font-size: .875rem;
        --smaller-font-size: .813rem;
    }
} */
/*=========================================================*/
/*========================== BASE =========================*/
/*=========================================================*/
*{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

html{
    scroll-behavior: smooth !important;
}

body{
    margin: 0 0 var(--header-height) 0;
    font-family: var(--body-font);
    font-size: var(--normal-font-size);
    background-color: var(--body-color);
    color: var(--text-color);
}
body.dark-theme{
    /* HSL color mode */
    --first-color-second: hsl(var(--hue-color), 30%, 8%);
    --title-color: hsl(var(--hue-color), 8%, 95%);
    --text-color: hsl(var(--hue-color), 8%, 75%);
    --input-color: hsl(var(--hue-color), 29%, 16%);
    --body-color: hsl(var(--hue-color), 28%, 12%);
    --container-color: hsl(var(--hue-color), 29%, 16% );
    --scroll-bar-color: hsl(var(--hue-color), 12%, 48%);
    --scroll-thumb-color: hsl(var(--hue-color), 12%, 36%);
}
h1,h2,h3,h4{
    color: var(--title-color);
    font-family: var(--font-semi-bold);
}

ul{
    list-style: none;
}

a{
    text-decoration: none;
}

img{
    max-width: 100%;
    height: auto;
}
/*=========================================================*/
/*======================= Nav BAR ======================*/
/*=========================================================*/
.title-color{
  color: var(--title-color) !important;

}
.navbar-light a.navbar-brand,
.navbar-light .navbar-nav .nav-item a {
  color: var(--title-color);
}

.title-color:hover,
.title-color:active,
.navbar-light a.navbar-brand:hover,
.navbar-light a.navbar-brand:active,
.navbar-light .navbar-nav .nav-item  a:hover,
.navbar-light .navbar-nav .nav-item  a.active {
  color: var(--first-color);
}
/*=========================================================*/
/*======================= SCROLL BAR ======================*/
/*=========================================================*/
::-webkit-scrollbar{
    width: .5rem;
    background-color: var(--scroll-bar-color);
    border-radius: .5rem;
}
::-webkit-scrollbar-thumb{
    background-color: var(--scroll-thumb-color);
    border-radius: .5rem;
}

::-webkit-scrollbar-thumb:hover {
    background-color: var(--text-color-light);
}

</style>
