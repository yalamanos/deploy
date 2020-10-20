<template>
  <Layout>

    <about />
    <newsletter />

  </Layout>
</template>

<script>
import Layout from '~/layouts/Default.vue'
import about from '~/components/about.vue'
import newsletter from '~/components/newsletter.vue'

export default {
  components: {
    Layout,
    about,
    newsletter,
  }
}
</script>
