<template>
  <div class="navbar">
    <div class="logo">
      <div class="rectangle">
        <div class="ellipse1"></div>
        <div class="ellipse2"></div>
      </div>
      <div class="textlogo"><span>Payna</span></div>
    </div>
    <menu>
      <ul>
        <li>Home</li>
        <li>Features</li>
        <li>Showcase</li>
        <li>Pricing</li>
      </ul>
    </menu>
  </div>
</template>

<script>
export default {
  name: "navbar"
}
</script>

<style scoped>
.navbar {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  width: 1272px;
  height: 48px;
  position: absolute;
  left: 120px;
  top: 40px;
  border: 1px solid black;
}
.logo {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
}
.rectangle{
  position: relative;
  width: 48px;
  height: 34px;
  left: 0px;
  top: 0px;
  /*background: #F5F6FB;*/
  border-radius: 10px;
}
.ellipse1 {
  position: absolute;
  width: 12px;
  height: 12px;
  left: 9px;
  top: 15px;
  border-radius: 50%;
  background: #207DFF;
}
.ellipse2 {
  position: absolute;
  width: 12px;
  height: 12px;
  left: 27px;
  top: 15px;
  border-radius: 50%;
  background: #F06157;
}
.textlogo {
  width: 91px;
  height: 42px;
  position: absolute;
  left: 60px;
  top: 0px;
  font-family: Poppins;
  font-style: normal;
  font-weight: 600;
  font-size: 28px;
  line-height: 42px;
  /* identical to box height */
  color: #070F18;
}
menu {
  position: relative;
  width: 435px;
  height: 24px;
  left: 439px;
  top: 15px;
}
li {
  display: inline;
  font-family: Poppins;
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 24px;
}
</style>
