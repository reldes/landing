<template>
    <v-app>
        <LeftMenu />
        <v-main>
            <slot></slot>
        </v-main>
    </v-app>
</template>

<script lang="ts">
import LeftMenu from '@/components/LeftMenu.vue';

export default {
    name: 'Layout',
    components: {
        LeftMenu
    }
}
</script>

<style scoped>
/* Add any necessary styles here */
</style>