<template>
  <div class="theRights">
    <div class="container">
      <p class="left">© 2020 Все права защищены</p>
      <p class="right">Сделано Figma.info</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "theRights",
};
</script>

<style lang="scss" scoped>
.theRights {
  width: 100%;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: #0f0f0f;
  font-family: PT Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 16px;
  color: #d0d0d0;
}
.container {
  display: flex;
  width: 100%;
  justify-content: center;
}

.left {
  width: 50%;
}

.right {
  width: 50%;
}
</style>
