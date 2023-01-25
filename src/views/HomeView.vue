<template>
  <div>
    <NavbarComp />
  </div>
</template>

<script>
import { defineComponent } from "vue";

import NavbarComp from "@/components/NavbarComp.vue";
// Components

export default defineComponent({
  name: "HomeView",

  components: {
    NavbarComp,
  },
});
</script>
