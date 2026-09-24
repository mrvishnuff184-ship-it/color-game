<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Color Prediction Game</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f172a;
      color: white;
      min-height: 100vh;
    }

    .header {
      background: #1e293b;
      padding: 18px;
      text-align: center;
      font-size: 24px;
      font-weight: bold;
    }

    .container {
      max-width: 500px;
      margin: auto;
      padding: 20px;
    }

    .card {
      background: #1e293b;
      border-radius: 18px;
      padding: 20px;
      margin-bottom: 18px;
      box-shadow: 0 8px 25px rgba(0,0,0,.25);
    }

    .points {
      text-align: center;
      font-size: 22px;
      margin-bottom: 15px;
    }

    .timer {
      text-align: center;
      font-size: 42px;
      font-weight: bold;
      margin: 15px 0;
    }

    .round {
      text-align: center;
      color: #94a3b8;
    }

    .buttons {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
      margin-top: 20px;
    }

    button {
      border: none;
      padding: 16px 8px;
      border-radius: 12px;
      color: white;
      font-size: 17px;
      font-weight: bold;
      cursor: pointer;
    }

    button:disabled {
      opacity: .45;
      cursor: not-allowed;
    }

    .red {
      background: #ef4444;
    }

    .green {
      background: #22c55e;
    }

    .violet {
      background: #8b5cf6;
    }

    .result {
      text-align: center;
      font-size: 21px;
      min-height: 30px;
      margin-top: 20px;
    }

    .history {
      list-style: none;
    }

    .history li {
      display: flex;
      justify-content: space-between;
      padding: 12px;
      margin: 7px 0;
      background: #334155;
      border-radius: 10px;
    }

    .dot {
      display: inline-block;
      width: 14px;
      height: 14px;
      border-radius: 50%;
      margin-right: 7px;
    }

    .red-dot {
      background: #ef4444;
    }

    .green-dot {
      background: #22c55e;
    }

    .violet-dot {
      background: #8b5cf6;
    }

    .note {
      text-align: center;
      color: #94a3b8;
      font-size: 13px;
      margin-top: 20px;
      line-height: 1.5;
    }
  </style>
</head>

<body>

  <div class="header">
    🎮 Color Prediction Game
  </div>

  <div class="container">

    <div class="card">
      <div class="points">
        ⭐ Virtual Points: <span id="points">1000</span>
      </div>

      <div class="round">
        Round #<span id="round">1</span>
      </div>

      <div class="timer" id="timer">10</div>

      <div class="buttons">
        <button class="red" onclick="predict('Red')" id="redBtn">
          🔴 Red
        </button>

        <button class="green" onclick="predict('Green')" id="greenBtn">
          🟢 Green
        </button>

        <button class="violet" onclick="predict('Violet')" id="violetBtn">
          🟣 Violet
        </button>
      </div>

      <div class="result" id="result">
        अपना रंग चुनें
      </div>
    </div>

    <div class="card">
      <h2 style="margin-bottom:15px;">📜 History</h2>

      <ul class="history" id="history">
        <li>अभी कोई result नहीं है</li>
      </ul>
    </div>

    <div class="note">
      यह demo game केवल entertainment के लिए है।
      इसमें real money, betting, deposit या withdrawal नहीं है।
    </div>

  </div>

<script>

  let points = 1000;
  let round = 1;
  let time = 10;
  let selected = null;

  const pointsEl = document.getElementById("points");
  const roundEl = document.getElementById("round");
  const timerEl = document.getElementById("timer");
  const resultEl = document.getElementById("result");
  const historyEl = document.getElementById("history");

  const buttons = [
    document.getElementById("redBtn"),
    document.getElementById("greenBtn"),
    document.getElementById("violetBtn")
  ];

  function predict(color) {

    if (selected !== null) return;

    selected = color;

    resultEl.innerHTML =
      "आपने चुना: <b>" + color + "</b>";

    buttons.forEach(btn => {
      btn.disabled = true;
    });
  }

  function getRandomColor() {

    const colors = ["Red", "Green", "Violet"];

    return colors[Math.floor(Math.random() * colors.length)];
  }

  function finishRound() {

    const winningColor = getRandomColor();

    if (selected === winningColor) {

      points += 100;

      resultEl.innerHTML =
        "🎉 सही! Result: <b>" +
        winningColor +
        "</b><br>+100 Virtual Points";

    } else {

      resultEl.innerHTML =
        "❌ गलत! Result: <b>" +
        winningColor +
        "</b>";

    }

    pointsEl.textContent = points;

    addHistory(winningColor);

    round++;

    roundEl.textContent = round;

    selected = null;

    buttons.forEach(btn => {
      btn.disabled = false;
    });
  }

  function addHistory(color) {

    if (
      historyEl.children.length === 1 &&
      historyEl.children[0].textContent.includes("अभी")
    ) {
      historyEl.innerHTML = "";
    }

    const li = document.createElement("li");

    let dotClass = "";

    if (color === "Red") {
      dotClass = "red-dot";
    }

    if (color === "Green") {
      dotClass = "green-dot";
    }

    if (color === "Violet") {
      dotClass = "violet-dot";
    }

    li.innerHTML =
      "<span><span class='dot " +
      dotClass +
      "'></span>" +
      color +
      "</span>" +
      "<span>Round " +
      (round) +
      "</span>";

    historyEl.prepend(li);
  }

  function countdown() {

    time--;

    timerEl.textContent = time;

    if (time <= 0) {

      finishRound();

      time = 10;
    }
  }

  setInterval(countdown, 1000);

</script>

</body>
</html>
