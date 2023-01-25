<template>
  <div>
    <v-btn class="bg-red text-white"> Clikck </v-btn>

    <v-btn flat class="bg-black">
      <v-icon icon="mdi-delete-empty-outline"></v-icon>
    </v-btn>
  </div>
</template>

<script>
import { defineComponent } from "vue";

// Components

export default defineComponent({
  name: "HomeView",
});
</script>
