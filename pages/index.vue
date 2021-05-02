<template>
  <div class="bg-gray-50 h-screen lg:flex items-center">
    <Hero />
  </div>
</template>

<script>
export default {
  async asyncData({ $content }) {
    const data = await $content("home").fetch();

    console.log("Data? probs not", data);
  }
};
</script>
