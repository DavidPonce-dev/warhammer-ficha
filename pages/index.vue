<template>
  <div class="ficha">
    <div class="papel">
      <div class="titulo">Personaje</div>
      <input type="text" placeholder="nombre">
      <input type="text" placeholder="raza">
      <input type="text" placeholder="profesion actual">
      <input type="text" placeholder="profesion anterior">
    </div>
    <div class="papel">
      <div class="titulo">Detalles personales</div>
      <input class="medio" type="text" placeholder="edad">
      <input class="medio" type="text" placeholder="sexo">
      <input class="medio" type="text" placeholder="color de ojos">
      <input class="medio" type="text" placeholder="peso">
      <input class="medio" type="text" placeholder="color de pelo">
      <input class="medio" type="text" placeholder="altura">
      <input class="medio" type="text" placeholder="signo astral">
      <input class="medio" type="text" placeholder="n° hermanos">
      <input type="text" placeholder="lugar de nacimiento">
      <input type="text" placeholder="marcas distintivas">
    </div>
    <div class="papel">
      <div class="titulo">Perfil del personaje</div>
      <table>
        <thead>
          <td>Principales</td>
          <td>HP</td>
          <td>F</td>
          <td>R</td>
          <td>Ag</td>
          <td>Int</td>
          <td>V</td>
          <td>Em</td>
        </thead>
        <tbody>
          <td>Iniciales</td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
        </tbody>
        <tbody>
          <td>Mejora</td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
        </tbody>
        <tbody>
          <td>Actuales</td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
        </tbody>
        <thead>
          <td>Secundarias</td>
          <td>A</td>
          <td>H</td>
          <td>BF</td>
          <td>BR</td>
          <td>M</td>
          <td>Mag</td>
          <td>PL</td>
          <td>PD</td>
        </thead>
        <tbody>
          <td>Iniciales</td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
        </tbody>
        <tbody>
          <td>Mejora</td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
        </tbody>
        <tbody>
          <td>Actuales</td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
          <td><input class="stat" type="text"></td>
        </tbody>
      </table>
    </div>
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
