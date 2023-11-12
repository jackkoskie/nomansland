<template>
  <div>
    <Navbar />
    <Banner />
    <NuxtPage />
  </div>
</template>

<script setup>
useHead({
  title: "No Man's Land",
  link: [
    {
      href: 'https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css',
      rel: 'stylesheet',
      crossorigin: 'anonymous',
    },
  ],
  script: [
    {
      src: 'https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js',
      crossorigin: 'anonymous',
    },
  ],
});
</script>
