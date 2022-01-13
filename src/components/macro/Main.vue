<template>
  <main>
    <Marketing />
    <Workwith />
    <Trusted />
    <Weboost />
    <Team />
    <Resource />
  </main>
</template>

<script>
import Marketing from "../sections/Marketing.vue";
import Workwith from "../sections/Workwith.vue";
import Trusted from "../sections/Trusted.vue";
import Weboost from "../sections/Weboost.vue";
import Team from "../sections/Team.vue";
import Resource from "../sections/Resource.vue";
export default {
  name: "Main",
  components: {
    Marketing,
    Workwith,
    Trusted,
    Weboost,
    Team,
    Resource,
  },
};
</script>

<style lang="scss" scoped>
</style>