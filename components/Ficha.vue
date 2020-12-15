<template>
  <div class="ficha">
    <Personaje />
    <DetallesPersonales />
    <Perfil />
  </div>
</template>

<script>
export default {
  name: 'FichaWarhammer'
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.ficha {
  background: url(http://api.thumbr.it/whitenoise-80x80.png?background=f7f1acff&noise=ffc800&density=92&opacity=78);
  border: solid 1px black;
  position: absolute;
  width: 100%;
  height: 100%;
}
.titulo {
    text-align: center;
    font-size: 25px;
    color: #fff;
    background: #000;
}
.papel {
  float:left;
  width: 440px;
  margin: 10px;
  background-color: #fff;
  border: 4px double #000;
}
.papel input {
  margin: 1px;
  border: unset;
  padding: 10px;
  font-size: 15px;
  width: 430px;
}
.papel .medio {
  width: 212px;
}
thead {
  text-align: center;
}
.stat{
  width: 40px !important;
  border: solid 1px black !important;
}
</style>
