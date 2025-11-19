<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Portal Gamer Definitivo</title>
<style>
body {font-family: Arial, sans-serif; background:#0a0a0a; color:white; margin:0;}
header {background:#0d47a1; padding:25px; text-align:center; font-size:36px; font-weight:bold; color:white;}
nav {background:#111; padding:15px; display:flex; flex-wrap:wrap; justify-content:center; gap:15px;}
nav a {color:#64b5f6; text-decoration:none; font-size:20px; padding:6px 12px; border-radius:6px;}
nav a:hover {background:#1e88e5;}
section {padding:30px;}
h2 {color:#42a5f5; font-size:28px;}
.card {background:#1b1b1b; padding:20px; border-radius:12px; margin:15px 0; display:flex; align-items:center; gap:20px;}
.card img {width:140px; border-radius:10px;}
.ranking {color:#ffca28; font-weight:bold; font-size:20px;}
.form-box {background:#222; padding:25px; border-radius:12px; max-width:500px;}
input, select {padding:12px; width:100%; margin:10px 0; border-radius:8px; border:none;}
button {padding:12px 20px; background:#42a5f5; border:none; border-radius:8px; color:black; font-weight:bold; cursor:pointer; width:100%; font-size:18px;}
button:hover {background:#64b5f6;}
#resultado {margin-top:20px; font-size:20px; color:#ffca28;}
</style>
</head>
<body>
<header>PORTAL GAMER – Sitio Completo Mejorado</header>

<nav>
<a href="#terror">Terror</a>
<a href="#suspenso">Suspenso</a>
<a href="#aventura">Aventura</a>
<a href="#scifi">Ciencia Ficción</a>
<a href="#familia">Familia</a>
<a href="#clasicos">Clásicos</a>
<a href="#mundo_abierto">Mundo Abierto</a>
<a href="#reco">Recomendaciones</a>
</nav>

<section id="terror">
<h2>🎃 Terror</h2>
<div class="card"><img src="https://i.imgur.com/Y8QqQ3S.jpeg"><div><span class="ranking">1. Resident Evil Village</span><br>Horror de supervivencia con ambientación increíble.</div></div>
<div class="card"><img src="https://i.imgur.com/WU0U54w.jpeg"><div><span class="ranking">2. Outlast</span><br>Terror psicológico extremo y persecuciones intensas.</div></div>
<div class="card"><img src="https://i.imgur.com/HMZ0KqN.jpeg"><div><span class="ranking">3. Silent Hill 2</span><br>El clásico más influyente del survival horror.</div></div>
</section>

<section id="suspenso">
<h2>🕵️ Suspenso</h2>
<div class="card"><img src="https://i.imgur.com/5KnYk4H.jpeg"><div><span class="ranking">1. Alan Wake 2</span> – Historia profunda y atmósfera inquietante.</div></div>
<div class="card"><img src="https://i.imgur.com/2r0OSly.jpeg"><div><span class="ranking">2. Control</span> – Misterio y acción con elementos paranormales.</div></div>
<div class="card"><img src="https://i.imgur.com/xl7XK7Q.jpeg"><div><span class="ranking">3. Inside</span> – Suspenso silencioso y minimalista.</div></div>
</section>

<section id="aventura">
<h2>🗺️ Aventura</h2>
<div class="card"><img src="https://i.imgur.com/4fjIEVv.jpeg"><div><span class="ranking">1. Zelda: Breath of the Wild</span></div></div>
<div class="card"><img src="https://i.imgur.com/BcGfa0e.jpeg"><div><span class="ranking">2. Uncharted 4</span></div></div>
<div class="card"><img src="https://i.imgur.com/0hB13dq.jpeg"><div><span class="ranking">3. Ori and the Blind Forest</span></div></div>
</section>

<section id="scifi">
<h2>🚀 Ciencia Ficción</h2>
<div class="card"><img src="https://i.imgur.com/xAuT9Tq.jpeg"><div><span class="ranking">1. Cyberpunk 2077</span></div></div>
<div class="card"><img src="https://i.imgur.com/dvZu0Ls.jpeg"><div><span class="ranking">2. Mass Effect Trilogy</span></div></div>
<div class="card"><img src="https://i.imgur.com/VmOv4fG.jpeg"><div><span class="ranking">3. Titanfall 2</span></div></div>
</section>

<section id="familia">
<h2>👨‍👩‍👧 Para la Familia</h2>
<div class="card"><img src="https://i.imgur.com/hQ8rFrp.jpeg"><div><span class="ranking">1. Mario Kart 8 Deluxe</span></div></div>
<div class="card"><img src="https://i.imgur.com/IWDKd4H.jpeg"><div><span class="ranking">2. Minecraft</span></div></div>
<div class="card"><img src="https://i.imgur.com/2HefbQ2.jpeg"><div><span class="ranking">3. Fall Guys</span></div></div>
</section>

<section id="clasicos">
<h2>🏆 Clásicos</h2>
<div class="card"><img src="https://i.imgur.com/2Cx5rs4.jpeg"><div><span class="ranking">1. Super Mario World</span></div></div>
<div class="card"><img src="https://i.imgur.com/YpKjM1K.jpeg"><div><span class="ranking">2. The Legend of Zelda: Ocarina of Time</span></div></div>
<div class="card"><img src="https://i.imgur.com/HYxkB9N.jpeg"><div><span class="ranking">3. Pac-Man</span></div></div>
</section>

<section id="mundo_abierto">
<h2>🌍 Mundo Abierto</h2>
<div class="card"><img src="https://i.imgur.com/fm8E6Fs.jpeg"><div><span class="ranking">1. Red Dead Redemption 2</span></div></div>
<div class="card"><img src="https://i.imgur.com/9rW8Gkp.jpeg"><div><span class="ranking">2. GTA V</span></div></div>
<div class="card"><img src="https://i.imgur.com/ZV9T0wI.jpeg"><div><span class="ranking">3. Elden Ring</span></div></div>
</section>

<section id="reco">
<h2>✨ Recomendador Inteligente</h2>
<div class="form-box">
<form>
<label>¿Qué género te gusta?</label>
<select id="genero">
<option value="terror">Terror</option>
<option value="suspenso">Suspenso</option>
<option value="aventura">Aventura</option>
<option value="scifi">Ciencia Ficción</option>
<option value="familia">Familia</option>
</select>

<label>¿Prefieres juegos largos o cortos?</label>
<select id="tiempo">
<option value="largos">Largos</option>
<option value="cortos">Cortos</option>
</select>

<label>¿Quieres historia profunda?</label>
<select id="historia">
<option value="si">Sí</option>
<option value="no">No</option>
</select>

<button type="button" onclick="recomendar()">Obtener recomendación</button>
</form>
<p id="resultado"></p>
</div>
</section>

<script>
function recomendar() {
    const genero = document.getElementById("genero").value;
    const tiempo = document.getElementById("tiempo").value;
    const historia = document.getElementById("historia").value;
    let r = "";

    if (genero === "terror") r = historia === "si" ? "Silent Hill 2" : "Outlast";
    if (genero === "suspenso") r = "Alan Wake 2";
    if (genero === "aventura") r = tiempo === "largos" ? "Breath of the Wild" : "Ori";
    if (genero === "scifi") r = historia === "si" ? "Mass Effect" : "Titanfall 2";
    if (genero === "familia") r = "Mario Kart 8";

    document.getElementById("resultado").innerHTML = "Tu recomendación es: <b>" + r + "</b>";
}
</script>

</body>
</html>
