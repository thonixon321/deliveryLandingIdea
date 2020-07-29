<template>
  <div
    id="app"
    class="container"
  >
    <div class='header transparentBG'>
      <Watermelon num='2' />
      <Apple />
      <Banana />
      <Broccoli />
      <Watermelon num='1' />
      <Onion />
      <Carrot num='1' />
      <Carrot num='2' />
      <Garlic />
      <Pumpkin />
      <nav class='nav'>
        <div class='nav__logo'>
          <Grocery />
          <span class="nav__logo--name">DeliverIt</span>
        </div>
        <ul class='nav__items'>
          <li class='nav__item'>Home</li>
          <li class='nav__item'>Staff</li>
          <li class='nav__item'>Pricing</li>
          <li class='nav__item'>Shop</li>
          <li class='nav__item'>Blog</li>
          <li class='nav__item'>Contact</li>
          <li class='nav__item'>
            <Cart />
          </li>
          <li class='nav__item'>
            <Search />
          </li>
        </ul>
      </nav>
      <figure class='hero__img'>
        <img
          src='./assets/img/happy-person-transparent.png'
          alt='hero image'
        >
      </figure>
      <header class='header-text'>
        <h1 class="header-text__main">Promotions of the week</h1>
        <p class="header-text__text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellendus, delectus, enim soluta dolor.</p>
        <button class="header-text__button">See our products</button>
      </header>
      <svg
        class="curvedSvg"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 1320 500"
        preserveAspectRatio="none"
      >
        <path
          fill="white"
          fill-opacity="1"
        >
          <animate
            attributeName="d"
            values="
          M0,192 C220,100,440,100,660,192 C880,290,1100,290,1320,192 L1320 500 L0 500;
          M0,100 C220,100,440,292,660,292 C880,292,1100,100,1320,100 L1320 500 L0 500;
          M0,192 C220,290,440,290,660,192 C880,100,1100,100,1320,192 L1320 500 L0 500;
          M0,292 C220,292,440,100,660,100 C880,100,1100,292,1320,292 L1320 500 L0 500;
          M0,192 C220,100,440,100,660,192 C880,290,1100,290,1320,192 L1320 500 L0 500
        "
            keyTimes="0; 0.25; 0.5; 0.75; 1"
            dur="10s"
            repeatCount="indefinite"
          />
        </path>
      </svg>
    </div>
    <div class='promote'>
      <h1 class='heading--1'>
        Best Foods
      </h1>
      <p class='heading--2'>
        ShopIt takes eating to a whole new level with its deliciousness and gourmet specialties
      </p>
      <p class='promote__details'>Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde voluptatem ipsa ut suscipit corporis doloremque possimus at cumque, veniam ipsum fugit dicta voluptatibus fugiat, architecto ipsam numquam consequuntur blanditiis aliquid!Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde voluptatem ipsa ut suscipit!</p>
    </div>
    <div class='features__bg'></div>
    <div class='features__col features__col-1'>
      <button class='features__button'>
        <span class='features__button-icon'>
          <Play /></span>
        <span class='features__button-text'>Italian foods</span>
      </button>
      <button class='features__button'>
        <span class='features__button-icon'>
          <Play /></span>
        <span class='features__button-text'>Chinese foods</span>
      </button>
      <button class='features__button'>
        <span class='features__button-icon'>
          <Play /></span>
        <span class='features__button-text'>Greek foods</span>
      </button>
      <button class='features__button'>
        <span class='features__button-icon'>
          <Play /></span>
        <span class='features__button-text'>Japonese foods</span>
      </button>
    </div>
    <div class='features__video'>
      <video
        class="features__video-content"
        autoplay
        muted
        loop
      >
        <source
          src="./assets/img/food.mp4"
          type="video/mp4"
        >
      </video>
    </div>
    <div class='features__col features__col-2'>
      <button class='features__button'>
        <span class='features__button-icon'>
          <Play /></span>
        <span class='features__button-text'>Indian foods</span>
      </button>
      <button class='features__button'>
        <span class='features__button-icon'>
          <Play /></span>
        <span class='features__button-text'>Mexican foods</span>
      </button>
      <button class='features__button'>
        <span class='features__button-icon'>
          <Play /></span>
        <span class='features__button-text'>Thai foods</span>
      </button>
      <button class='features__button'>
        <span class='features__button-icon'>
          <Play /></span>
        <span class='features__button-text'>American foods</span>
      </button>
    </div>

    <div class='info__text--1'>
      <h1 class='heading--1'>
        Great Delivery
      </h1>
      <p class='heading--2'>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, laudantium voluptatem quis deserunt eaque ex suscipit.
      </p>
      <button class="header-text__button not-first">See our products</button>
    </div>

    <figure class='info__img--1'>
      <img
        src='./assets/img/deliveryman.png'
        alt='info image'
      >
    </figure>

    <div class='info__text--2'>
      <h1 class='heading--1'>
        Highest Ratings
      </h1>
      <p class='heading--2'>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, laudantium voluptatem quis deserunt eaque ex suscipit.
      </p>
      <button class="header-text__button not-first">See our products</button>
    </div>

    <figure class='info__img--2'>
      <img
        src='./assets/img/oldmanthumb.png'
        alt='info image'
      >
    </figure>
    <footer class='footer'>
      <div class='footer__topic footer__about'>
        <h3 class='footer__header'>About Us</h3>
        <ul class='footer__list'>
          <li class='footer__list--item'>Our Heritage</li>
          <li class='footer__list--item'>Our Products</li>
          <li class='footer__list--item'>Stories and News</li>
          <li class='footer__list--item'>Customer Service</li>
        </ul>
      </div>
      <div class='footer__topic footer__career'>
        <h3 class='footer__header'>Careers</h3>
        <ul class='footer__list'>
          <li class='footer__list--item'>Culture and Values</li>
          <li class='footer__list--item'>Diversity and Inclusion</li>
          <li class='footer__list--item'>College Achievement Plan</li>
          <li class='footer__list--item'>Locations</li>
        </ul>
      </div>
      <div class='footer__topic footer__business'>
        <h3 class='footer__header'>For Businesses</h3>
        <ul class='footer__list'>
          <li class='footer__list--item'>Suppliers</li>
          <li class='footer__list--item'>Corporate Gift Card Sales</li>
          <li class='footer__list--item'>Office and Foodservice</li>
          <li class='footer__list--item'>Support Center</li>
        </ul>
      </div>
      <div class='footer__topic footer__order'>
        <h3 class='footer__header'>Ways to Order</h3>
        <ul class='footer__list'>
          <li class='footer__list--item'>Order on the Web</li>
          <li class='footer__list--item'>Download the App</li>
          <li class='footer__list--item'>Delivery</li>
          <li class='footer__list--item'>Google Assistant</li>
        </ul>
      </div>
      <div class='footer__logo'>
        <div class='footer__logo-header'>
          <Grocery />
          <span class="nav__logo--name">DeliverIt</span>
        </div>
        <div class="footer__copyright">&copy; 2020 DeliverIt Company. All rights reserved.</div>
      </div>
    </footer>
  </div>
</template>

<script>
import Grocery from "./assets/vueSVGs/grocery";
import Cart from "./assets/vueSVGs/cart";
import Search from "./assets/vueSVGs/search";
import Play from "./assets/vueSVGs/play";
import Apple from "./assets/vueSVGs/apple";
import Banana from "./assets/vueSVGs/banana";
import Broccoli from "./assets/vueSVGs/broccoli";
import Watermelon from "./assets/vueSVGs/watermelon";
import Onion from "./assets/vueSVGs/onion";
import Carrot from "./assets/vueSVGs/carrot";
import Garlic from "./assets/vueSVGs/garlic";
import Pumpkin from "./assets/vueSVGs/pumpkin";

export default {
  name: "App",
  components: {
    Grocery,
    Cart,
    Search,
    Play,
    Apple,
    Banana,
    Broccoli,
    Watermelon,
    Onion,
    Carrot,
    Garlic,
    Pumpkin,
  },
};
</script>

<style lang="scss">
@font-face {
  font-family: Calistoga;
  font-style: normal;
  font-weight: 300;
  src: url("./fonts/Calistoga-Regular.ttf");
}
@import "./styles/global.scss";

.curvedSvg path {
  animation: pathAnim 10s linear infinite;
}

.features {
  &__bg {
    grid-column: 1 / -1;
    grid-row: 3 / 7;
    align-self: stretch;
    z-index: -1;
    background-image: url(./assets/img/circlesBG.svg);
    background-size: cover;
  }
}

@keyframes pathAnim {
  0% {
    d: path(
      "M0,192 C220,100,440,100,660,192 C880,290,1100,290,1320,192 L1320 500 L0 500"
    );
  }
  25% {
    d: path(
      "M0,100 C220,100,440,292,660,292 C880,292,1100,100,1320,100 L1320 500 L0 500"
    );
  }
  50% {
    d: path(
      "M0,192 C220,290,440,290,660,192 C880,100,1100,100,1320,192 L1320 500 L0 500"
    );
  }
  75% {
    d: path(
      "M0,292 C220,292,440,100,660,100 C880,100,1100,292,1320,292 L1320 500 L0 500"
    );
  }
  100% {
    d: path(
      "M0,192 C220,100,440,100,660,192 C880,290,1100,290,1320,192 L1320 500 L0 500"
    );
  }
}
</style>
