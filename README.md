<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>SOW – 언어 선택</title>
  <style>
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f7ff;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }
    header {
      text-align: center;
      margin-top: 40px;
      margin-bottom: 20px;
    }
    h1 {
      margin: 0;
      font-size: 28px;
    }
    p {
      margin: 6px 0;
      color: #555;
    }
    .lang-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      margin-top: 20px;
      padding: 20px;
    }
    .card {
      background: white;
      padding: 20px 24px;
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      width: 260px;
      text-align: center;
    }
    .card h2 {
      margin-top: 0;
      margin-bottom: 8px;
      font-size: 22px;
    }
    .card p {
      font-size: 14px;
      margin-bottom: 16px;
    }
    .btn {
      display: inline-block;
      padding: 10px 18px;
      border-radius: 999px;
      border: none;
      text-decoration: none;
      font-size: 14px;
      cursor: pointer;
      background: #4f46e5;
      color: white;
    }
    .btn.disabled {
      background: #cbd5f5;
      cursor: default;
    }
    footer {
      margin-top: auto;
      margin-bottom: 20px;
      font-size: 12px;
      color: #999;
    }
  </style>
</head>
<body>
  <header>
    <h1>SOW – 성실 엄마표 스터디</h1>
    <p>언어를 선택하고, 그 안에서 권(책)과 과를 선택해서 공부해요.</p>
  </header>

  <div class="lang-container">
    <!-- 영어 영역 (나중에 채우기) -->
    <div class="card">
      <h2>English Zone</h2>
      <p>영어 찬양 / 영어 말씀 / 영어 어휘 공부 (준비 중)</p>
      <a class="btn disabled">준비 중</a>
    </div>

    <!-- 중국어 영역 -->
    <div class="card">
      <h2>中文区 (중국어 Zone)</h2>
      <p>중국어 찬양, 말씀, 단어 학습</p>
      <!-- 여기서 중국어 찬양 1권으로 이동 -->
      <a class="btn" href="cn-praise-1/index.html">중국어 찬양 1권으로 가기</a>
    </div>
  </div>

  <footer>
    SOWBIBLE · 규랭이의 말씀·언어·공부 놀이터
  </footer>
</body>
</html>
