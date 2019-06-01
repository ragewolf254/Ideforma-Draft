<template>
  <v-list
    class="elevation-1"
  >
    <v-list-tile
      :key="i"
      v-for="(item, i) in items"
    >
      <v-list-tile-content>
        <v-list-tile-title>{{ item.task }}</v-list-tile-title>
      </v-list-tile-content>
    </v-list-tile>

  </v-list>
</template>

<script>
export default {
  name: 'list',
  props: {
    items: {
      type: Array,
      required: false
    }
  }
}
</script>
