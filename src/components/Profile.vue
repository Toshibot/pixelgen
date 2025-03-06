<template>
  <section class="profile-section">
    <article>
      <div class="logo"><span class="pixel">pixel</span>gen<span class="dot">.</span>au</div>
      <div>coming soon</div>
    </article>
  </section>
</template>
<script lang="ts">

export default {
  components: {
  },
  data() {
  }
}
</script>
<style scoped lang="scss"> 
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
  article {
    text-align: center;
    padding: 0 16px;

    p {
      max-width: 600px;
      text-align: left;
      display: block;
      margin: 0 auto;
      line-height: 1.6;
    }
  }
</style>