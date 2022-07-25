<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script setup>
// export default defineNuxtComponent({
//   // async asyncData() {
//   //   console.log("Aysnc data", process.client);
//   //   return {};
//   // },
//   created() {
//     console.log("Created", process.client);
//   },
// });

useAsyncData(( ) => {
  console.log("Aysnc data", process.client);
  return {};
})
</script>
