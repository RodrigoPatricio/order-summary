<template>
  <div class="plan-container">
    <div class="img-icon">
      <img src="../assets/icon-music.svg" alt="icon-music" class="icon" />
    </div>
    <div class="price">
      <p class="plan">
        <span>Annual Plan</span><br>$59.99/year
      </p>
    </div>
    <div class="highlight">
      <p>Change</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sumary",
};
</script>

<style>
.plan-container {
    max-width: 400px;
    padding: 20px 0 20px 0;
    border-radius: 10px;
    margin: auto;
    background-color: #f4f4f4;
    margin-top: 3em;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
span {
    font-weight: 900;
    font-size: 18px;
}
.highlight {
    color: purple;
    text-decoration: underline;
    font-size: 18px;
}
</style>
