<template>
  <div class="grid-con">
    <img src="../assets/banner.png" alt="" />

    <div class="grid-value">
      <div>
        <p>
          <span class="texthead"> Voice Recognition </span> <br />
          It is a long established fact that a reader will be distracted by the
          readable content of a page when looking at its layout. The point of
          using Lorem Ipsum is that it has a more-or-less normal distribution of
          letters, as opposed to using 'Content here, content here', making it
          look like readable English. Many desktop publishing packages and web
          page editors now use Lorem Ipsum as their default model text, There
          are many variations of passages of Lorem Ipsum available, but the
          majority have suffered alteration in some form,
        </p>
        <br />
        <button
          type="button"
          class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
          style="border-radius: 50px"
        >
          learn more
        </button>
        <button
          type="button"
          class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
          style="border-radius: 50px"
        >
          Link
        </button>
      </div>
    </div>
  </div>
  <br />
  <hr />
  <br />
  <div class="grid-con">
    <div class="grid-value">
      <div>
        <p>
          <span class="texthead"> Voice Recognition </span> <br />
          There are many variations of passages of Lorem Ipsum available, but
          the majority have suffered alteration in some form, by injected
          humour, or randomised words which don't look even slightly believable.
          If you are going to use a passage of Lorem Ipsum, you need to be sure
          there isn't anything embarrassing hidden in the middle of text. All
          the Lorem Ipsum generators on the Internet tend to repeat predefined
          chunks as necessary, making this the first true generator on the
          Internet. There are many variations of passages of Lorem Ipsum
          available,
        </p>
        <br />
        <button
          type="button"
          class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
          style="border-radius: 50px"
        >
          learn more
        </button>
        <button
          type="button"
          class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
          style="border-radius: 50px"
        >
          Link
        </button>
      </div>
    </div>
    <img src="../assets/banner.jpg" alt="" />
  </div>
</template>
<script setup></script>
<style scoped>
.grid-con {
  padding-left: 20px;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  justify-content: center;
  grid-column-gap: 2rem;
  align-items: center;
}
/* .grid-con2 {
  padding-top: 20px;
  padding-left: 10px;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  justify-content: center;
  align-items: center;
  grid-column-gap: 2rem;
} */
.grid-con2 img {
  border-radius: 60px;
  width: 90%;
}
.grid-con img {
  border-radius: 60px;
  width: 90%;
}
.grid-value {
  padding-left: 20px;
  display: grid;
}

.texthead {
  font-size: 40px;
}
.button-con {
  padding-top: 30px;
}
</style>
