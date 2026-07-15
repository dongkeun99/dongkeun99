<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>이동근 (Dongkeun Lee) — GitHub Profile README</title>
<style>
  :root {
    --ink: #1c2530;
    --sub: #57606a;
    --line: #d8dee4;
    --blue: #1668a8;
    --blue-soft: #eaf3fa;
    --code-bg: #eff2f5;
    --code-ink: #1f4e79;
    --green: #2a8c6a;
    --bg: #ffffff;
  }
  * { box-sizing: border-box; }
  body {
    margin: 0;
    background: #f6f8fa;
    font-family: -apple-system, "Segoe UI", "Noto Sans KR", "Apple SD Gothic Neo", sans-serif;
    color: var(--ink);
    line-height: 1.65;
  }
  .wrap {
    max-width: 860px;
    margin: 0 auto;
    background: var(--bg);
    padding: 48px 56px 64px;
    border-left: 1px solid var(--line);
    border-right: 1px solid var(--line);
  }
  h1 {
    font-size: 30px; margin: 0 0 4px; letter-spacing: -0.5px;
  }
  h1 .en { color: var(--sub); font-weight: 500; font-size: 22px; }
  h3.tag {
    font-size: 17px; color: var(--ink); font-weight: 700;
    margin: 18px 0 10px;
  }
  .lead { color: #37414c; font-size: 14.5px; margin: 0 0 6px; }
  .lead b { color: var(--blue); }
  .links { font-size: 14px; margin: 16px 0 4px; }
  .links a { color: var(--blue); text-decoration: none; font-weight: 600; }
  hr {
    border: none; border-top: 1px solid var(--line); margin: 30px 0;
  }
  h2 {
    font-size: 21px; margin: 6px 0 14px; letter-spacing: -0.3px;
    display: flex; align-items: center; gap: 8px;
  }
  h2 .ico { font-size: 18px; }
  h4 {
    font-size: 15.5px; margin: 20px 0 8px; color: #16324a;
  }
  p { margin: 8px 0; font-size: 14px; }
  .quote {
    border-left: 3px solid var(--blue); background: var(--blue-soft);
    padding: 10px 16px; margin: 12px 0; color: #2c3a45; font-size: 13.5px;
    border-radius: 0 5px 5px 0;
  }
  .quote em { color: #1a5a8c; font-style: italic; }
  table {
    border-collapse: collapse; width: 100%; margin: 12px 0; font-size: 13.5px;
  }
  th, td {
    border: 1px solid var(--line); padding: 8px 12px; text-align: left; vertical-align: top;
  }
  th { background: #f2f5f8; font-weight: 700; }
  td b { color: #16324a; }
  code {
    background: var(--code-bg); color: var(--code-ink);
    font-family: "SFMono-Regular", Consolas, "DejaVu Sans Mono", monospace;
    font-size: 12.5px; padding: 1px 5px; border-radius: 4px;
  }
  pre {
    background: #0f1b26; color: #d6e3ee; padding: 16px 18px; border-radius: 8px;
    overflow-x: auto; font-size: 12.5px; line-height: 1.55;
    font-family: "SFMono-Regular", Consolas, "DejaVu Sans Mono", monospace;
  }
  pre .c { color: #7f9bb3; }
  pre .t { color: #79c0ff; }
  pre .k { color: #ffa657; }
  .badges { margin: 10px 0; }
  .chip {
    display: inline-block; background: var(--blue); color: #fff;
    font-size: 11px; font-weight: 600; padding: 3px 10px; border-radius: 12px;
    margin: 2px 3px 2px 0;
  }
  .meta { color: var(--sub); font-size: 12.5px; margin: 4px 0 0; }
  ul.clean { padding-left: 20px; margin: 8px 0; }
  ul.clean li { font-size: 13.5px; margin: 4px 0; }
  ol { padding-left: 22px; }
  ol li { font-size: 13.5px; margin: 4px 0; }
  .solve b, .result b { color: var(--blue); }
  .result { color: var(--green); font-weight: 700; }
  .footnote {
    font-size: 12px; color: var(--sub); background: #fafbfc;
    border: 1px dashed var(--line); padding: 10px 14px; border-radius: 6px; margin: 12px 0;
  }
</style>
</head>
<body>
<div class="wrap">

  <h1>이동근 <span class="en">(Dongkeun Lee)</span></h1>
  <h3 class="tag">모르는 자리에서 가장 먼저 손을 드는 개발자 이동근입니다.</h3>
  <p class="lead">기계공학에서 출발해 스스로 진로를 바꿨습니다.</p>
  <p class="lead">그렇게 자원한 자리에서 HTML을 처음 배웠고, 부트캠프 두 프로젝트에서 1위를 했으며, 지금은 백엔드를 맡고 있습니다.</p>
  <p class="lead">화면만 만드는 개발자보다 <b>데이터가 어디서 와서 어떻게 흐르는지 아는 개발자</b>가 되려 합니다.</p>
  <p class="links">📄 <a href="https://github.com/dongkeun99/dongkeun99/blob/main/portfolio.pdf">포트폴리오 PDF 보기</a> · ✉️ <a href="mailto:mark6896@naver.com">mark6896@naver.com</a></p>

  <hr>

  <h2><span class="ico">🛠</span> Tech Stack</h2>
  <table>
    <tr><th style="width:22%">분류</th><th>기술</th></tr>
    <tr><td><b>Frontend</b></td><td><code>TypeScript</code> <code>JavaScript(ES6+)</code> <code>React</code> <code>Next.js (App Router)</code> <code>Tailwind CSS</code></td></tr>
    <tr><td><b>Backend / Data</b></td><td><code>Supabase</code> <code>PostgreSQL</code> <code>DB Trigger</code> <code>Realtime</code></td></tr>
    <tr><td><b>Tools</b></td><td><code>Git</code> <code>GitHub</code> <code>Vercel</code> <code>Figma</code> <code>Claude Code</code> <code>Codex</code></td></tr>
  </table>
  <p>생성된 코드를 그대로 두지 않고, <b>왜 그렇게 동작하는지 확인한 뒤 반영하는 것</b>을 기준으로 삼습니다. 속도는 도구에서 얻되, 판단은 스스로 합니다.</p>

  <hr>

  <h2><span class="ico">📦</span> Kanto — 필리핀 생활 필수 플랫폼</h2>
  <div class="quote">중고거래 · 구인구직 · 부동산을 한 곳에서 다루는 커뮤니티 서비스<br>멋쟁이사자처럼 부트캠프 파이널 프로젝트 · <b>팀 평가 1위</b></div>
  <div class="badges">
    <span class="chip">Demo · kanto-iota.vercel.app</span>
    <span class="chip">Code · github.com/FRONTENDBOOTCAMP-17th/kanto</span>
  </div>
  <p class="meta"><code>Next.js</code> <code>TypeScript</code> <code>Supabase</code> <code>Tailwind CSS</code> · 프론트엔드 4인 · 2026.05 ~ 2026.07</p>

  <h4>담당한 것</h4>
  <table>
    <tr><th style="width:30%">파트</th><th>내용</th></tr>
    <tr><td><b>회원가입</b> <code>/signup</code></td><td>폼 상태 관리 및 유효성 검증, Supabase 인증 연동, 가입 시 회원 정보 자동 생성 트리거</td></tr>
    <tr><td><b>중고물품 상세</b> <code>/usedgoods/[id]</code></td><td>이미지 캐러셀, DB 트리거 기반 좋아요 수 집계, 좋아요 알림 Realtime 전달, 신고 모달, 작성자 전용 수정·삭제(서버 소유권 재검증)</td></tr>
    <tr><td><b>관리자 회원 관리</b> <code>/admin/users</code></td><td>서버·클라이언트 컴포넌트 분리, 반응형 UI(테이블형/카드형)</td></tr>
    <tr><td><b>부동산 등록</b> <code>/rental/create</code></td><td>다단계 입력 폼, posts–rentals 2단계 저장 구조 설계</td></tr>
    <tr><td><b>페이지네이션 공통 컴포넌트</b></td><td>props 3개만 노출하고 페이지 상태는 URL에 위임한 순수 컴포넌트 — 유저 목록 5곳 + 프로필 4개 섹션 등 <b>총 9곳</b>에서 재사용</td></tr>
    <tr><td><b>유지보수</b></td><td>그 외 다수 페이지의 에러·버그 수정</td></tr>
  </table>

  <h4>담당 파트의 데이터 구조</h4>
<pre><span class="t">auth.users</span>  <span class="c">(Supabase 인증)</span>
    │
    │  <span class="k">Trigger</span> — 가입 시 자동 생성
    ▼
<span class="t">public.users</span>  ── auth_id 로 연결
    │
    │  user_id
    ▼
  <span class="t">posts</span>  <span class="c">(게시글 공통 정보)</span>
    ├──▶ <span class="t">usedgoods</span>  <span class="c">(중고물품 고유 정보)</span>
    │       ▲
    │       │ <span class="k">Trigger</span> — likes 추가·삭제 시 like_count 자동 갱신
    │     <span class="t">likes</span>
    │
    └──▶ <span class="t">rentals</span>    <span class="c">(부동산 고유 정보 · 2단계 저장)</span></pre>

  <h4>기억에 남는 문제 해결</h4>

  <p><b>회원가입은 성공하는데, 서비스 회원 정보가 저장되지 않던 문제</b></p>
  <p>Supabase는 인증 정보를 <code>auth.users</code>에, 서비스 프로필을 <code>public.users</code>에 따로 보관합니다. 가입은 되는데 서비스 회원이 생기지 않아 원인을 파고들자 <b>세 겹으로 겹쳐</b> 있었습니다.</p>
  <ol>
    <li>두 테이블을 이어주는 <b>트리거가 없었음</b></li>
    <li><code>public.users.id</code>에 자동 증가 기본값이 없어 <b>NOT NULL 위반</b></li>
    <li>결정적으로, <b>트리거 함수가 에러를 던지면 <code>auth.users</code> 삽입까지 함께 롤백</b>되어 회원가입 자체가 실패</li>
  </ol>
  <p>세 번째 원인은 에러 메시지에 드러나지 않아, 한 겹씩 벗겨내며 직접 찾아야 했습니다.</p>
  <p class="solve"><b>해결</b> — 가입 시 <code>public.users</code>에 회원을 자동 생성하는 트리거 함수를 작성했습니다. 시퀀스로 <code>id</code>를 채우고, <code>auth_id</code>로 인증 계정과 서비스 프로필을 연결하고, <code>ON CONFLICT DO NOTHING</code>으로 중복 가입을 무시하도록 했습니다. 처음 해결할 때는 함수 전체를 예외 처리로 감싸 프로필 생성이 실패해도 인증 정보는 남도록 만들었고, 이후 팀에서 중복 트리거를 정리하는 과정에서 중복 방지 처리만으로 충분한 형태로 단순화됐습니다.</p>
  <p><span class="result">결과</span> — 여기서 만든 <code>auth_id</code> 연결 규칙은 이후 관리자 회원 관리와 부동산 등록에서 회원을 식별하는 기준으로 그대로 재사용되었습니다.</p>

  <p><b>좋아요를 누를 때마다 전체 개수를 세던 비효율</b></p>
  <p>좋아요 수를 표시하려면 매번 좋아요 테이블(<code>common_likes</code>) 전체를 <code>count</code> 조회해야 했고, 목록에 카드가 늘어날수록 조회가 그만큼 반복되는 구조였습니다.</p>
  <p class="solve"><b>해결</b> — 게시글 테이블에 <code>like_count</code> 컬럼을 두고, 좋아요 추가·삭제 시 값을 자동 갱신하는 <b>DB Trigger</b>를 작성했습니다. 애플리케이션이 아니라 <b>DB가 정합성을 책임지게</b> 해, 어느 경로로 변경되든 수치가 어긋나지 않도록 했습니다.</p>
  <p><span class="result">결과</span> — 조회는 컬럼 하나를 읽는 것으로 끝납니다. 또한 좋아요가 달리면 트리거가 작성자에게 알림을 생성하고, 작성자는 이 알림을 <b>Realtime 구독</b>하고 있어 새로고침 없이 즉시 전달받습니다.</p>

  <p><b>게시글과 임대 정보를 어떻게 나눠 저장할 것인가</b></p>
  <p>부동산 글에는 제목·이미지처럼 <b>모든 게시글의 공통 정보</b>와, 보증금·방 타입·편의시설처럼 <b>부동산에만 있는 정보</b>가 섞여 있었습니다. 한 테이블에 전부 넣으면 중고거래·구인구직 글에는 빈 칸만 늘어납니다.</p>
  <p class="solve"><b>해결</b> — 공통 정보는 <code>posts</code>, 부동산 고유 정보는 <code>rentals</code>로 분리하고, <code>posts</code>를 먼저 저장해 얻은 식별자로 <code>rentals</code>를 저장하는 <b>2단계 저장 구조</b>를 설계했습니다.</p>
  <p><span class="result">결과</span> — 게시글 종류가 늘어나도 공통 구조를 재사용할 수 있게 되었고, 삭제 시 연결된 데이터도 함께 정리되도록 처리했습니다.</p>

  <hr>

  <h2><span class="ico">🌱</span> 또랑 — AI 쉬운 정보 서비스 (해커톤)</h2>
  <div class="quote">느린학습자 · 경계선 지능인을 위해 어려운 정보를 쉬운 말로 바꿔주는 AI 서비스<br><b>기획서 제출 완료 · 심사 대기 중</b> (개발 착수 전)</div>
  <p>프론트엔드가 익숙하지만, 이번에는 <b>백엔드(Server)를 자원</b>했습니다. 파이널 프로젝트에서 Supabase를 다루며 <em>화면은 결국 데이터가 흐른 결과일 뿐</em>이라는 걸 체감했기 때문입니다.</p>
  <p><b>대상자 분류 알고리즘 설계</b> — 사용자의 이해 수준을 3단계로 나누는 기준을 설계했습니다.</p>
  <ul class="clean">
    <li>절단점수(cut-off) 기반 구간 설정</li>
    <li>측정표준오차(SEM)를 반영한 경계 보정</li>
    <li>애매한 구간은 더 쉬운 단계로 배정하는 <b>보수적 규칙</b> — 어려운 설명을 받아 이해하지 못하는 위험이, 쉬운 설명을 받는 불편보다 크다고 판단</li>
  </ul>
  <p>기능을 짜기 전에 <b>"무엇이 옳은 분류인가"를 먼저 정의해야 한다</b>는 것을 배운 과정이었습니다.</p>

  <hr>

  <h2><span class="ico">📚</span> Background</h2>
  <table>
    <tr><td style="width:24%"><b>원광대학교</b></td><td>컴퓨터·소프트웨어공학과 · 2025.08 졸업 (3학년 편입 · 평점 3.61)</td></tr>
    <tr><td><b>멋쟁이사자처럼</b></td><td>프론트엔드 부트캠프 · 2026.01 ~ 2026.07 · <b>팀 프로젝트 1위 2회 · 우수상(수강생 중 4인)</b></td></tr>
    <tr><td><b>자격</b></td><td>정보처리기사 (2025)</td></tr>
  </table>

</div>
</body>
</html>
