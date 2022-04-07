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
        <img src="../assets/buy-comics-merchandise.png" alt="merchandise" />
        <span>dc merchandise</span>
      </div>
      <div class="set-up">
        <img src="../assets/buy-comics-subscriptions.png" alt="subscriptions" />
        <span>subscriptions</span>
      </div>
      <div class="set-up">
        <img
          src="../assets/buy-comics-shop-locator.png"
          alt="comics-shop-locator"
        />
        <span>comics shop locator</span>
      </div>
      <div class="set-up">
        <img src="../assets/buy-dc-power-visa.svg" alt="dc-power-visa" />
        <span>dc power visa</span>
      </div>
    </div>
    <div id="middle">
      <div id="foot-list">
        <div>
          <span>DC COMICS</span>
          <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <span>SHOP</span>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
        <div>
          <span>DC</span>
          <ul>
            <li>Terms of use</li>
            <li>Privacy policy</li>
            <li>Ad choise</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscription</li>
            <li>Talent Workshops</li>
            <li>CPSC Certficates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>
        <div>
          <span>SITES</span>
          <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>
      <img src="../assets/dc-logo-bg.png" alt="dc logo" />
    </div>
    <div id="down">
      <a href="#">SIGN UP NOW!</a>
      <div>
        <span>FOLLOW US</span>
        <img src="../assets/footer-facebook.png" alt="FB" />
        <img src="../assets/footer-twitter.png" alt="twitter" />
        <img src="../assets/footer-youtube.png" alt="YT" />
        <img src="../assets/footer-pinterest.png" alt="pinterest" />
        <img src="../assets/footer-periscope.png" alt="periscope" />
      </div>
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
    display: flex;
    justify-content: space-around;
    #foot-list {
      display: flex;
      margin-top: 3%;
      div {
        margin-right: 3%;
        ul {
          margin: 10px 0;
          li {
            list-style: none;
            color: rgb(114, 114, 114);
          }
        }
        span {
          font-weight: bold;
          font-size: 20px;
          color: white;
          margin-bottom: 10px;
        }
      }
    }
    img {
      height: 350px;
    }
  }
  #down {
    background-color: rgb(41, 41, 41);
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 30px;
    div {
      display: flex;
      align-items: center;
      column-gap: 20px;
      span {
        color: rgb(0, 132, 255);
        font-weight: bold;
      }
    }
    a {
      color: white;
      border: 1px solid rgb(0, 132, 255);
      text-decoration: none;
      padding: 10px;
      &:hover {
        background-color: rgb(70, 70, 70);
        transition: 200ms;
      }
    }
  }
}
</style>