<template>
  <div>
    <img src="../assets/dc-logo.png" alt="DC Logo" />
    <ul>
      <li>characters</li>
      <li id="active">comics</li>
      <li>movies</li>
      <li>tv</li>
      <li>games</li>
      <li>collectibles</li>
      <li>videos</li>
      <li>fans</li>
      <li>news</li>
      <li>shop</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HeaderExport",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div {
  display: flex;
  padding: 30px 0;
  justify-content: space-around;
  align-items: center;
  img {
    width: 100px;
    height: 100px;
  }
  ul {
    display: flex;
    list-style: none;
    column-gap: 10px;
    li {
      text-transform: uppercase;
      font-weight: bold;
    }
    #active {
      color: rgb(0, 140, 255);
      border-bottom: 2px solid rgb(0, 140, 255);
    }
  }
}
</style>
