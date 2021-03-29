<template>
  <div class="lookCollection">
    <div class="container">
      <div class="lookCollection_img"></div>

      <div class="lookCollection_content">
        <h1 class="lookCollection_text">коллекция 2018</h1>
        <div class="line_white">
          <div class="line"></div>
        </div>

        <div class="lookcollection_wrapper">
          <p class="lookCollection_list">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non rutrum
            ornare ut mattis habitant dui arcu. Sagittis amet nunc ut neque quis
            nibh arcu. Vivamus vestibulum nisi et venenatis sed scelerisque
            magna consectetur. Amet convallis quis gravida facilisis vulputate.
            Faucibus facilisi habitasse ipsum interdum dictum aliquet. Velit
            quis ullamcorper pulvinar nulla malesuada integer. Aenean praesent
            viverra nulla nullam natoque volutpat curabitur auctor. Viverra
            viverra ullamcorper scelerisque risus dignissim egestas. Id aliquam
            a aliquam egestas leo orci pharetra sed diam.
          </p>
        </div>

        <div class="lookCollection_footer">
          <div class="lookCollection_wrap">
            <span class="lookCollection_footer_text">посмотреть коллекцию</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "lookCollection",
};
</script>

<style lang="scss" scoped>
.lookCollection {
  width: 100%;
  height: 600px;
}
.container {
  display: flex;
}
.lookCollection_img {
  width: 40%;
  height: 600px;
  background: url("../assets/img/block_lookCollection/Rectangle 9.png") center;
  background-size: cover;
}

.lookCollection_content {
  width: 60%;
  height: 600px;
  text-align: center;
  background: #000;
}

.lookCollection_text {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 12rem;
  padding-top: 4rem;
  font-family: " Playfair Display";
  font-style: normal;
  font-weight: normal;
  font-size: 36px;
  line-height: 48px;
  text-align: center;
  text-transform: uppercase;
  color: #ffffff;
}
.line_white {
  display: flex;
  justify-content: center;
  height: 3rem;
}
.line {
  width: 7rem;
  background: #fff;
  height: 1px;
}
.lookcollection_wrapper {
  display: flex;
  width: 100%;
  justify-content: center;
}
.lookCollection_list {
  display: flex;
  width: 471px;
  height: 173px;
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 150%;
  text-align: center;
  color: #ffffff;
}
.lookCollection_footer {
  display: flex;
  height: 10rem;
}
.lookCollection_wrap {
  display: flex;
  justify-content: center;
  align-items: center;
}
.lookCollection_footer_text {
  display: flex;
  width: 331px;
  height: 47px;
  border: 2px solid #fff;
  color: #fff;
  justify-content: center;
  align-items: center;
  font-family: "PT Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 23px;
  text-align: center;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
</style>
