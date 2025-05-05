
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  
  <style>
    body {
      max-width: 900px;
      margin: 0 auto;
      padding: 1rem;
      font-family: sans-serif;
      text-align: left;
    }
    header {
      margin-bottom: 2rem;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      color: #000; /* 파란색 링크로 보이지 않도록 */
    }
    header .subtitle {
      margin: 0.25rem 0 0;
      color: #666;
      font-size: 1rem;
    }
    .image-row {
      display: flex;
      justify-content: space-between;
      gap: 1rem;
      margin-bottom: 2rem;
    }
    .image-row img {
      width: 48%;
      height: auto;
      display: block;
    }
    section + section {
      margin-top: 2rem;
    }
    section h2 {
      margin-bottom: 0.5rem;
    }
    hr {
      border: none;
      border-top: 2px solid #eee;
      margin: 0.5rem 0 1rem;
    }
    .team-list {
      display: flex;
      justify-content: space-between;
      gap: 1rem;
      margin-top: 1rem;
    }
    .team-member {
      width: 30%;
    }
    .team-member h3 {
      margin-bottom: 0.25rem;
    }
    .team-member ul {
      list-style: disc;
      padding-left: 1.25rem;
      margin: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hello, Stranger</h1>
    <p class="subtitle">Team.Ink</p>
    <p class="subtitle">글로벌미디어학부 2025 졸업전시</p>
  </header>

  <div class="image-row">
    <img src="images/wave01.png" alt="wave 001">
    <img src="images/bell01.jpg" alt="bell 001">
  </div>

  <section>
    <h2>작품 소개</h2>
    <hr />
    <p><strong>Hello, Stranger</strong>는 낯선 이가 건네는 소리와 색을 통해 개인의 경험과 감성을 일깨우는 미디어아트입니다.</p>
    <p>낯선 이와의 눈맞춤 속, 관람객이 <strong>느끼는 모든 것이 작품의 의미</strong>가 되는 경험을 선사합니다.</p>
    <p>이 공간에는 수많은 사람들의 기억과 감정이 그대로 남아 스며듭니다.</p>
  </section>

  <section>
    <h2>기술 스택</h2>
    <hr />
    <ul>
      <li>Touch Designer</li>
      <li>Maya</li>
      <li>Arduino</li>
    </ul>
  </section>

  <section>
    <h2>팀원 소개</h2>
    <hr />
    <div class="team-list">
      <div class="team-member">
        <h3>최수영</h3>
        <ul>
          <li>기획, 개발</li>
          <li><a href="mailto:csy010921@naver.com">csy010921@naver.com</a></li>
        </ul>
      </div>
      <div class="team-member">
        <h3>곽윤희</h3>
        <ul>
          <li>기획, 디자인</li>
          <li><a href="mailto:misodul0826@naver.com"><li><a href="mailto:misodul0826@naver.com">misodul0826@naver.com</a></li></a></li>
        </ul>
      </div>
      <div class="team-member">
        <h3>조연정</h3>
        <ul>
          <li>기획, 디자인</li>
          <li><a href="mailto:misodul0826@naver.com">misodul0826@naver.com</a></li>
        </ul>
      </div>
    </div>
  </section>
</body>
</html>
