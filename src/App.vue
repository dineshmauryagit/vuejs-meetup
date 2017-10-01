<template>
  <v-app>
    <v-toolbar>
      <v-toolbar-title>DevMeetup</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-item>
        <v-btn flat>
          <v-icon left>supervisor_account</v-icon>
          View Meetup
        </v-btn>
      </v-toolbar-item>
    </v-toolbar>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        clipped: false,
        drawer: true,
        fixed: false,
        items: [
          { icon: 'bubble_chart', title: 'Inspire' }
        ],
        miniVariant: false,
        right: true,
        rightDrawer: false,
        title: 'Vuetify.js'
      }
    }
  }
</script>
