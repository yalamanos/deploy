<template>
  <div>
    <siteHeader />
    <slot></slot>
    <siteFooter />
  </div>
</template>




<script>
import siteHeader from '~/components/header.vue'
import siteFooter from '~/components/footer.vue'
import '~/assets/variables.scss'

export default {
  components: {
    siteHeader,
    siteFooter
  },
}
</script>