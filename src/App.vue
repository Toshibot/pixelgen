<script setup lang="ts">
</script>

<template>
  <body id="Body" class="t-dark">
    <main class="o-main u-vert-center">
      <div class="logo"><span class="pixel">pixel</span>gen<span class="dot">.</span>au</div>
      <div>coming soon</div>
    </main>
  </body>
</template>

<style scoped lang="scss">

</style>
<script lang="ts">

export default {
  components: {
  },
  data() {
  }
}
</script>
<style scoped lang="scss">
  body {
    overflow: hidden;
    position: absolute;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100%;
  }
  .logo {
    font-family: "Jersey 10", serif;
    font-weight: 400;
    font-style: normal;
    font-size: 64px;
    text-align: center;
    color: #999;
    .pixel {
      color: #fff;
    }
    .dot {
      color: #F33464;
    }
  }
</style>

