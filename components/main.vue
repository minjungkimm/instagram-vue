<template>
  <main class="main-container">
    <section class="main-section">
      <Content />
      <Side />
    </section>
  </main>
</template>
<script>
import Content from '~/components/content.vue'
import Side from '~/components/side.vue'
export default {
  components: {
    Content,
    Side,
  },
}
</script>
