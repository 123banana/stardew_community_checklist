<template>
  <div>
    <BundleNav />
    <section class="section">
      <router-view></router-view>
    </section>
  </div>
</template>

<script>
import BundleNav from '@/components/bundles/BundleNav.vue'
export default {
  components: {BundleNav},
  name: 'bundles'
}
</script>
