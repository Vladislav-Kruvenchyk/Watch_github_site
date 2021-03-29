<template>
  <div class="footer">
    <div class="container">
      <div class="content">
        <div class="footer_header">
          <div class="footer_wrapper">
            <p class="footer_header_text">о магазине</p>
          </div>
          <div class="footer_container_left">
            <p class="footer_left_text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mi semper
              viverra nunc cursus tortor lectus nunc nulla nibh. Egestas amet
              consectetur vel vitae aliquam dictum suspendisse. Lobortis eget
              consequat, tellus et et sed turpis. Pretium quisque vitae, amet,
              porttitor odio ultricies massa pharetra leo. Et ipsum urna fames
              in sit mi ultrices nisi, nunc.
            </p>
          </div>
        </div>

        <div class="footer_header">
          <div class="footer_wrapper">
            <div class="footer_header_text_middle">категории</div>
          </div>

          <div class="footer_container_middle">
            <ul class="footer_wrap">
              <li class="footer_item_one">часы</li>
              <li class="footer_item_two">браслеты</li>
              <li class="footer_item_tree">ремни</li>
              <li class="footer_item_foure">ювелирные изделия</li>
              <li class="footer_item_five">запчасти</li>
            </ul>
          </div>
        </div>

        <div class="footer_header">
          <div class="footer_wrapper">
            <span class="footer_header_text">рассылка</span>
          </div>
          <div class="footer_container_right">
            <p class="footer_right_text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mi semper
              viverra nunc cursus tortor lectus nunc nulla nibh.
            </p>
          </div>
          <div class="footer_right_wrapper">
            <input
              type="text"
              placeholder="Вашу почта"
              class="footer_right_input"
            />
            <div class="footer_right_item">подписаться</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "footer",
};
</script>

<style lang="scss" scoped>
.footer {
  width: 100%;
  height: 400px;
  background: url("../assets/img/block_footer/Rectangle 15.png");
  background-size: cover;
}
.container {
  display: flex;
  width: 100%;
  height: 400px;
  justify-content: center;
}
.content {
  display: flex;
  width: 1130px;
  height: 100%;
  justify-content: center;
}
.footer_header {
  display: block;
  width: 100%;
}
.footer_container_left {
  display: flex;
  width: 100%;
  height: 14rem;
}
.footer_left_text {
  display: flex;
  width: 350px;
  height: 147px;
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 150%;
  color: #ffffff;
}
.footer_wrapper {
  display: flex;
  height: 10rem;
}
.footer_header_text {
  display: flex;
  align-items: center;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 32px;
  text-transform: uppercase;
  color: #ffffff;
}
.footer_container_middle {
  display: flex;
  width: 100%;
  flex-wrap: wrap;
  flex-shrink: 2;
}

.footer_header_text_middle {
  display: flex;
  align-items: center;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 32px;
  text-transform: uppercase;
  margin-left: 1rem;
  color: #ffffff;
}
.footer_middle {
  display: flex;
}
.footer_wrap {
  display: flex;
  height: 7rem;
  width: 100%;
  flex-wrap: wrap;
}

.footer_item_one {
  display: flex;
  width: 70px;
  height: 41px;
  margin-left: 1rem;
  align-items: center;
  justify-content: center;
}
.footer_item_two {
  display: flex;
  width: 98px;
  height: 41px;
  margin-left: 1rem;
  justify-content: center;
  align-items: center;
}
.footer_item_tree {
  display: flex;
  width: 79px;
  height: 41px;
  margin-left: 1rem;
  justify-content: center;
  align-items: center;
}
.footer_item_foure {
  display: flex;
  width: 164px;
  height: 41px;
  margin-left: 1rem;
  justify-content: center;
  align-items: center;
}

.footer_item_five {
  display: flex;
  width: 100px;
  height: 41px;
  margin-left: 1rem;
  justify-content: center;
  align-items: center;
}
.footer_item_one,
.footer_item_two,
.footer_item_tree,
.footer_item_foure,
.footer_item_five {
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 150%;
  background: #0f0f0f;
  color: #d0d0d0;
}
.footer_container_right {
  display: flex;
  width: 355px;
  height: 63px;
}
.footer_right_text {
  display: flex;
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 150%;
  color: #ffffff;
}
.footer_right_wrapper {
  display: flex;
  margin-top: 1rem;
}
.footer_right_input {
  display: flex;
  width: 210px;
  height: 42px;
  padding-left: 1rem;
}
input::placeholder {
  color: #ffff;
}
input {
  background: rgba(255, 255, 255, 0.4);
}
.footer_right_item {
  display: flex;
  width: 140px;
  height: 42px;
  align-items: center;
  justify-content: center;
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 150%;
  letter-spacing: 0.05em;
  color: #ffffff;
  background: #0f0f0f;
}
</style>
