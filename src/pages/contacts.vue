<template>
  <v-container>
    <h1>Contact Us</h1>
    <v-row>
      <v-col cols="12" md="6">
        <v-card class="mb-4">
          <v-card-title>
            <v-icon left>mdi-email</v-icon>
            Email
          </v-card-title>
          <v-card-text>
            <a href="mailto:alexsokolianskiy@gmail.com">alexsokolianskiy@gmail.com</a>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" md="6">
        <v-card class="mb-4">
          <v-card-title>
            Discord Channel
          </v-card-title>
          <v-card-text>
            <a href="https://discord.gg/vz3Pu9BMcW" target="_blank">Join our Discord</a>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" md="6">
        <v-card class="mb-4">
          <v-card-title>
            <v-icon left>mdi-github</v-icon>
            GitHub
          </v-card-title>
          <v-card-text>
            <a href="https://github.com/reldes" target="_blank">https://github.com/reldes</a>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" md="6">
        <v-card class="mb-4">
          <v-card-title>
            <v-icon left>mdi-map-marker</v-icon>
            Address
          </v-card-title>
          <v-card-text>
            st. Zhukovsky 64, Zaporozhye, Ukraine, 69063
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
export default {
  name: 'Contacts'
}
</script>