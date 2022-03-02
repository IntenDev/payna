<template>
  <div class="container">
    <div>
      <div class="managePay">
        <h1>Manage Payroll Like an Expert</h1>
      </div>
      <p>Payna is helping you to setting up the payroll without required any finance skills or knowledge before</p>
      <button>Get Started</button>
    </div>
    <div>
      <div class="manageImg"></div>
      <div class="analytics"></div>
      <div class="builk"></div>
    </div>
  </div>

</template>

<script>
export default {
  name: "managePay"
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  width: 1272px;
  position: relative;
  left: 120px;
  top: 40px;
  /*border: 1px solid black;*/
}
.manageImg {
  background-image: url('/img/image3.png');
  width: 540px;
  height: 400px;
  border-radius: 50px;
}
.analytics {
  background-image: url('/img/Group7.png');
  position: absolute;
  width: 249px;
  height: 191px;
  left: 521px;
  top: 130px;
  z-index: 10;
}
.builk {
  background-image: url('/img/Group6.png');
  position: absolute;
  width: 249px;
  height: 102px;
  left: 1000px;
  top: 41px;


}
</style>
