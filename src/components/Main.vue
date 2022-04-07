<template>
  <div>
    <Series v-for="(item, index) in item" :key="index" :serie="item" />
  </div>
</template>

<script>
import Series from "../components/Series.vue";

export default {
  name: "MainExport",
  props: {
    item: Array,
  },
  components: {
    Series,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>