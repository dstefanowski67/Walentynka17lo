<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<title>Walentynka 💖</title>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<style>
* { box-sizing: border-box; }

body {
    margin: 0;
    height: 100vh;
    font-family: 'Pacifico', cursive;
    background-color: #fff0f5;
    background-image:
        radial-gradient(#ffb6c1 2px, transparent 2px),
        radial-gradient(#ff69b4 2px, transparent 2px);
    background-size: 40px 40px;
    background-position: 0 0, 20px 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

.container {
    background: white;
    padding: 40px 30px;
    border-radius: 35px;
    text-align: center;
    box-shadow: 0 0 50px rgba(255,105,180,0.45);
    max-width: 95%;
}

h1 {
    color: #ff1493;
    font-size: 42px;
    margin-bottom: 25px;
}

.countdown {
    font-size: 28px;
    color: #ff69b4;
    margin-bottom: 40px;
}

.buttons {
    position: relative;
    height: 140px;
}

button {
    font-family: 'Pacifico', cursive;
    font-size: 30px;
    padding: 20px 60px;
    border-radius: 50px;
    border: none;
    cursor: pointer;
    position: absolute;
    transition: transform 0.2s;
}

.yes {
    background-color: #ff69b4;
    color: white;
    left: 50%;
    transform: translateX(-50%);
}

.no {
    background-color: #f0f0f0;
    color: #999;
    top: 80px;
}

.message {
    margin-top: 40px;
    font-size: 28px;
    color: #ff1493;
    display: none;
    line-height: 1.4;
    font-weight: bold;
}

.heart {
    position: absolute;
    animation: floatUp 4s linear forwards;
}

@keyframes floatUp {
    0% { opacity: 1; transform: translateY(0); }
    100% { opacity: 0; transform: translateY(-800px); }
}

@media (max-width: 600px) {
    h1 { font-size: 34px; }
    .countdown { font-size: 24px; }
    button { font-size: 24px; padding: 16px 45px; }
    .message { font-size: 22px; }
}
</style>
</head>
<body>

<div class="container">
    <h1>Natalia, czy zostaniesz moją walentynką? 💕</h1>

    <div class="countdown" id="countdown"></div>

    <div class="buttons">
        <button class="yes" onclick="yesClicked()">TAK</button>
        <button class="no" id="noBtn">NIE</button>
    </div>

    <div class="message" id="message">
        🎉 GRATULACJE, WYGRAŁAŚ WALENTYNKOWĄ RANDKĘ NIESPODZIANKĘ! 💝
    </div>
</div>

<script>
// SERDUSZKA PO TAK
function yesClicked() {
    document.getElementById("message").style.display = "block";
    for (let i = 0; i < 60; i++) createHeart();
}

function createHeart() {
    const heart = document.createElement("div");
    heart.className = "heart";
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * window.innerWidth + "px";
    heart.style.bottom = "0";
    heart.style.fontSize = (24 + Math.random() * 36) + "px";
    document.body.appendChild(heart);
    setTimeout(() => heart.remove(), 4000);
}

// BARDZO UCIEKAJĄCY PRZYCISK NIE
const noBtn = document.getElementById("noBtn");
noBtn.addEventListener("mouseover", () => {
    const maxX = window.innerWidth - noBtn.offsetWidth;
    const maxY = window.innerHeight - noBtn.offsetHeight;
    const x = Math.random() * maxX;
    const y = Math.random() * maxY;
    noBtn.style.left = x + "px";
    noBtn.style.top = y + "px";
});

// LICZNIK DO WALENTYNEK
const countdownEl = document.getElementById("countdown");
const valentines = new Date(new Date().getFullYear(), 1, 14);

setInterval(() => {
    const now = new Date();
    let diff = valentines - now;

    if (diff < 0) {
        valentines.setFullYear(valentines.getFullYear() + 1);
        diff = valentines - now;
    }

    const d = Math.floor(diff / (1000*60*60*24));
    const h = Math.floor((diff / (1000*60*60)) % 24);
    const m = Math.floor((diff / (1000*60)) % 60);
    const s = Math.floor((diff / 1000) % 60);

    countdownEl.innerHTML =
        `⏳ Do Walentynek zostało: <br><strong>${d} dni ${h}h ${m}m ${s}s</strong> 💘`;
}, 1000);
</script>

</body>
</html>
