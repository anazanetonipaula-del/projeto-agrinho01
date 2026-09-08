<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agrinho Paraná - Colheita</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background: #87ceeb;
    overflow: hidden;
}

/* TELA DO JOGO */
#game {
    width: 100vw;
    height: 100vh;
    position: relative;
    overflow: hidden;
}

/* CÉU */
.sky {
    position: absolute;
    width: 100%;
    height: 38%;
    background: linear-gradient(#58b9ed, #bdeaff);
}

/* SOL */
.sun {
    position: absolute;
    width: 80px;
    height: 80px;
    background: #ffd83d;
    border-radius: 50%;
    top: 35px;
    right: 70px;
    box-shadow: 0 0 30px #fff27a;
}

/* NUVENS */
.cloud {
    position: absolute;
    background: white;
    width: 100px;
    height: 35px;
    border-radius: 30px;
    opacity: 0.9;
}

.cloud::before,
.cloud::after {
    content: "";
    position: absolute;
    background: white;
    border-radius: 50%;
}

.cloud::before {
    width: 50px;
    height: 50px;
    top: -25px;
    left: 20px;
}

.cloud::after {
    width: 40px;
    height: 40px;
    top: -18px;
    right: 15px;
}

.cloud1 {
    top: 70px;
    left: 10%;
}

.cloud2 {
    top: 130px;
    left: 55%;
}

/* TERRENO */
.field {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 64%;
    background: #8b5a2b;
}

/* LINHAS DA PLANTAÇÃO */
.row {
    position: absolute;
    width: 100%;
    height: 70px;
    border-top: 5px dashed rgba(60, 35, 10, 0.5);
}

/* MILHO */
.corn {
    position: absolute;
    width: 25px;
    height: 55px;
}

.corn::before {
    content: "🌽";
    font-size: 38px;
}

/* SOJA */
.soy {
    position: absolute;
    width: 30px;
    height: 30px;
}

.soy::before {
    content: "🌱";
    font-size: 32px;
}

/* TRATOR */
#tractor {
    position: absolute;
    width: 120px;
    height: 75px;
    left: 50%;
    bottom: 90px;
    transform: translateX(-50%);
    z-index: 10;
    transition: left 0.08s, bottom 0.08s;
}

/* Corpo */
.body {
    position: absolute;
    width: 75px;
    height: 42px;
    background: #e63920;
    bottom: 18px;
    left: 25px;
    border-radius: 8px;
    border: 3px solid #a51e0e;
}

/* Cabine */
.cabin {
    position: absolute;
    width: 42px;
    height: 40px;
    background: #e63920;
    bottom: 45px;
    left: 43px;
    border-radius: 5px;
    border: 3px solid #a51e0e;
}

/* Janela */
.window {
    position: absolute;
    width: 27px;
    height: 22px;
    background: #9ee7ff;
    top: 5px;
    left: 5px;
    border: 2px solid #333;
}

/* Rodas */
.wheel {
    position: absolute;
    border-radius: 50%;
    background: #222;
    border: 5px solid #111;
}

.wheel.big {
    width: 40px;
    height: 40px;
    bottom: 0;
    left: 30px;
}

.wheel.small {
    width: 27px;
    height: 27px;
    bottom: 5px;
    left: 85px;
}

/* HUD */
#hud {
    position: absolute;
    top: 15px;
    left: 15px;
    z-index: 20;
    background: rgba(0,0,0,0.7);
    color: white;
    padding: 15px;
    border-radius: 12px;
    font-size: 18px;
}

#hud span {
    color: #ffe14a;
    font-weight: bold;
}

/* INSTRUÇÕES */
#instructions {
    position: absolute;
    bottom: 15px;
    left: 50%;
    transform: translateX(-50%);
    background: rgba(0,0,0,0.75);
    color: white;
    padding: 10px 20px;
    border-radius: 15px;
    z-index: 30;
    text-align: center;
}

/* BOTÃO */
#startScreen {
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.75);
    z-index: 100;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    color: white;
}

#startScreen h1 {
    font-size: 45px;
    margin-bottom: 15px;
}

#startScreen p {
    font-size: 20px;
    margin-bottom: 25px;
}

button {
    background: #39a852;
    color: white;
    border: none;
    padding: 15px 35px;
    border-radius: 10px;
    font-size: 20px;
    cursor: pointer;
}

button:hover {
    background: #2c873f;
}

/* CONTROLES MOBILE */
.controls {
    position: absolute;
    bottom: 70px;
    right: 20px;
    z-index: 40;
    display: flex;
    gap: 10px;
}

.controls button {
    width: 65px;
    height: 55px;
    padding: 0;
    font-size: 25px;
}
</style>
</head>

<body>

<div id="game">

    <div class="sky"></div>

    <div class="sun"></div>

    <div class="cloud cloud1"></div>
    <div class="cloud cloud2"></div>

    <div class="field">

        <div class="row" style="top: 30px;"></div>
        <div class="row" style="top: 130px;"></div>
        <div class="row" style="top: 230px;"></div>
        <div class="row" style="top: 330px;"></div>
        <div class="row" style="top: 430px;"></div>

        <!-- PLANTAÇÕES -->
        <div id="plants"></div>

    </div>

    <!-- TRATOR -->
    <div id="tractor">

        <div class="body"></div>

        <div class="cabin">
            <div class="window"></div>
        </div>

        <div class="wheel big"></div>
        <div class="wheel small"></div>

    </div>

    <!-- HUD -->
    <div id="hud">
        🌾 Colheita<br>
        🌽 Milho: <span id="cornScore">0</span><br>
        🌱 Soja: <span id="soyScore">0</span><br>
        🏆 Pontos: <span id="points">0</span>
    </div>

    <!-- INSTRUÇÕES -->
    <div id="instructions">
        ⬅️ ➡️ ⬆️ ⬇️ Use as setas para dirigir o trator
    </div>

    <!-- CONTROLES -->
    <div class="controls">
        <button onclick="moveLeft()">⬅️</button>
        <button onclick="moveUp()">⬆️</button>
        <button onclick="moveDown()">⬇️</button>
        <button onclick="moveRight()">➡️</button>
    </div>

    <!-- TELA INICIAL -->
    <div id="startScreen">
        <h1>🚜 Agro Colheita</h1>
        <p>Ajude o agricultor a colher milho e soja!</p>
        <button onclick="startGame()">COMEÇAR</button>
    </div>

</div>

<script>

const tractor = document.getElementById("tractor");
const plantsContainer = document.getElementById("plants");

let tractorX = window.innerWidth / 2 - 60;
let tractorY = window.innerHeight - 170;

let cornScore = 0;
let soyScore = 0;
let points = 0;

const speed = 15;

/* CRIAR PLANTAÇÕES */

function createPlants() {

    plantsContainer.innerHTML = "";

    for (let i = 0; i < 25; i++) {

        const plant = document.createElement("div");

        const isCorn = Math.random() > 0.5;

        plant.className = isCorn ? "corn" : "soy";

        plant.dataset.type = isCorn ? "corn" : "soy";

        plant.style.left = Math.random() * (window.innerWidth - 50) + "px";

        plant.style.top =
            (Math.random() * (window.innerHeight * 0.55)) + "px";

        plantsContainer.appendChild(plant);
    }
}

/* INICIAR */

function startGame() {

    document.getElementById("startScreen").style.display = "none";

    createPlants();

    updateTractor();

}

/* MOVIMENTAÇÃO */

function moveLeft() {

    tractorX -= speed;

    if (tractorX < 0)
        tractorX = 0;

    updateTractor();

}

function moveRight() {

    tractorX += speed;

    if (tractorX > window.innerWidth - 120)
        tractorX = window.innerWidth - 120;

    updateTractor();

}

function moveUp() {

    tractorY -= speed;

    if (tractorY < window.innerHeight * 0.35)
        tractorY = window.innerHeight * 0.35;

    updateTractor();

}

function moveDown() {

    tractorY += speed;

    if (tractorY > window.innerHeight - 150)
        tractorY = window.innerHeight - 150;

    updateTractor();

}

/* ATUALIZAR POSIÇÃO */

function updateTractor() {

    tractor.style.left = tractorX + "px";
    tractor.style.bottom =
        (window.innerHeight - tractorY - 75) + "px";

    checkHarvest();

}

/* COLHEITA */

function checkHarvest() {

    const tractorRect = tractor.getBoundingClientRect();

    const plants = document.querySelectorAll(".corn, .soy");

    plants.forEach(plant => {

        const plantRect = plant.getBoundingClientRect();

        if (

            tractorRect.left < plantRect.right &&
            tractorRect.right > plantRect.left &&
            tractorRect.top < plantRect.bottom &&
            tractorRect.bottom > plantRect.top

        ) {

            if (plant.dataset.type === "corn") {

                cornScore++;
                points += 10;

            } else {

                soyScore++;
                points += 15;

            }

            plant.remove();

            updateScore();

        }

    });

}

/* ATUALIZAR PONTUAÇÃO */

function updateScore() {

    document.getElementById("cornScore").textContent = cornScore;

    document.getElementById("soyScore").textContent = soyScore;

    document.getElementById("points").textContent = points;

}

/* TECLADO */

document.addEventListener("keydown", function(event) {

    if (event.key === "ArrowLeft")
        moveLeft();

    if (event.key === "ArrowRight")
        moveRight();

    if (event.key === "ArrowUp")
        moveUp();

    if (event.key === "ArrowDown")
        moveDown();

});

/* NOVAS PLANTAÇÕES */

setInterval(function() {

    if (document.getElementById("startScreen").style.display === "none") {

        if (document.querySelectorAll(".corn, .soy").length < 10) {

            createPlants();

        }

    }

}, 5000);

</script>

</body>
</html>
