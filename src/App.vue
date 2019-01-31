<template>
  <div id="app">
    <div class="bg-grey p-4">
      <router-link to="/" class="no-underline text-grey-darkest">
        Home
      </router-link>
    </div>
    <router-view />
  </div>
</template>

<script>
import "@/assets/css/styles.css";

export default {
  name: "App"
};
</script>
