---
layout: project_page
permalink: /
title: "Hello, Stranger"
presentation: "글로벌미디어학부 2025 졸업전시"
team:
  - Ink
authors:
  - 최수영
  - 곽윤희
  - 조연정
affiliations:
  - Soongsil University
video: ""
code: "https://github.com/soo0choi/Ink.git"
data: "https://github.com/your-repo/dataset"
---

<style>
  /* 전체 컨테이너 가운데 정렬, 적절한 최대 너비 지정 */
  .project-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 1rem;
  }
  /* 이미지 블록 */
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
  /* 각 section 제목과 내용 간격 */
  section {
    margin-bottom: 2rem;
  }
  section h2 {
    margin-bottom: 0.5rem;
  }
  hr {
    border: none;
    border-top: 2px solid #ccc;
    margin-bottom: 1rem;
  }
  /* 팀원 소개: inline-block 으로 가로배치, 모바일에서는 세로로 쌓임 */
  .team-member {
    display: inline-block;
    vertical-align: top;
    width: 30%;
    min-width: 200px;
    margin-right: 1%;
  }
  .team-member:last-child {
    margin-right: 0;
  }
</style>

<div class="project-container">

  <!-- 이미지 행 -->
  <div class="image-row">
    <img src="images/wave01.png" alt="wave 001">
    <img src="images/bell01.jpg" alt="bell 001">
  </div>

  <!-- 작품 소개 -->
  <section>
    <h2>작품 소개</h2>
    <hr>
    <p><strong>Hello, Stranger</strong>는 낯선 이가 건네는 소리와 색을 통해 개인의 경험과 감성을 일깨우는 미디어아트입니다.</p>
    <p>낯선 이와의 눈맞춤 속, 관람객이 <strong>느끼는 모든 것이 작품의 의미</strong>가 되는 경험을 선사합니다.</p>
    <p>이 공간에는 수많은 사람들의 기억과 감정이 그대로 남아 스며듭니다.</p>
  </section>

  <!-- 기술 스택 -->
  <section>
    <h2>기술 스택</h2>
    <hr>
    <ul>
      <li>Touch Designer</li>
      <li>Maya</li>
      <li>Arduino</li>
    </ul>
  </section>

  <!-- 팀원 소개 -->
  <section>
    <h2>팀원 소개</h2>
    <hr>
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
      </ul>
    </div>
    <div class="team-member">
      <h3>조연정</h3>
      <ul>
        <li>기획, 디자인</li>
        <li><a href="mailto:misodul0826@naver.com">misodul0826@naver.com</a></li>
      </ul>
    </div>
  </section>

</div>
