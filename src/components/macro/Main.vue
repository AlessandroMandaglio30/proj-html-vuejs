<template>
  <main>
    <Marketing />
    <Workwith />
    <Trusted />
  </main>
</template>

<script>
import Marketing from "../sections/Marketing.vue";
import Workwith from "../sections/Workwith.vue";
import Trusted from "../sections/Trusted.vue";
export default {
  name: "Main",
  components: {
    Marketing,
    Workwith,
    Trusted,
  },
};
</script>

<style lang="scss" scoped>
</style>