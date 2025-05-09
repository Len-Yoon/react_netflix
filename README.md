<h1>react_netflix</h1>

<p><strong>React를 이용해 만든 Netflix 클론 프로젝트입니다.</strong><br>
Firebase를 통한 사용자 인증 기능과 영화 API 데이터를 활용하여 Netflix 스타일의 UI를 구현했습니다.</p>

<h2>🛠 사용 기술</h2>
<ul>
  <li>React</li>
  <li>React Router</li>
  <li>Firebase Authentication</li>
  <li>Styled-components</li>
  <li>TMDB(The Movie Database) API</li>
</ul>

<h2>✨ 주요 기능</h2>
<ul>
  <li>회원가입 및 로그인 (Firebase 인증 사용)</li>
  <li>영화 목록 조회 및 상세 페이지</li>
  <li>Netflix 스타일의 반응형 UI</li>
  <li>로그아웃 기능</li>
</ul>

<h2>🗂 프로젝트 구조</h2>
<pre>
react_netflix/
├── src/
│   ├── components/
│   ├── pages/
│   ├── store/
│   ├── utils/
│   └── App.js
├── public/
├── package.json
└── README.md
</pre>

<h2>🚀 시작하기</h2>
<ol>
  <li>프로젝트 클론
    <pre><code>git clone https://github.com/Len-Yoon/react_netflix.git
cd react_netflix</code></pre>
  </li>
  <li>필요한 패키지 설치
    <pre><code>npm install</code></pre>
  </li>
  <li>환경 변수 설정 (<code>.env</code> 파일 생성)
    <pre><code>REACT_APP_API_KEY=your_tmdb_api_key
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
...</code></pre>
  </li>
  <li>프로젝트 실행
    <pre><code>npm start</code></pre>
  </li>
</ol>

<h2>📌 참고</h2>
<ul>
  <li>영화 데이터는 <a href="https://www.themoviedb.org/documentation/api" target="_blank">TMDB API</a>를 사용했습니다.</li>
  <li>인증 기능은 <a href="https://firebase.google.com/products/auth" target="_blank">Firebase Authentication</a>을 기반으로 구현했습니다.</li>
</ul>
