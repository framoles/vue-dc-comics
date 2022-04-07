<template>
  <div class="card">
    <img :src="srcImg" :alt="title" />
    <span>{{ title }}</span>
    <div class="prices">
      <span>{{ price }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "LastSeries",
  props: {
    title: String,
    srcImg: String,
    price: String,
  },
};
</script>

<style scoped lang="scss">
.card {
  display: flex;
  flex-direction: column;
  width: calc((100% / 6) - 40px);
  position: relative;
  cursor: pointer;
  .prices {
    display: none;
    width: 100%;
    height: 100%;
    background-color: rgba(8, 7, 7, 0.678);
    position: absolute;
    span {
      text-align: center;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 2em;
    }
  }
  &:hover .prices {
    display: block;
  }
}
</style>