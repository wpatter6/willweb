<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-xs-center">
        <logo class="text-xs-center" />
      </div>
      <v-card>
        <v-card-title class="headline">Modern Web and Mobile Application Development</v-card-title>
        <v-card-text>
          <p>WillWeb is a small modern web and app development shop.</p>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" flat nuxt to="/apps">Check out our Apps!</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  head() {
    return {
      meta: []
    }
  },
  components: {
    Logo
  }
}
</script>
