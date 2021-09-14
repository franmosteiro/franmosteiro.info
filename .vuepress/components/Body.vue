<template>
  <div class="body">
    <p>
      I'm a <b>Product Engineer</b> from <a href="https://goo.gl/maps/acotGaE7nSeBR3ce7" target="_blank">Bilbao, Basque Country</a>
      <br/>
      👇 Here there are some links, in case you want to have a look and see what I'm up to 👇
    </p>
    <p>
      <a href="https://github.com/franmosteiro" target="_blank">
          <img :src="$withBase('/github-logo.png')" alt="github-logo">
      </a>
      <a href="mailto:fran@larivolta.es" target="_blank">
          <img :src="$withBase('/mail-logo.png')" alt="mailto-logo">
      </a> 
      <a href="https://twitter.com/fran_mosteiro" target="_blank">
          <img :src="$withBase('/twitter-logo.png')" alt="twitter-logo">
      </a>
    </p>
  </div>
</template>

<style scoped>
.body {
  margin: auto;
  width: 50%;
  padding: 10px;
  text-align: center;
}

img {
    width: 50px;
    height: 50px;
}
</style>
