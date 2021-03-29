<template>
  <div class="img">
    <div class="img_container">
      <ul class="img_content">
        <li class="img_text">PORTEN</li>
        <li class="img_line"></li>
        <li class="img_text_one">санкт-петербург</li>
      </ul>
    </div>
    <div class="content_footer">
      <p class="content_footer_text">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Purus interdum
        purus, est tortor pulvinar ut in. Fringilla a diam enim sed justo, sed
        iaculis sagittis. Tortor id eu interdum nec ut iaculis. Penatibus
        ullamcorper ultricies morbi ipsum sem metus pharetra, mi. Tortor nibh
        magna feugiat id nunc, dui nisl viverra.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "img",
};
</script>

<style lang="scss" scoped>
.img {
  display: block;
  justify-content: center;
  width: 100%;
  min-height: 810px;
  background: url("../assets/img/block_header/Rectangle 3.png") center;
  background-size: cover;
}
.img_container {
  display: flex;
  justify-content: center;
}
.img_content {
  display: block;
  width: 320px;
  height: 320px;
  border: 2px solid white;
  margin-top: 10rem;
  justify-content: center;
}
.img_text {
  font-family: "Post No Bills Jaffna";
  overflow: hidden;
  font-style: normal;
  font-weight: bold;
  font-size: 64px;
  line-height: 96px;
  height: 4.9rem;
  text-align: center;
  margin-top: 5rem;
  color: #ffffff;
}

.img_text_one {
  display: flex;
  justify-content: center;
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 22px;
  line-height: 28px;
  text-align: center;
  text-transform: uppercase;
  margin-top: 8px;
  color: #ffffff;
}
.img_line {
  display: flex;
  width: 11.1rem;
  height: 2px;
  background: #ffffff;
  margin-left: 4.4rem;
}
.content_footer {
  justify-content: center;
  margin-top: 4.5rem;
  display: flex;
}

.content_footer_text {
  width: 730px;
  height: 96px;
  text-align: center;
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 150%;
  text-align: center;
  text-transform: uppercase;
  color: #ffffff;
}
</style>
