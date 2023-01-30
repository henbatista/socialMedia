<template>
  <Register />
</template>

<script lang="ts">
import Vue from 'vue'
import RegisterTemplate from "@/components/templates/RegisterTemplate.vue"

export default Vue.extend({
  components: {
    Register: RegisterTemplate
  },
  layout: "default",
})
</script>