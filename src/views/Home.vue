<template>
  <b-container fluid>
    <b-row id="line" class="h-25 flex-column align-items-center">
      <b-col id="n1"> oi</b-col>
      <b-col id="n2">
        <img src="../assets/logo.png" alt="">
      </b-col>
      <b-col id="n1">oi</b-col>
    </b-row>
    <b-row id="line2" class="h-50 align-items-center">
      <b-col>
        <img src="../assets/logo.png" alt="">
      </b-col>
    </b-row>
    <b-row id="line3" class="h-25 align-items-center">
      <b-col>
        <img src="../assets/logo.png" alt="">
      </b-col>
    </b-row>
  </b-container>
</template>

<script>

export default {
  name: "Home",
};
</script>

<style scoped>
html, body {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
}
#line{
  position: absolute;
}
#line2 {
  position: absolute;
  top: 25%;
}
#line3 {
  position: absolute;
  top: 75%;
}
#n1{
  height: 20%;
  position: relative;
}
#n2{
  height: 60%;
  position: relative;
}
img{
  height: 100%;
  width: 100%;
  object-fit: contain;
}
.rectangle {
  width: 60%;
  height: 110px;
  z-index: 2;
  flex: wrap;

  background: rgba(45, 156, 219, 0.5);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;

  font-size: 28px;
  font: Gorditas;
  line-height: 24px;
  letter-spacing: 2%;
  object-fit: cover;
}
#tempo,
#velocidade,
#distancia {
  color: white;
  object-fit: cover;
}
.rectangleRigth {
  z-index: 2;
  width: 20%;
  left: 0%;

  background: rgba(45, 156, 219, 0.5);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;

  font-size: 28px;
  font: Gorditas;
  line-height: 24px;
  letter-spacing: 2%;
  color: #f4f6fb;
  object-fit: cover;
}

.mediapipe {
  background-color: rgba(45, 156, 219, 0.5);
  height: 140px;
  width: 250px;
  z-index: 2;
  object-fit: cover;
}

.input_video,
.output_canvas {
  height: 140px;
  width: 250px;
  object-fit: cover;
}

#progress {
  height: 50%;
  width: 100%;
  object-fit: cover;
}
/* cor de background da barra */
#progress::-webkit-progress-bar {
  background-color: #fff;
}
/* cor de background do valor de progresso */
#progress::-webkit-progress-value {
  background: rgba(45, 156, 219, 0.5);
}
#progress::-moz-progress-bar {
  background: rgba(45, 156, 219, 0.5);
}
</style>
