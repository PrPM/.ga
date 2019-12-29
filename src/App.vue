<template>
  <div id="app">
    <section class="bighead">
      The
      <b>progressive</b>
      <br />JS package manager.
      <p>
        Goal:
        <em>3x faster</em> than
        <em>NPM</em>.
      </p>
    </section>
    <section class="buttons">
      <a href="https://github.com/prpmjs">GitHub</a>
      <span class="separator">|</span>
      <a href="https://discord.gg/ptSSGt7">Discord</a>
    </section>
    <section class="logo">
      <img src="/prpm.png" />
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Raleway:800|Rubik:400,700&display=swap");

body {
  font-family: "Rubik", sans-serif;
}

body {
  margin: 0;
  padding: 0;
  border: none;
}

.bighead {
  padding: 50px;
  padding-left: 20vw;
  padding-top: 50vh;
  background-color: #ff6802;
  color: white;
  font-size: 3em;
}

.bighead > b {
  font-family: "Raleway", sans-serif;
  font-weight: 800;
}

.bighead > p {
  margin: 0;
  font-size: 20pt;
}

.bighead > p > em {
  font-weight: bold;
  font-style: normal;
}

.buttons {
  padding: 20px 0 0 20vw;
}

.buttons > .separator {
  color: #777777;
  font-size: 2em;
  margin: 0 0.75vw;
}

.buttons > a {
  color: #212121;
  font-size: 2em;
  text-decoration: none;
  transition: 100ms;
}

.buttons > a:hover {
  color: #666666;
}

.logo {
  height: 20px;
  width: 20px;
  position: absolute;
  top: 40px;
  left: 20vw;
}

.logo > img[src="/prpm.png"] {
  height: 70px;
}

.soon {
  font-size: 50px;
  color: rgb(168, 168, 168);
  padding-top: 50px;
  text-align: center;
}

@media screen and (max-width: 550px) {
  .bighead {
    padding: 200px 10px 20px;
  }
  .logo {
    top: 20px;
    left: 10px;
  }
  .buttons {
    padding: 20px;
  }
}
</style>
