<template>
  <div class="brands">
    <div class="brands_header">
      <div class="brands_content">
        <p class="brands_header_text">наши бренды</p>
        <div class="brands_header_line">
          <div class="line"></div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="brands_wrap">
        <div class="brands_item">
          <div class="brands_list"></div>
        </div>
      </div>

      <div class="brands_wrap">
        <div class="brands_item">
          <div class="brands_list"></div>
        </div>
      </div>

      <div class="brands_wrap">
        <div class="brands_item">
          <div class="brands_list"></div>
        </div>
      </div>

      <div class="brands_wrap">
        <div class="brands_item">
          <div class="brands_list"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "brands",
};
</script>

<style lang="scss" scoped>
.brands {
  width: 100%;
  height: 362px;
  background: #000;
  padding-top: 4rem;
}

.container {
  display: flex;
  width: 100%;
  height: 10rem;
  flex-wrap: wrap;
  flex-shrink: 2;
  justify-content: center;
  align-items: center;
}

.brands_header {
  width: 100%;
  height: 7rem;
  display: flex;
}
.brands_content {
  display: block;
}

.brands_header_text {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 5rem;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
  text-align: center;
  text-transform: uppercase;
  color: #fff;
}
.brands_header_line {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 2rem;
}

.line {
  width: 5rem;
  height: 1px;
  background: #fff;
}

.brands_wrap {
  display: flex;
  width: 18rem;
}
.brands_item {
  display: flex;
}
.brands_list {
  width: 255px;
  height: 94px;
  background: url("../assets/img/block_brands/Rectangle 2.png");
  background-size: cover;
}
</style>
