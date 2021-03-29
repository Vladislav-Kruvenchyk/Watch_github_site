<template>
  <div class="collection">
    <div class="collection_wrap">
      <div class="collection_box">
        <h1 class="collection_header_text">СЕЗОН 2020/21</h1>
        <div class="collection_header_line">
          <div class="line"></div>
        </div>
      </div>
      <div class="colletion_box_two">
        <div class="collection_innet">
          <div class="collection_block"></div>
        </div>

        <div class="collection_innet">
          <div class="collection_block"></div>
        </div>

        <div class="collection_innet">
          <div class="collection_block"></div>
        </div>
      </div>

      <div class="collection_footer_block_two">
        <div class="collection_footer">
          <span class="text">Louis XVI ATHOS</span>
          <span class="text_two">165 000 руб. </span>
        </div>

        <div class="collection_footer">
          <span class="text">Louis XVI ATHOS</span>
          <span class="text_two">165 000 руб. </span>
        </div>

        <div class="collection_footer">
          <span class="text">Louis XVI ATHOS</span>
          <span class="text_two">165 000 руб. </span>
        </div>
      </div>
    </div>
    <div class="collection_img">
      <div class="collection_img_container">
        <span class="collection_img_text">Новая коллекция</span>
        <div class="collection_img_line">
          <div class="line"></div>
        </div>

        <div class="collection_img_footer">
          <div class="collection_img_wrap">
            <span class="collection_img_footer_text">Каталог</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "blockCollection",
};
</script>

<style lang="scss" scoped>
.collection_img_container {
  width: 100%;
}
.collection_img_text {
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
  text-align: center;
  text-transform: uppercase;
  color: #ffffff;
}
.collection_img_line {
  display: flex;
  width: 100%;
  justify-content: center;
  margin-top: 1rem;
}
.line {
  width: 8rem;
  height: 1px;
  background: #fff;
}
.collection_img_footer {
  width: 100%;
  margin-top: 2rem;
}
.collection_img_wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.collection_img_footer_text {
  font-family: PT Sans;
  border: 2px solid;
  font-style: normal;
  font-weight: normal;
  width: 10rem;
  height: 3rem;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 18px;
  line-height: 23px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #ffffff;
}
.collection_footer_block_two {
  display: flex;
  justify-content: center;
}
.text {
  display: flex;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 24px;
  color: #ffffff;
}
.text_two {
  display: flex;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 21px;
  color: #d0d0d0;
}
.collection_footer {
  display: block;
  width: 260px;
  margin-left: 50px;
  margin-top: 2rem;
}
.colletion_box_two {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 4rem;
}
.line {
  width: 10rem;
  height: 1px;
  background: #fff;
}
.collection_header_line {
  justify-content: center;
  display: flex;
  margin-top: 1rem;
}
.collection_box {
  display: block;
  justify-content: center;
  align-items: center;
  padding-top: 6rem;
  margin-left: 2rem;
}
.collection_header_text {
  display: block;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
  text-align: center;
  text-transform: uppercase;
  color: #fff;
}
.collction_text {
  display: block;
}
.collection_innet {
  display: flex;
  width: 260px;
  height: 325px;
  margin-top: 2rem;
  margin-left: 3rem;
  background: #191b1c;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.collection_block {
  display: flex;
  width: 214px;
  height: 215px;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: url("../assets/img/block_season/62050 1.png") no-repeat;
  background-size: cover;
}
.collection {
  display: flex;
  width: 100%;
  height: 730px;
}
.collection_wrap {
  width: 60%;
  height: 730px;
  flex-wrap: wrap;
  background: #000;
}
.collection_img {
  height: 730px;
  width: 40%;
  background: url("../assets/img/block_season/Rectangle 8.png");
  background-size: cover;
  justify-content: center;
  align-items: center;
  text-align: center;
  display: flex;
  padding-top: 26rem;
}
.collection_wrapper {
  display: flex;
  background: #191b1c;
  width: 15rem;
}
.collection_list {
  width: 214px;
  height: 115px;
  padding: 2rem;
  background: #000;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: url("../assets/img/block_season/62050 1.png") no-repeat;
  background-size: cover;
}
</style>
