<template>
  <div class="newArrials">
    <div class="newArrials_header">
      <p class="newArrials_header_text">новые поступления</p>
      <div class="newArrials_header_line">
        <div class="line"></div>
      </div>
    </div>

    <div class="container">
      <div class="container_wrapper">
        <div class="newArrials_content">
          <div class="newArrials_wrap">
            <div class="newArrials_list"></div>
          </div>
          <p class="newArrials_text">Louis XVI ATHOS</p>
          <p class="newArrials_prise">165 000 руб.</p>
        </div>

        <div class="newArrials_content">
          <div class="newArrials_wrap">
            <div class="newArrials_list"></div>
          </div>
          <p class="newArrials_text">Louis XVI ATHOS</p>
          <p class="newArrials_prise">165 000 руб.</p>
        </div>

        <div class="newArrials_content">
          <div class="newArrials_wrap">
            <div class="newArrials_list"></div>
          </div>
          <p class="newArrials_text">Louis XVI ATHOS</p>
          <p class="newArrials_prise">165 000 руб.</p>
        </div>

        <div class="newArrials_content">
          <div class="newArrials_wrap">
            <div class="newArrials_list"></div>
          </div>
          <p class="newArrials_text">Louis XVI ATHOS</p>
          <p class="newArrials_prise">165 000 руб.</p>
        </div>

        <div class="newArrials_content">
          <div class="newArrials_wrap">
            <div class="newArrials_list"></div>
          </div>
          <p class="newArrials_text">Louis XVI ATHOS</p>
          <p class="newArrials_prise">165 000 руб.</p>
        </div>

        <div class="newArrials_content">
          <div class="newArrials_wrap">
            <div class="newArrials_list"></div>
          </div>

          <p class="newArrials_text">Louis XVI ATHOS</p>
          <p class="newArrials_prise">165 000 руб.</p>
        </div>

        <div class="newArrials_content">
          <div class="newArrials_wrap">
            <div class="newArrials_list"></div>
          </div>
          <p class="newArrials_text">Louis XVI ATHOS</p>
          <p class="newArrials_prise">165 000 руб.</p>
        </div>

        <div class="newArrials_content">
          <div class="newArrials_wrap">
            <div class="newArrials_list"></div>
          </div>
          <p class="newArrials_text">Louis XVI ATHOS</p>
          <p class="newArrials_prise">165 000 руб.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "arrials",
};
</script>

<style lang="scss" scoped>
.newArrials {
  overflow: hidden;
  display: block;
  width: 100%;
  height: 1289px;
  background: #000;
  justify-content: center;
  align-items: center;
}
.newArrials_header {
  display: block;
}
.newArrials_header_text {
  display: flex;
  width: 100%;
  height: 12rem;
  padding-top: 4rem;
  justify-content: center;
  align-items: center;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
  text-align: center;
  text-transform: uppercase;
  color: #ffffff;
}

.newArrials_header_line {
  display: flex;
  justify-content: center;
}

.line {
  width: 8rem;
  height: 1px;
  background: #fff;
}
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  margin-top: 3rem;
  width: 100%;
  height: 934px;
}
.container_wrapper {
  overflow: hidden;
  display: flex;
  width: 1200px;
  height: 920px;
  flex-wrap: wrap;
  justify-content: center;
}
.newArrials_content {
  overflow: hidden;
  display: flex;
  flex-wrap: wrap;
  flex-shrink: 1;
  width: 260px;
  height: 27rem;
  margin-left: 2rem;
  margin-top: 2rem;
}
.newArrials_wrap {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  background: #191b1c;
  width: 260px;
  height: 325px;
}
.newArrials_list {
  display: flex;
  background: url("../assets/img/block_newArrials/62050 1.png") center;
  background-size: cover;
  width: 215px;
  height: 214px;
}

.newArrials_text {
  width: 10rem;
  height: 2rem;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 24px;
  color: #ffffff;
}

.newArrials_prise {
  width: 10rem;
  height: 2rem;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 21px;
  color: #d0d0d0;
}
</style>
