<template>
  <div class="flex flex-col w-full mx-auto space-y-5 md:space-y-0 md:space-x-5 md:flex-row">
    <input type="text" class="flex-1 w-full px-5 py-5 text-2xl bg-gray-200 border border-gray-300 rounded-lg focus:ring-4 focus:border-blue-600 focus:ring-blue-600 focus:ring-opacity-50 focus:outline-none" data-primary="blue-600" data-rounded="rounded-lg" placeholder="Email Address">
    <a href="#_" class="flex-shrink-0 px-10 py-5 text-2xl font-medium text-center text-white bg-blue-600 rounded-lg focus:ring-4 focus:ring-blue-600 focus:ring-opacity-50 focus:ring-offset-2 focus:outline-none" data-primary="blue-600" data-rounded="rounded-lg">Sign Up</a>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'RegisterForm'
})
</script>

<style scoped>

</style>