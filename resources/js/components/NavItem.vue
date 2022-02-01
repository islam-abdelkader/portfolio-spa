<template>
  <li class="nav-item">
    <router-link :to="to" class="nav-link" active-class="active">
      {{ $t(title) }}
    </router-link>
  </li>
</template>
<script>
export default {
  name: 'NavItem',
  props: {
    title: { type: String, default: null },
    to: { type: String, default: null }
  }
}
</script>
