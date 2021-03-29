<template>
  <div class="header_navbar">
    <nav class="navbar">
      <ul class="navbar_wrapper">
        <li class="navbar_list">PORTEN</li>
      </ul>
      <ul class="navbar_wrap">
        <li class="navbar_content">Понравилось</li>
        <li class="navbar_content">личный кабинет</li>
        <li class="navbar_content">настройки</li>
        <li class="navbar_content_cart"></li>
        <li class="navbar_content_border"></li>
        <li class="navbar_content_border_two"></li>
        <li class="navbar_content_search"></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "headerBar",
};
</script>

<style lang="scss" scoped>
.header_navbar {
  height: 80px;
  width: 100%;
}
.navbar {
  background: #0f0f0f;
  display: flex;
  height: 80px;
  width: 100%;
}
.navbar_wrap {
  display: flex;
  // на flex ругаеться
  width: 50%;
  justify-content: end;
  align-items: center;
}
.navbar_wrapper {
  display: flex;
  width: 50%;
  text-align: end;
  align-items: center;
}
.navbar_list {
  padding-right: 26rem;
  font-family: "Post No Bills Jaffna";
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 54px;
  color: #fff;
}
.navbar_content {
  display: flex;
  justify-content: center;
  text-align: center;
  width: 9rem;
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 18px;
  text-transform: uppercase;
  color: #ffffff;
}
.navbar_content_cart {
  overflow: hidden;
  background: url("../assets/img/block_header/icon/Cart.png");
  background-size: cover;
  margin-left: 1rem;
  width: 20px;
  height: 14px;
}
.navbar_content_border {
  background: url("../assets/img/block_header/icon/border.png");
  background-size: cover;
  width: 3px;
  height: 3px;
  transform: translateX(-14px) translateY(7px);
}
.navbar_content_border_two {
  background: url("../assets/img/block_header/icon/border_two.png");
  background-size: cover;
  width: 4px;
  height: 4px;
  transform: translateX(-9px) translateY(8px);
}
.navbar_content_search {
  overflow: hidden;
  background: url("../assets/img/block_header/icon/Search.png");
  background-size: cover;
  width: 17px;
  margin-left: 2rem;
  height: 16px;
}
</style>
