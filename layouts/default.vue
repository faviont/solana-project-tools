<template>
  <v-app>
    <div style="background-color:#060826;" class="flex-col">
      <AppHeader />
      <div class="flex justify-center items-center flex-col mt-5 mr-5 ml-5">
          <div class="w-full max-w-2xl">
              <div class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
              <Nuxt />
              </div>
          </div>
      </div>
      <div class="flex flex-grow"></div>
      <AppFooter />
    </div>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import AppHeader from "@/components/base/AppHeader.vue";
import AppFooter from "@/components/base/AppFooter.vue";
export default Vue.extend({
  components: {
    AppHeader,
    AppFooter
  }
});
</script>