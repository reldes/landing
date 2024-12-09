<template>
  <v-app>
    <v-main>
      <Layout>
        <router-view />
      </Layout>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Layout from '@/layouts/Layout.vue';
export default {
  components: {
    Layout
  }
}
</script>
<script lang="ts" setup>
  //
</script>
