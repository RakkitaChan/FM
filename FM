<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Radio FM</title>
<style>
body {
  margin:0;
  background:#121212;
  display:flex;
  justify-content:center;
  align-items:center;
  height:100vh;
  font-family:Arial;
}
.player {
  background:#1e1e1e;
  padding:20px;
  border-radius:20px;
  text-align:center;
  color:white;
}
button {
  background:#1db954;
  border:none;
  color:white;
  padding:10px 20px;
  border-radius:30px;
  cursor:pointer;
}
</style>
</head>
<body>

<div class="player">
  <h3>📻 FM Radio</h3>
  <audio id="radio"></audio>
  <br><br>
  <button onclick="playRadio()">▶ Play</button>
</div>

<script>
const radio = document.getElementById("radio");

function playRadio() {
  radio.src = "http://cinema.acs.its.nyu.edu:8000/wnyu128.mp3";
  radio.play();
}
</script>

</body>
</html>
