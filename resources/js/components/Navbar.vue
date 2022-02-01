<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-transparent">
    <div class="container-md">
      <router-link
        :to="{ name: user ? 'home' : 'welcome' }"
        class="navbar-brand"
      >
        {{ $t('islam') }}
      </router-link>
      <div>
        <button
          class="navbar-toggler shadow-none border-0 title-color"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbar"
          @click="nav = !nav"
        >
          <i v-if="nav" class="uil uil-apps" />
          <i v-else class="uil uil-times" />
        </button>
      </div>
      <div id="navbar" class="collapse navbar-collapse">
        <ul class="navbar-nav">
          <locale-dropdown />
        </ul>

        <ul class="navbar-nav ms-auto">
          <nav-item title="portfolio" :to="{ name: 'portfolio' }" />
          <nav-item title="about" :to="{ name: 'about' }" />
          <nav-item title="skills" :to="{ name: 'skills' }" />
          <nav-item title="services" :to="{ name: 'services' }" />
          <nav-item title="contact" :to="{ name: 'contact' }" />

          <!-- Authenticated -->
          <!-- <li v-if="user" class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle text-dark"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <img
                :src="user.photo_url"
                class="rounded-circle profile-photo me-1"
              />
              {{ user.name }}
            </a>
            <div class="dropdown-menu">
              <router-link
                :to="{ name: 'settings.profile' }"
                class="dropdown-item ps-3"
              >
                <fa icon="cog" fixed-width />
                {{ $t('settings') }}
              </router-link>

              <div class="dropdown-divider" />
              <a href="#" class="dropdown-item ps-3" @click.prevent="logout">
                <fa icon="sign-out-alt" fixed-width />
                {{ $t('logout') }}
              </a>
            </div>
          </li> -->
          <!-- Guest -->
          <!-- <template v-else>
            <nav-item title="login" :to="{ name: 'login' }" />
            <nav-item title="register" :to="{ name: 'register' }" />
          </template> -->
          <li class="nav-item">
            <a
              class="shadow-none border-0 bg-transparent nav-link"
              @click="toggleMode"
            >
              <i v-if="mode" class="uil uil-moon" />
              <i v-else class="uil uil-sun" />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import { mapGetters } from 'vuex'
import LocaleDropdown from './LocaleDropdown'
import NavItem from './NavItem.vue'
import BaseButton from './UI/BaseButton.vue'

export default {
  components: {
    LocaleDropdown,
    NavItem,
    BaseButton
  },

  data: () => ({
    appName: window.config.appName,
    nav: true,
    mode: true
  }),

  computed: mapGetters({
    user: 'auth/user'
  }),

  methods: {
    async logout() {
      // Log out the user.
      await this.$store.dispatch('auth/logout')

      // Redirect to login.
      this.$router.push({ name: 'login' })
    },
    toggleMode() {
      if (this.mode) {
        document.body.classList.add('dark-theme')
      } else document.body.classList.remove('dark-theme')

      this.mode = !this.mode
    }
  }
}
</script>

<style scoped>
.profile-photo {
  width: 2rem;
  height: 2rem;
  margin: -0.375rem 0;
}

/* .container {
  max-width: 1100px;
} */

</style>
