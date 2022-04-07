<template>
  <div>
    <div id="jumbotron"></div>
    <div id="main">
      <Series
        v-for="(item, index) in items"
        :key="index"
        :title="item.series"
        :srcImg="item.thumb"
        :price="item.price"
      >
      </Series>
      <a href="#">LOAD MORE</a>
    </div>
  </div>
</template>

<script>
import Series from "../components/Series.vue";

export default {
  name: "MainExport",
  props: {
    items: Array,
  },
  components: {
    Series,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#jumbotron {
  width: 100%;
  height: 300px;
  background-image: url("../assets/jumbotron.jpg");
}
#main {
  display: flex;
  flex-wrap: wrap;
  gap: 20px 40px;
  background-color: rgb(32, 32, 32);
  padding: 50px 10%;
  color: white;
  a {
    margin: auto;
    padding: 10px 30px;
    background-color: rgb(0, 132, 255);
    color: white;
    font-weight: bold;
    text-decoration: none;
    &:hover {
      background-color: rgb(0, 89, 255);
      transition: 200ms;
    }
  }
}
</style>