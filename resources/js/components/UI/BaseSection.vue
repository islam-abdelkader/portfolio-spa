<template>
  <section class="pt-4 pb-5">
    <h2 class="text-center fw-bold">{{ title }}</h2>
    <span class="mb-5 d-block text-center">{{ desc }}</span>
    <slot />
  </section>
</template>
<script>
export default {
  name: 'BaseSection',
  props: {
    title: {
      type: String,
      required: false,
      default: null
    },
    desc: {
      type: String,
      required: false,
      default: null
    }
  }
}
</script>
