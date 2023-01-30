<template>
  <section class="py-24 bg-white">

    <div class="max-w-3xl px-10 mx-auto xl:px-5">
  
      <div class="flex flex-col justify-center space-y-8">
        <h2 class="w-full mx-auto text-4xl font-extrabold leading-none text-left text-gray-900 sm:text-5xl md:text-7xl">Weekly Newsletter</h2>
        <p class="w-full max-w-3xl mx-auto text-xl text-left text-gray-500 md:text-2xl">Get the latest trends and updates in your inbox each week. We will provide you with top notch designs and resources.</p>

        <FormRegister />

        <p class="text-gray-400"><span class="font-medium text-gray-700">Trusted by</span> over 27,000 subscribers.</p>
  
    </div>
    </div>
  
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import RegisterForm from '../molecules/RegisterForm.vue';
export default Vue.extend({
  components: {
    FormRegister: RegisterForm
  },
})
</script>

<style scoped>

</style>