<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>표독지수 상승</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      text-align: center;
      background-color: #f5f5f5;
      padding: 50px;
    }

    h1 {
      font-size: 48px;
      color: black;
      margin-bottom: 10px;
    }

    #percentage {
      font-size: 36px;
      margin-bottom: 30px;
    }

    .graph-container {
      width: 80%;
      height: 200px;
      background: #ddd;
      margin: 0 auto 30px;
      position: relative;
      overflow: hidden;
      border-radius: 12px;
    }

    .graph-fill {
      height: 100%;
      background: linear-gradient(90deg, #ff4d4d 0%, #ff0000 100%);
      width: 0%;
      transition: width 0.5s ease;
    }

    .button-container {
      margin-top: 20px;
    }

    button {
      padding: 10px 20px;
      font-size: 18px;
      margin: 0 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    #increaseBtn {
      background-color: #4CAF50;
      color: white;
    }

    #increaseBtn:hover {
      background-color: #45a049;
    }

    #resetBtn {
      background-color: #f44336;
      color: white;
    }

    #resetBtn:disabled {
      background-color: #ccc;
      cursor: not-allowed;
    }

    #resetBtn:hover:enabled {
      background-color: #d32f2f;
    }
  </style>
</head>
<body>

  <h1>표독지수</h1>
  <div id="percentage">0%</div>
  <div class="graph-container">
    <div class="graph-fill" id="graph"></div>
  </div>

  <div class="button-container">
    <button id="increaseBtn">상승</button>
    <button id="resetBtn" disabled>초기화</button>
  </div>

  <script>
    let current = 0;
    const percentage = document.getElementById('percentage');
    const graph = document.getElementById('graph');
    const increaseBtn = document.getElementById('increaseBtn');
    const resetBtn = document.getElementById('resetBtn');

    function updateDisplay() {
      if (current >= 100) {
        percentage.textContent = 'MAX';
        graph.style.width = '100%';
        increaseBtn.disabled = true;
        resetBtn.disabled = false;
      } else {
        percentage.textContent = current + '%';
        graph.style.width = current + '%';
      }
    }

    increaseBtn.addEventListener('click', () => {
      if (current < 100) {
        current += 5;
        if (current > 100) current = 100;
        updateDisplay();
      }
    });

    resetBtn.addEventListener('click', () => {
      current = 0;
      updateDisplay();
      percentage.textContent = '0%';
      graph.style.width = '0%';
      increaseBtn.disabled = false;
      resetBtn.disabled = true;
    });
  </script>
</body>
</html>
