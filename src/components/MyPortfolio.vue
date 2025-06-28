<template>

    <head>
        <title>백엔드 개발자를 꿈꾸는 김용희의 포트폴리오</title>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=340, initial-scale=1, maximum-scale=1, minimum-scale=1, user-scalable=no" />
    </head>

    <body>
        <section class="left-header">
            <section class="photo-section">
                <div class="circle-photo">
                    <img src="@/assets/image/avatar.jpg" alt="증명사진" />
                </div>

            </section>
            <div class="profile-name">김용희 <br> KimyYongHee</div>
            <nav class="nav-col">
                <a href="#Introduction">Introduction</a>
                <a href="#Education">Education</a>
                <a href="#Career">Career</a>
                <a href="#SkillSet">SkillSet</a>
                <a href="#Portfolio">Portfolio</a>
                <a href="#Centification">Centification</a>
                <a href="#Context">Context</a>
            </nav>
        </section>
        <main class="main-content">
            <section id="Introduction">
                <h2>Introduction</h2>
                <h1>안녕하세요.<br>백엔드 개발자를 꿈꾸는 <br>김용희 입니다.</h1>
                <h3>"성장과 전환의 시간"</h3>
                <p><strong>안녕하세요 조금 늦은 나이에 다시 백엔드 개발자란 꿈에 도전하는 신입 개발자 김용희입니다.</strong><br>
                컴퓨터소프트웨어공학과를 졸업하고 행정직에서 근무하며, 다양한 사람들과 소통하고 동료들과 협력하여 문제를 해결하는 지혜를 얻었습니다. 이 경험은 제가 백엔드 개발자로서 견고한 시스템을 구축하고 팀원원과 시너지를 내는 데 중요한 자신이 될 것이라 확신합니다. 지난 시간은 저에게 백엔드 개발에 대한 확신과 깊은 열정을 심어주었고, 현재는 '다시 꿈꾸는 백엔드 개발자'라는 목표를 향해 적극적으로 역량을 키워나가고 있습니다.</p>
            </section>
            <section id="Education">
                <h2>Education</h2>
                <p>2017 ~ 2024 원광대학교 컴퓨터소프트웨어공학과 졸업</p>
                <p>2023 ~ 2023 벤쳐 스타트업 아카데미(풀스택 개발자 양성과정) 수료</p>
                <p>2025 ~ 2026 코드잇 스프린트, AWS활용 Spring 백엔드 개발자 부트캠프 수료</p>
            </section>
            <section id="Career">
                <h2>Career</h2>
                <p>2024 ~ 2025 원광대학교 컴퓨터소프트웨어공학과 교육보조원</p>
            </section>
            <section id="SkillSet">
                <h2>SkillSet</h2>
                <p>JAVA</p>
                <p>Spring</p>
                <p>JPA</p>
                <p>MySQL</p>
            </section>
            <section id="Portfolio">
                <h2>Portfolio</h2>
                <p>포트폴리오는 여기에 </p>
            </section>
            <section id="Certification">
                <h2>Certification</h2>
                <p>2025 정보처리기사 취득</p>
            </section>
            <section id="Contact">
                <h2>Contact Me</h2>
                <p>Phone: 010-3423-1465</p>
                <p>Email: dydgml7313@gmail.com</p>
                <p>Github: https://github.com/backKim1024</p>
            </section>
        </main>
    </body>

</template>

<style>
/* ---------- 공통 유틸리티 ---------- */
:root {
    --main-bg: #129990;
    --main-bg-dark: #0e7c7b;
    --accent: #FFFBDE;
    --white: #fff;
    --shadow: 0 4px 24px rgba(0,0,0,0.08);
    --border-radius: 18px;
    --font-main: 'Pretendard', 'Noto Sans KR', Arial, sans-serif;
}

html {
    scroll-behavior: smooth; /* 부드러운 스크롤 */
    background: var(--accent);
}

body {
    margin: 0;
    padding: 0;
    display: flex;
    font-family: var(--font-main);
    background: var(--accent);
    color: #222;
}

/* ---------- 사이드 헤더 ---------- */
.left-header {
    width: 340px; /* 살짝 줄임 */
    min-height: 100vh;
    background: linear-gradient(135deg, var(--main-bg), var(--main-bg-dark));
    color: var(--white);
    padding: 32px 20px 32px 20px; /* 더 넉넉한 패딩 */
    box-sizing: border-box;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: center; /* 가로 가운데 정렬로 변경 */
    box-shadow: var(--shadow); /* 그림자 추가 */
    border-right: 2px solid #e0e0e0;
}

/* ---------- 프로필 사진 ---------- */
.photo-section {
    width: 100%;
    margin-bottom: 12px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.circle-photo {
    width: 180px; /* 더 작게, 더 세련되게 */
    height: 180px;
    border-radius: 50%;
    overflow: hidden;
    background: #fffbe9;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 4px 24px rgba(0,0,0,0.10); /* 더 부드러운 그림자 */
    margin-bottom: 20px;
    border: 4px solid var(--accent); /* 포인트 테두리 */
}

.circle-photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
}

/* ---------- 이름 ---------- */
.profile-name {
    text-align: center;
    margin: 0 0 32px 0; /* 아래로만 여백 */
    font-size: 2.1rem;
    font-weight: 800;
    line-height: 1.2;
    letter-spacing: 1px;
    width: 100%;
    color: var(--white);
    text-shadow: 0 2px 8px rgba(0,0,0,0.08);
}

/* ---------- 네비게이션 ---------- */
.nav-col {
    display: flex;
    flex-direction: column;
    gap: 18px;
    align-items: center;
    text-align: center;
    width: 100%;
    margin-top: 16px;
}

.nav-col a {
    color: var(--accent);
    font-size: 1.3rem;
    font-weight: 700;
    text-decoration: none;
    border-radius: 10px; 
    padding: 12px 0;
    width: 90%;
    transition: 
        background 0.22s cubic-bezier(.4,0,.2,1),
        color 0.22s cubic-bezier(.4,0,.2,1),
        box-shadow 0.18s;
    letter-spacing: 0.5px;
    /* box-shadow: 0 2px 8px rgba(0,0,0,0.03); */
}

.nav-col a:hover,
.nav-col a:focus {
    background: var(--accent);
    color: var(--main-bg);
    box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}

/* ---------- 메인 컨텐츠 ---------- */
.main-content {
    margin-left: 340px; /* 헤더와 맞춤 */
    padding: 56px 48px 56px 48px;
    flex: 1;
    min-height: 100vh;
    background: var(--accent);
    box-sizing: border-box;
    /* 부드러운 그림자 효과 */
}

.main-content section {
    background: var(--white);
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
    padding: 40px 32px 32px 32px;
    margin-bottom: 38px;
    transition: box-shadow 0.2s;
}

.main-content section:hover {
    box-shadow: 0 8px 32px rgba(18,153,144,0.13);
}

.main-content h2 {
    color: var(--main-bg);
    font-size: 2.1rem;
    margin-bottom: 18px;
    font-weight: 800;
    letter-spacing: 1px;
    border-left: 6px solid var(--main-bg);
    padding-left: 12px;
    background: linear-gradient(90deg, #e0f7f4 60%, transparent 100%);
    border-radius: 8px;
}

.main-content h1 {
    font-size: 2.5rem;
    font-weight: 900;
    margin: 20px 0 12px 0;
    color: #222;
}

.main-content h3 {
    font-size: 1.3rem;
    color: var(--main-bg-dark);
    margin-bottom: 18px;
    font-weight: 700;
}

.main-content p {
    font-size: 1.12rem;
    line-height: 1.7;
    margin-bottom: 10px;
    color: #333;
}

.main-content strong {
    color: var(--main-bg);
    font-weight: 700;
}

/* ---------- 기타 ---------- */
/* 링크 강조 효과 등 추가 가능 */
a {
    outline: none;
}
</style>