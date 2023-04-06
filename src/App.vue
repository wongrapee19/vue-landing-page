<script setup>
import { onMounted } from "vue";
import { Modal } from "flowbite";
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";

onMounted(() => {
  const $buttonElement = document.querySelector("#button");
  const $modalElement = document.querySelector("#modal");
  const $closeButton = document.querySelector("#closeButton");

  const modalOptions = {
    backdropClasses:
      "bg-gray-900 bg-opacity-50 dark:bg-opacity-80 fixed inset-0 z-40",
  };

  if ($modalElement) {
    const modal = new Modal($modalElement, modalOptions);
    $buttonElement.addEventListener("click", () => modal.toggle());
    $closeButton.addEventListener("click", () => modal.hide());

    // programmatically show
    // modal.show();
  }
});
</script>
<template>
  <TheHeader />

  <footer>
    <br />
    <hr />
    <TheFooter />
  </footer>
</template>

<style scoped></style>
