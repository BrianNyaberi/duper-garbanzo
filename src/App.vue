<template>
<div class="container mt-12 form-section mx-auto px-4 font-sans">
<form class="shadow-md rounded-lg px-8 py-6 mb-4 border-2 border-gray-200"> <!-- New Change -->
<h3 class="text-xl mb-8 mx-auto text-center font-bold text-purple-600">Shipping Address</h3>
<div class="mb-4">
<input type="text" placeholder="Name" class="bg-gray-200 border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500" />
<input type="text" placeholder="Street" class="mt-5 bg-gray-200 border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500" />
<input type="text" placeholder="City" class="mt-5 bg-gray-200 border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500" />
<div class="flex">
<input type="text" placeholder="State" class="mr-1 mt-5 bg-gray-200 border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500" />
<input type="text" placeholder="Postal Code" class="ml-1 mt-5 bg-gray-200 border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500" />
</div>
<div class="flex items-center justify-between">
<input type="text" placeholder="Phone" class="mr-1 mt-5 bg-gray-200 border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500" />
<input type="text" placeholder="Email" class="ml-1 mt-5 bg-gray-200 border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500" />
</div>
<button class="cursor-pointer mt-7 w-full shadow bg-purple-600 hover:bg-purple-600 focus:shadow-outline focus:outline-none text-white font-bold py-2 px-4 rounded mt-4" type="button">
Continue
</button>
</div>
</form>
</div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  // components: {
  //   HelloWorld
  // }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
