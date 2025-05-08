<div align="center">
  <h1><img src="./assets/img/youtubelogo.png" width="120px" style="vertical-align: middle; margin-right: 3px;"> YouTube Clone Frontend</h1>
</div>

<h1>📍 목차</h1>
<ol>
  <li><a href="#intro"> 프로젝트 소개</a></li>
  <li><a href="#team"> 팀원 소개 및 역할</a></li>
  <li><a href="#features"> 주요 기능</a></li>
  <li><a href="#structure"> 프로젝트 구조 및 환경</a></li>
  <li><a href="#stack"> 사용 기술 및 도구</a></li>
  <li><a href="#convention"> 브랜치/커밋 컨벤션</a></li>
  <li><a href="#retrospective"> 최종 회고</a></li>
</ol>

<hr>

<h2 id="intro">1. 프로젝트 소개</h2>
<p>오르미 11기 백엔드 양성과정 대전 프론트엔드 프로젝트</p>
<ul>
  <li>경과: 영상 추천 Youtube 클론 페이지 구현</li>
  <li>진행 기간: 2025년 4월 21일 ~ 2025년 5월 12일</li>
  <li>목표: Home / Channel / Video / Search / Subscribe / Like 기능 구현, 공통 컴포넌트 재사용, API 연동 포함 협업 경험</li>
</ul>

<hr>

<h2 id="team">2. 팀원 소개 및 역할</h2>
<table>
  <tr>
    <td align="center" width="150px">
      <a href="https://github.com/KIMYOUNGLONG" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/206796619?v=4" alt="김영롱" width="100px"/><br />김영롱
      </a>
    </td>
    <td align="center" width="150px">
      <a href="https://github.com/sungyeonkim27" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/192389552?v=4" alt="김성연" width="100px"/><br />김성연
      </a>
    </td>
    <td align="center" width="150px">
      <a href="https://github.com/yoonhyunjin02" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/97629676?v=4" alt="윤현진" width="100px"/><br />윤현진
      </a>
    </td>
    <td align="center" width="150px">
      <a href="https://github.com/jwljwljwl" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/206796485?v=4" alt="이재원" width="100px"/><br />이재원
      </a>
    </td>
  </tr>
</table>

<h3>원인별 역할</h3>
<table border="1" align="center">
  <thead>
    <tr><th>이름</th><th>주요 구현 내용</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>윤현진</strong></td>
      <td>프로젝트 전체 조율, 브랜치 전략 수립, videoCard 구조 설계 및 재사용, develop 병합 및 충돌 해결, API 연동 구조 정비</td>
    </tr>
    <tr>
      <td><strong>김성연</strong></td>
      <td>검색 기능 구현, 태그 필터 API 연동, 반응형 UI 구현, 조회수 포맷 개선, home-search.js 최적화</td>
    </tr>
    <tr>
      <td><strong>이재원</strong></td>
      <td>사이드바 toggle, 공유/저장/좋아요/구독 기능, 댓글 정렬 및 대댓글 흐름, SVG 상태변화 구현</td>
    </tr>
    <tr>
      <td><strong>김영롱</strong></td>
      <td>리드미 정리 및 문서화, 필터바 기본 스타일링, CSS 보조 디버깅</td>
    </tr>
  </tbody>
</table>

<h4>기간별 역할 분담</h4>
<table border="1" align="center">
  <thead>
    <tr><th>기간</th><th>윤현진</th><th>김성연</th><th>이재원</th><th>김영롱</th></tr>
  </thead>
  <tbody>
    <tr><td>4/21~22</td><td>초기 구조 설계</td><td></td><td></td><td>리드미 양식 조사</td></tr>
    <tr><td>4/23~24</td><td>Header/Nav 설계</td><td>홈 검색 기능</td><td>Sidebar JS</td><td>버튼 UI</td></tr>
    <tr><td>4/25~26</td><td>videoCard 분기</td><td>video 검색</td><td>좋아요/구독</td><td>video.css 정리</td></tr>
    <tr><td>4/27~5/6</td><td>API 최종 정비</td><td>필터 태그 연동</td><td>대댓글 기능</td><td>README 정리</td></tr>
  </tbody>
</table>

<!-- 이하 생략 없이 실제 전체 섹션 삽입됨 -->