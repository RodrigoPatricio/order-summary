<template>
  <div class="container">
    <Header />
    <Advert />
    <Sumary />
    <Confirmation />
  </div>
</template>

<script>
import Header from "./components/Header";
import Advert from "./components/Advert";
import Sumary from "./components/Sumary";
import Confirmation from "./components/Confirmation";

export default {
  name: "App",
  components: {
    Header,
    Advert,
    Sumary,
    Confirmation,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600;800&family=Red+Hat+Display:wght@500;700;900&family=Roboto&display=swap');
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Red Hat Display;
  cursor: pointer;
  background-image: url("./assets/pattern-background-desktop.svg");
  background-color: hsl(225, 100%, 94%);
}
.container {
  max-width: 500px;
  margin: 100px auto;
  overflow: auto;
  min-height: 800px;
  border-radius: 15px;
  align-items: center;
  background-color: #fff;
  box-shadow: 0 10px 18px #888;
}
</style>
