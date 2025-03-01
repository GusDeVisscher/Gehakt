<template>
  <nav class="flex justify-content-between align-items-center w-full bg-blue-600 text-white p-4 fixed top-0 left-0 shadow-md">
    <div class="flex flex-row align-items-center">
      <img src="@/assets/logo.png" class="w-3rem mr-3" alt="">
      <img src="@/assets/text_slogan.png" class="w-10rem mt-3" alt="">
    </div>

    <div class="flex gap-4">
      <RouterLink to="/" class="nav-link">Home</RouterLink>
      <RouterLink to="/about" class="nav-link">About</RouterLink>
      <RouterLink to="/products" class="nav-link">Products</RouterLink>
      <RouterLink to="/contact" class="nav-link">Contact</RouterLink>
    </div>
  </nav>
</template>

<script setup lang="ts">
</script>

<style scoped>
/* Styling for navigation links */
.nav-link {
  text-decoration: none;
  color: white;
  font-weight: bold;
  transition: color 0.3s ease;
}

.nav-link:hover {
  color: #dbeafe; /* Lighter blue */
}

/* Add margin to content so it doesn’t hide behind the navbar */
body {
  padding-top: 60px; /* Adjust if navbar height changes */
}
</style>
