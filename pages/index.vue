<template>
  <div class="bg-gray-50 h-screen lg:flex items-center">
    <!-- Hero section -->
    <div
      class="max-w-7xl m-auto h-3/4 grid grid-cols-1 lg:grid-cols-2 p-5 md:p-10 lg:p-20"
    >
      <div>
        <h1
          class="text-5xl md:text-6xl lg:text-7xl font-bold text-center lg:text-left"
        >
          A place to learn more about <span class="text-green-500">Vue</span>
        </h1>
        <p
          class="text-lg sm:text-2xl mt-4 text-center lg:text-left text-gray-600"
        >
          Helpful documentation on how to solve certain edge cases, build
          complex projects, and scaling large applications.
        </p>
        <div class="w-full text-center mt-8 lg:text-left">
          <a
            class="transition cursor-pointer w-10 border border-green-500 p-3 rounded hover:bg-green-500 hover:text-white"
            >GET STARTED</a
          >
        </div>
      </div>
      <div class="w-full h-auto">
        <HeroSvg />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
