<template>
  <div>
    <Navbar />
    <Hero />
    <Footer />
    <!-- <Appbar /> -->
    <!-- <Search/> -->

    <!-- <Modal /> -->
  </div>
</template>

<script>
import { onMounted } from "vue";
import { initFlowbite } from "flowbite";

// initialize components based on data attribute selectors
onMounted(() => {
  initFlowbite();
}); // export default {};
</script>

<style lang="scss" scoped></style>
