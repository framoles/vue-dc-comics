<template>
  <div>
    <div id="up">
      <div class="set-up">
        <img
          src="../assets/buy-comics-digital-comics.png"
          alt="digitalcomics"
        />
        <span>digital comics</span>
      </div>
      <div class="set-up">
        <img
          src="../assets/buy-comics-digital-comics.png"
          alt="digitalcomics"
        />
        <span>digital comics</span>
      </div>
      <div class="set-up">
        <img
          src="../assets/buy-comics-digital-comics.png"
          alt="digitalcomics"
        />
        <span>digital comics</span>
      </div>
      <div class="set-up">
        <img
          src="../assets/buy-comics-digital-comics.png"
          alt="digitalcomics"
        />
        <span>digital comics</span>
      </div>
      <div class="set-up">
        <img
          src="../assets/buy-comics-digital-comics.png"
          alt="digitalcomics"
        />
        <span>digital comics</span>
      </div>
    </div>
    <div id="middle">
      <ul></ul>
      <ul></ul>
      <ul></ul>
      <ul></ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterExport",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div {
  #up {
    background-color: rgb(4, 157, 245);
    display: flex;
    padding: 30px;
    justify-content: space-around;
    .set-up {
      color: white;
      display: flex;
      align-items: center;
      column-gap: 10px;
      img {
        width: 40px;
      }
      span {
        text-transform: uppercase;
      }
    }
  }
  #middle {
    background-size: cover;
    background-image: url("../assets/footer-bg.jpg");
    height: 400px;
  }
}
</style>