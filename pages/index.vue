<template>
  <div class="gray_area">
    <NuxtPage></NuxtPage>
    <p>首頁</p>
    <svg
      id="search"
      xmlns="http://www.w3.org/2000/svg"
      width="2em"
      height="2em"
      viewBox="0 0 1024 1024"
    >
      <path
        fill="currentColor"
        d="M1014.64 969.04L703.71 656.207c57.952-69.408 92.88-158.704 92.88-256.208c0-220.912-179.088-400-400-400s-400 179.088-400 400s179.088 400 400 400c100.368 0 192.048-37.056 262.288-98.144l310.496 312.448c12.496 12.497 32.769 12.497 45.265 0c12.48-12.496 12.48-32.752 0-45.263zM396.59 736.527c-185.856 0-336.528-150.672-336.528-336.528S210.734 63.471 396.59 63.471c185.856 0 336.528 150.672 336.528 336.528S582.446 736.527 396.59 736.527z"
      ></path>
    </svg>
  </div>
  <BooksPicArea />
  <hr />
  <h3>熱門</h3>
  <BooksPicArea />
  <hr />
  <h3>追蹤</h3>
  <BooksPicArea />
</template>

<style>
@import "~/assets/index.css";
</style>
<script>
import BooksPicArea from "~/components/BooksPicArea.vue";
export default {
  layout: "default",
  methods: {},
};
</script>
