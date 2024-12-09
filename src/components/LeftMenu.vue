<template>
    <v-navigation-drawer app>
        <v-list>
            <v-list-item>
                <v-list-item-content>
                    <router-link to="/">
                        <v-list-item-title>Quick start</v-list-item-title>
                    </router-link>
                </v-list-item-content>
            </v-list-item>
            <v-list-item>
                <v-list-item-content>
                    <router-link to="/templates">
                        <v-list-item-title>
                            Templates
                        </v-list-item-title>
                    </router-link>
                </v-list-item-content>
            </v-list-item>
            <v-list-item>
                <v-list-item-content>
                    <router-link to="/contacts">
                    <v-list-item-title>
                        Contacts
                    </v-list-item-title>
                </router-link>
                </v-list-item-content>
            </v-list-item>
        </v-list>
    </v-navigation-drawer>
</template>

<script>
export default {
    name: 'LeftMenu'
}
</script>

<style scoped>
/* Add any necessary styles here */
</style>