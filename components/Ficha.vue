<template>
  <header>
    <div class="left">
      <Personaje />
      <DetallesPersonales />
    </div>
    <div class="right">
      <Perfil />
      <Jugador />
    </div>
    <Armas />
  </header>
</template>

<script>
export default {
  name: "FichaWarhammer",
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
header {
  position: relative;
  width: 922px;
  height: 700px;
  margin: 50px auto;
  background: url(http://api.thumbr.it/whitenoise-80x80.png?background=f7f1acff&noise=ffc800&density=92&opacity=78);
  border: solid 1px black;
}
input {
  border: unset;
  padding: 6px;
  width: 98%;
}
thead {
  text-align: center;
}
.left{
  width: 50%;
}
.right{
    width: 50%;
    position: absolute;
    right: 0;
}
.titulo {
  text-align: center;
  font-size: 25px;
  color: #fff;
  background: #000;
}
.papel {
  float: left;
  width: 440px;
  margin: 10px;
  background-color: #fff;
  border: 4px double #000;
}
</style>
