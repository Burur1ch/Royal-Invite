<template>
  <div class="dresscode">
    <div class="container">
      <div class="dresscode__rapper">
        <div>
          <h3 class="dresscode__title">Dress-code</h3>
        </div>
        <div>
          <p class="dresscode__text">
            Нам будет особенно приятно видеть вас в нарядах цветовой гаммы&nbsp;
            нашей свадьбы:
          </p>
        </div>
        <div>
          <div class="dresscode__wrapper">
            <div class="dresscode__color dresscode__color-one"></div>
            <div class="dresscode__color dresscode__color-two"></div>
            <div class="dresscode__color dresscode__color-three"></div>
            <div class="dresscode__color dresscode__color-four"></div>
            <div class="dresscode__color dresscode__color-five"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.dresscode {
  margin: 0 auto 150px;
}
@media (min-width: 320px) and (max-width: 767px) {
  .dresscode {
    margin-bottom: 250px;
  }
}
.dresscode .container {
  margin: 0 auto;
  max-width: 1280px;
  padding: 0 40px;
  position: relative;
}
@media (min-width: 768px) and (max-width: 1024px) {
  .dresscode .container {
    padding: 0 60px;
  }
}
@media (min-width: 435px) and (max-width: 770px) {
  .dresscode .container {
    padding: 0;
  }
}
@media (min-width: 320px) and (max-width: 434px) {
  .dresscode .container {
    padding: 0;
  }
}
.dresscode__rapper {
  margin: 0 auto;
  max-width: 800px;
  width: 100%;
}
@media (min-width: 768px) and (max-width: 1024px) {
  .dresscode__rapper {
    max-width: 730px;
  }
}
.dresscode__title {
  border-bottom: 1px solid #665f55;
  color: #665f55;
  font-family: KyivType Sans;
  font-size: 46px;
  font-weight: 200;
  line-height: 56px;
  margin: 0 auto 65px;
  max-width: 300px;
  position: relative;
  text-align: center;
  width: 100%;
}
@media (min-width: 320px) and (max-width: 767px) {
  .dresscode__title {
    font-size: 36px;
    line-height: 44px;
    margin-bottom: 50px;
    max-width: 250px;
  }
}
.dresscode__text {
  color: #665f55;
  font-family: Open Sans, serif;
  font-size: 16px;
  font-weight: 300;
  line-height: 22px;
  margin: 0 auto 20px;
  padding: 0 40px;
  text-align: center;
}
@media (min-width: 769px) and (max-width: 1024px) {
  .dresscode__text {
    max-width: 730px;
    padding: 0 60px;
  }
}
@media (min-width: 435px) and (max-width: 770px) {
  .dresscode__text {
    font-size: 14px;
    line-height: 20px;
    max-width: 600px;
    padding: 0 35px;
    width: 100%;
  }
}
@media (min-width: 320px) and (max-width: 434px) {
  .dresscode__text {
    font-size: 14px;
    line-height: 20px;
    max-width: 320px;
    padding: 0 20px;
    width: 100%;
  }
}
.dresscode__text-people {
  font-size: 22px;
  line-height: 26px;
  margin-bottom: 30px;
}
@media (min-width: 768px) {
  .dresscode__text-people {
    font-size: 24px;
    line-height: 28px;
  }
}
.dresscode__wrap {
  margin: 0 auto 20px;
}
.dresscode__jpg {
  height: 100%;
  object-fit: cover;
  width: 100%;
}
.dresscode__wrapper {
  align-items: center;
  display: flex;
  justify-content: center;
  margin: 0 auto 100px;
  max-width: 600px;
  position: relative;
  width: 100%;
}
@media (min-width: 768px) and (max-width: 1023px) {
  .dresscode__wrapper {
    max-width: 500px;
  }
}
@media (min-width: 550px) and (max-width: 767px) {
  .dresscode__wrapper {
    max-width: 400px;
  }
}
@media (min-width: 320px) and (max-width: 549px) {
  .dresscode__wrapper {
    margin-bottom: 70px;
    max-width: 275px;
  }
}
.dresscode__color {
  height: 120px;
  width: 120px;
  border-radius: 100px;
}
@media (min-width: 768px) and (max-width: 1023px) {
  .dresscode__color {
    height: 100px;
    width: 100px;
  }
}
@media (min-width: 550px) and (max-width: 767px) {
  .dresscode__color {
    height: 80px;
    width: 80px;
  }
}
@media (min-width: 320px) and (max-width: 549px) {
  .dresscode__color {
    height: 55px;
    width: 55px;
  }
}
.dresscode__color-one {
  background-color: #ece5d3;
}
.dresscode__color-two {
  background-color: #e4d9c3;
}
.dresscode__color-three {
  background-color: #dcc2a9;
  top: 0;
}
.dresscode__color-four {
  background-color: #ab8b74;
}
.dresscode__color-five {
  background-color: #a58e7e;
}
</style>