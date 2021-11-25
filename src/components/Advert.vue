<template>
  <div class="sumary">
    <h1 class="title">{{ title }}</h1>
    <p class="text">{{ text }}</p>
  </div>
</template>

<script>
export default {
  name: "Advert",
  data() {
    return {
      title: "Order Sumary",
      text: "You can now listen to millions of songs, audiobooks and podecasts on any device anywhere you like",
    };
  },
};
</script>

<style>
.sumary {
  max-width: 350px;
  margin: auto;
  margin-top: 2em;
  text-align: center;
}
.title {
  font-weight: 700;
  font-size: 35px;
}
.text {
  font-size: 17px;
  margin-top: 1em;
}
</style>
