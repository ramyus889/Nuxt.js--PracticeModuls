<script>
export default {
  name: "default",
  mounted() {
    document.title = "Nuxt.js";
  },
};
</script>
<template>
  <v-app>
    <v-main>
      <UseHeader />
      <div class="mt-[100px] sm:mx-[50px] mx-[30px]">
        <slot />
      </div>
    </v-main>
  </v-app>
</template>
