<template>
  <v-card>
    <v-card-title class="display-1">
      <div
        dark
        v-text="title"
        class="display-1"
        style="background-color: pink"
      />
      <div
        class="body-1"
        v-text="description"
      />
    </v-card-title>
  </v-card>
</template>

<script>
export default {
  name: 'achievements-info',
  props: {
    title: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    }
  }
}
</script>
