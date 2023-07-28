<template>

    <v-layout class="overflow-visible" style="height: 56px;">
      <v-bottom-navigation
        v-model="value"
        :bg-color="color"
        mode="shift"
      >
        <v-btn>
          <v-icon>mdi-tshirt-crew-outline</v-icon>
  
          <span>Tshirt</span>
        </v-btn>
  
        <v-btn>
          <v-icon>mdi-lingerie</v-icon>
  
          <span>Tights</span>
        </v-btn>
  
        <v-btn>
          <v-icon>mdi-human-female-dance</v-icon>
  
          <span>Trasher</span>
        </v-btn>
  
        <v-btn>
          <v-icon>mdi-arm-flex</v-icon>
  
          <span>Jerseys</span>
        </v-btn>

        <v-btn>
          <v-icon>mdi-tshirt-crew-outline</v-icon>
  
          <span>Tshirt</span>
        </v-btn>
  
        <v-btn>
          <v-icon>mdi-lingerie</v-icon>
  
          <span>Tights</span>
        </v-btn>
      </v-bottom-navigation>
    </v-layout>
  </template>

<script>
export default {
  data: () => ({ value: 1 }),

  computed: {
    color () {
      switch (this.value) {
        case 0: return 'blue-grey'
        case 1: return 'teal'
        case 2: return 'brown'
        case 3: return 'indigo'
        default: return 'blue-grey'
      }
    },
  },
}
</script>