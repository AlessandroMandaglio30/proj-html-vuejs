<template>
  <main>
    <Marketing />
    <Workwith />
    <Trusted />ù
    <Weboost />
  </main>
</template>

<script>
import Marketing from "../sections/Marketing.vue";
import Workwith from "../sections/Workwith.vue";
import Trusted from "../sections/Trusted.vue";
import Weboost from "../sections/Weboost.vue";
export default {
  name: "Main",
  components: {
    Marketing,
    Workwith,
    Trusted,
    Weboost,
  },
};
</script>

<style lang="scss" scoped>
</style>