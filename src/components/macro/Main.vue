<template>
  <main>
    <Marketing />
    <Workwith />
  </main>
</template>

<script>
import Marketing from "../sections/Marketing.vue";
import Workwith from "../sections/Workwith.vue";
export default {
  name: "Main",
  components: {
    Marketing,
    Workwith,
  },
};
</script>

<style lang="scss" scoped>
</style>