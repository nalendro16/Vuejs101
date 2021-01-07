<template>
  <div class="logos-wraper">
    <h2 class="title-header">Find Logo</h2>
    <div class="item-logos">
      <img class="logo" src="../assets/mastercard.svg" alt="mastercards logo" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/paypal.svg" alt="paypal logo" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/taylor.svg" alt="taylor logo" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'logos',
}
</script>

<style scoped>
.logos-wraper {
  width: 70%;
  overflow: hidden;
  margin: auto;
}
.item-logos {
  float: left;
  margin: 0 70px 70px 0;
  width: 150px;
  height: 150px;
}
.item-logos .logo {
  width: 150px;
  height: 150px;
}
.title-header {
  margin-bottom: 80px;
}
</style>
