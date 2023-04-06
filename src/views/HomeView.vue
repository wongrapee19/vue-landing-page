<script setup>
import TheWelcome from "../components/TheWelcome.vue";
import TheMain1 from "../components/TheMain1.vue";
</script>

<template>
  <main>
    <div class="grid-contain">
      <TheMain1 />
    </div>
  </main>
</template>

<style scoped>
.grid-contain {
  padding-top: 100px;
  display: grid;
}
</style>
