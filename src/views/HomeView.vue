<script setup>
import TheWelcome from "../components/TheWelcome.vue";
import TheMain1 from "../components/TheMain1.vue";
</script>

<template>
  <main>
    <div class="grid-contain">
      <div class="grid-top">
        <TheMain1 />
        <TheMain1 />
      </div>
    </div>
  </main>
</template>

<style scoped>
@media screen and (min-width: 320px) {
  .grid-contain {
    padding: 40px;
    display: grid;
  }
  .grid-top {
    padding-top: 50px;
  }
}

@media screen and (min-width: 992px) {
  .grid-contain {
    padding: 50px;
    display: grid;
  }
  .grid-top {
    padding-top: 20px;
  }
}
</style>
