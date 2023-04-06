<template lang="">
  <div class="store-con">
    From A: {{ store.count }}
    <br />
    From B: {{ store.count2 }}
  </div>
  <div class="store-con1">
    <button
      @click="store.increment()"
      class="bg-blue-400 py-3 px-4 rounded-lg hover:bg-blue-600"
    >
      Click Plus A :]
    </button>
  </div>

  <div class="store-con1">
    <button
      @click="store.increment2()"
      class="bg-blue-400 py-3 px-4 rounded-lg hover:bg-blue-600"
    >
      Click Plus B :]
    </button>
  </div>
</template>
<script setup>
import { reactive } from "vue";

const store = reactive({
  count: 0,
  count2: 0,
  increment() {
    this.count++;
  },
  increment2() {
    this.count2++;
  },
});
</script>
<style scoped>
.store-con {
  display: flex;
  justify-content: center;
  padding-top: 90px;
}

.store-con1 {
  display: flex;
  justify-content: center;
  padding-top: 20px;
}
</style>
