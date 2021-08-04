<template class="relative">
  <div class="absolute flex flex-row justify-start space-x-4 top-0 md:flex-col md:inset-x-1/2 md:space-x-0 md:space-y-6 lg:flex-row-reverse lg:right-0 lg:space-y-0 lg:space-x-4 lg:space-x-reverse">
    <div class="h-28 w-28 bg-indigo-300 md:bg-red-500 lg:bg-purple-800 lg:bg-opacity-25">1</div>
    <div class="h-28 w-28 bg-indigo-400 md:bg-yellow-400 lg:bg-blue-800 lg:bg-opacity-50">2</div>
    <div class="h-28 w-28 bg-indigo-500 md:bg-green-500 lg:bg-indigo-800 lg:bg-opacity-75">3</div>
  </div>
</template>

<script>
export default {
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
