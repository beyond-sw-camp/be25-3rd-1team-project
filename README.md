<div align="center">

<!-- ✅ 통통 튀면서 왼→오 날아오는 Subees (SVG data URI) -->
<img
  alt="Subees bounce-in"
  src="data:image/svg+xml;utf8,<?xml version='1.0' encoding='UTF-8'?>\
<svg xmlns='http://www.w3.org/2000/svg' width='900' height='120' viewBox='0 0 900 120'>\
  <defs>\
    <style><![CDATA[\
      .t{font-family:'Noto Sans KR','Pretendard','Inter','Segoe UI',sans-serif; font-weight:900; font-size:56px; fill:#fff;}\
      /* 왼쪽 바깥에서 시작 → 오버슈트(튀김) → 정착 */\
      @keyframes fly{\
        0%   {transform:translate(-280px,0) scale(.92);}\
        60%  {transform:translate(18px,0)  scale(1.03);}\
        78%  {transform:translate(-10px,0) scale(.99);}\
        90%  {transform:translate(6px,0)   scale(1.01);}\
        100% {transform:translate(0,0)     scale(1);}\
      }\
      /* 통통 튀는 느낌(수직 바운스) */\
      @keyframes bounce{\
        0%,100%{transform:translateY(0);}\
        20%{transform:translateY(-10px);}\
        40%{transform:translateY(0);}\
        60%{transform:translateY(-6px);}\
        80%{transform:translateY(0);}\
      }\
      .wrap{animation:fly 1.1s cubic-bezier(.2,.9,.25,1) both;}\
      .b{animation:bounce .9s ease-out .25s both;}\
      /* 글자별 딜레이(살짝 파도처럼) */\
      .c1{animation:bounce .9s ease-out .25s both;}\
      .c2{animation:bounce .9s ease-out .30s both;}\
      .c3{animation:bounce .9s ease-out .35s both;}\
      .c4{animation:bounce .9s ease-out .40s both;}\
      .c5{animation:bounce .9s ease-out .45s both;}\
      .c6{animation:bounce .9s ease-out .50s both;}\
    ]]></style>\
  </defs>\
  <g class='wrap' transform='translate(0,0)'>\
    <g transform='translate(70,78)'>\
      <text class='t'>\
        <tspan class='c1'>S</tspan>\
        <tspan class='c2'>u</tspan>\
        <tspan class='c3'>b</tspan>\
        <tspan class='c4'>e</tspan>\
        <tspan class='c5'>e</tspan>\
        <tspan class='c6'>s</tspan>\
      </text>\
    </g>\
  </g>\
</svg>"
/>


## 통합 구독 관리 서비스 Front-end (Subees)

<img src="./이미지/로고/Subees_Logo.png" width="320" alt="Subees Logo" />
<br />
<sub><b>Team Logo</b></sub>

<br /><br />

<img src="./이미지/포스터/포스터예시.jpg" width="620" alt="Project Poster" />
<br />
<sub><b>Project Poster</b></sub>

<br /><br />

<img src="https://img.shields.io/badge/Frontend-React-0f172a?style=for-the-badge" alt="Frontend" />
<img src="https://img.shields.io/badge/Language-TypeScript-0f172a?style=for-the-badge" alt="TypeScript" />
<img src="https://img.shields.io/badge/Style-Tailwind%20CSS-0f172a?style=for-the-badge" alt="Tailwind" />
<img src="https://img.shields.io/badge/State-TanStack%20Query-0f172a?style=for-the-badge" alt="TanStack Query" />

</div>


---

## 👀목차
1. [👥팀원 소개](#팀원-소개)
2. [📌프로젝트 개요 (Project Overview)](#프로젝트-개요-project-overview)
3. [🧠프로젝트 선정 이유 및 기대 효과](#프로젝트-선정-이유-및-기대-효과)
4. [🗺️사용자 시나리오 및 프로세스 맵](#사용자-시나리오-및-프로세스-맵)
5. [🧰기술 스택 (Tech Stack)](#기술-스택-tech-stack)
6. [🧩Framework & Language](#framework--language)
7. [🔁상태 관리 및 통신 라이브러리](#상태-관리-및-통신-라이브러리)
8. [🎨UI 라이브러리 및 디자인 도구](#ui-라이브러리-및-디자인-도구)
9. [🏗️설계 및 구조 (Design & Architecture)](#설계-및-구조-design--architecture)
10. [🖼️화면 및 기능 설계서 (Figma)](#화면-및-기능-설계서-figma)
11. [🧩유스케이스 다이어그램 (Use Case Diagram)](#유스케이스-다이어그램-use-case-diagram)
12. [🧱컴포넌트 계층 구조 및 폴더 구조](#컴포넌트-계층-구조-및-폴더-구조)
13. [🧪단위 테스트 및 시연 (UI/UX Unit Test)](#단위-테스트-및-시연-uiux-unit-test)
14. [🎞️기능별 시연 GIF](#기능별-시연-gif)
15. [📊UI/UX 단위 테스트 결과서 (Spreadsheet 링크)](#uiux-단위-테스트-결과서-spreadsheet)
16. [🧭브라우저 호환성 및 반응형 대응 현황](#브라우저-호환성-및-반응형-대응-현황)
17. [📌개발 관리 및 회고 (Project Management)](#개발-관리-및-회고-project-management)
18. [📅WBS 기반 일정 관리 현황](#wbs-기반-일정-관리-현황)
19. [🚀향후 개선 및 확장 방안](#향후-개선-및-확장-방안)
20. [📝팀원별 회고록 및 트러블슈팅](#팀원별-회고록-및-트러블슈팅)

---

<a id="팀원-소개"></a>
## 👥팀원 소개

<div align="center">

<table align="center">
  <tr>
    <td align="center" width="180">
      <img src="./이미지/깃허브_사진/cat1.jpg" width="160" height="160" style="object-fit:cover; border-radius:14px; display:block; margin:0 auto;" alt="조장:김가영" />
      <br />
      <b>조장:김가영</b>
      <br />
      <a href="https://github.com/ZonezIpex">
        <img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GITHUB" />
      </a>
    </td>

  <td align="center" width="180">
      <img src="./이미지/깃허브_사진/cat2.jpg" width="160" height="160" style="object-fit:cover; border-radius:14px; display:block; margin:0 auto;" alt="김다솜" />
      <br />
      <b>김다솜</b>
      <br />
      <a href="https://github.com/ZonezIpex">
        <img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GITHUB" />
      </a>
    </td>

  <td align="center" width="180">
      <img src="./이미지/깃허브_사진/cat3.jpg" width="160" height="160" style="object-fit:cover; border-radius:14px; display:block; margin:0 auto;" alt="김승욱" />
      <br />
      <b>김승욱</b>
      <br />
      <a href="https://github.com/ZonezIpex">
        <img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GITHUB" />
      </a>
    </td>

  <td align="center" width="180">
      <img src="./이미지/깃허브_사진/cat4.jpg" width="160" height="160" style="object-fit:cover; border-radius:14px; display:block; margin:0 auto;" alt="김정수" />
      <br />
      <b>김정수</b>
      <br />
      <a href="https://github.com/ZonezIpex">
        <img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GITHUB" />
      </a>
    </td>

  <td align="center" width="180">
      <img src="./이미지/깃허브_사진/cat5.jpg" width="160" height="160" style="object-fit:cover; border-radius:14px; display:block; margin:0 auto;" alt="신민수" />
      <br />
      <b>신민수</b>
      <br />
      <a href="https://github.com/ZonezIpex">
        <img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GITHUB" />
      </a>
    </td>

  <td align="center" width="180">
      <img src="./이미지/깃허브_사진/cat6.jpg" width="160" height="160" style="object-fit:cover; border-radius:14px; display:block; margin:0 auto;" alt="이서윤" />
      <br />
      <b>이서윤</b>
      <br />
      <a href="https://github.com/ZonezIpex">
        <img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GITHUB" />
      </a>
    </td>
  </tr>
</table>

</div>


---

<a id="프로젝트-개요-project-overview"></a>
## 📌프로젝트 개요 (Project Overview)

- **서비스 명칭:** Subees  
- **한 줄 소개:** <!-- TODO: 예) 분산된 구독 결제/해지/알림을 한 곳에서 관리하는 통합 구독 관리 서비스 -->

> <!-- TODO: 프로젝트 개요(문제정의/핵심가치/대상 사용자)를 3~5줄로 작성 -->

---

<a id="프로젝트-선정-이유-및-기대-효과"></a>
## 🧠프로젝트 선정 이유 및 기대 효과

- **선정 이유**
  - <!-- TODO: 구독이 여러 서비스로 분산되어 관리가 어려움 -->
  - <!-- TODO: 결제일/총액/해지 루트가 제각각이라 누락/과지출 발생 -->
- **기대 효과**
  - <!-- TODO: 월 지출 가시화, 결제일 알림, 해지 가이드 제공으로 절감 -->

---

<a id="사용자-시나리오-및-프로세스-맵"></a>
## 🗺️사용자 시나리오 및 프로세스 맵

- 시나리오 A: 회원가입/로그인 → 구독 등록 → 결제일 알림 수신 → 대시보드에서 월 지출 확인  
- 시나리오 B: 구독 해지 가이드 확인 → 해지 완료 체크 → 기록 보관  

<!-- TODO: 시나리오를 실제 서비스 플로우에 맞춰 2~3개로 정리 -->

### Process Map
<!-- TODO: 프로세스 맵 이미지 교체 -->
<div align="center">

<img src="./이미지/포스터/포스터예시.jpg" width="620" alt="Placeholder" />

</div>

---

<a id="기술-스택-tech-stack"></a>
## 🧰기술 스택 (Tech Stack)

<!-- TODO: 실제 사용 스택으로 수정 -->
| 분류 | 기술 |
|---|---|
| Framework | <!-- TODO: React / Next.js --> |
| Language | <!-- TODO: TypeScript --> |
| Styling | <!-- TODO: Tailwind CSS --> |
| State/Data | <!-- TODO: TanStack Query / Zustand / Redux --> |
| Build/Tooling | <!-- TODO: Vite / Next / ESLint / Prettier --> |
| Test | <!-- TODO: Vitest/Jest/Playwright/Cypress --> |
| Design | <!-- TODO: Figma --> |

---

<a id="framework--language"></a>
## 🧩Framework & Language

- Framework: <!-- TODO -->
- Language: <!-- TODO -->

---

<a id="상태-관리-및-통신-라이브러리"></a>
## 🔁상태 관리 및 통신 라이브러리

- 상태 관리: <!-- TODO -->
- 통신(HTTP): <!-- TODO -->
- 에러 처리 전략: <!-- TODO: 공통 에러 처리/재시도/토큰 만료 처리 -->

---

<a id="ui-라이브러리-및-디자인-도구"></a>
## 🎨UI 라이브러리 및 디자인 도구

- UI Library: <!-- TODO -->
- Design Tool: <!-- TODO -->

---

<a id="설계-및-구조-design--architecture"></a>
## 🏗️설계 및 구조 (Design & Architecture)

- 설계 원칙: <!-- TODO: Atomic/Feature-sliced/도메인 분리 등 -->

### Architecture Diagram
<!-- TODO: 아키텍처 다이어그램 이미지 교체 -->
<div align="center">

<img src="./이미지/포스터/포스터예시.jpg" width="620" alt="Placeholder" />

</div>

---

<a id="화면-및-기능-설계서-figma"></a>
## 🖼️화면 및 기능 설계서 (Figma)

🔗 <!-- TODO: Figma 상세 링크 붙여넣기 -->

---

<a id="유스케이스-다이어그램-use-case-diagram"></a>
## 🧩유스케이스 다이어그램 (Use Case Diagram)

<!-- TODO: 유스케이스 다이어그램 이미지 교체 -->
<div align="center">

<img src="./이미지/포스터/포스터예시.jpg" width="620" alt="Placeholder" />

</div>

---

<a id="컴포넌트-계층-구조-및-폴더-구조"></a>
## 🧱컴포넌트 계층 구조 및 폴더 구조

<!-- TODO: 실제 프로젝트 구조로 수정 -->
```txt
src/
  app/
  components/
  features/
  services/
  stores/
  hooks/
  styles/
  utils/
  types/
  assets/
```

---

<a id="단위-테스트-및-시연-uiux-unit-test"></a>
## 🧪단위 테스트 및 시연 (UI/UX Unit Test)

### Test Strategy
- 컴포넌트 단위: 렌더링/상태/인터랙션  
- 페이지 단위: 주요 플로우(로그인→등록→알림)  
- 회귀 테스트: 핵심 기능 우선  

### Test Commands
```bash
# TODO: 실제 명령어로 교체
pnpm test
pnpm e2e
```

---

<a id="기능별-시연-gif"></a>
## 🎞️기능별 시연 GIF

<!-- TODO: GIF로 교체 (현재는 깨짐 방지를 위해 이미지로 자리만 잡음) -->
<div align="center">

<img src="./이미지/포스터/포스터예시.jpg" width="620" alt="Placeholder" />

</div>

---

<a id="uiux-단위-테스트-결과서-spreadsheet"></a>
## 📊UI/UX 단위 테스트 결과서 (Spreadsheet 링크)

🔗 <!-- TODO: 테스트 결과서 스프레드시트 링크 -->

<!-- TODO: 결과서 캡처 이미지 교체 -->
<div align="center">

<img src="./이미지/포스터/포스터예시.jpg" width="620" alt="Placeholder" />

</div>

---

<a id="브라우저-호환성-및-반응형-대응-현황"></a>
## 🧭브라우저 호환성 및 반응형 대응 현황

| Browser | Status | Note |
|---|---|---|
| Chrome | ✅ |  |
| Edge | ✅ |  |
| Safari | ⬜ | <!-- TODO --> |
| Firefox | ⬜ | <!-- TODO --> |

- Desktop: ✅
- Tablet: ⬜ <!-- TODO -->
- Mobile: ⬜ <!-- TODO -->

---

<a id="개발-관리-및-회고-project-management"></a>
## 📌개발 관리 및 회고 (Project Management)

- 이슈/태스크 관리: <!-- TODO -->
- 브랜치 전략: <!-- TODO -->
- PR 규칙: <!-- TODO -->
- 회고 방식: <!-- TODO -->

---

<a id="wbs-기반-일정-관리-현황"></a>
## 📅WBS 기반 일정 관리 현황

🔗 <!-- TODO: WBS 링크 -->

<!-- TODO: WBS 캡처 이미지 교체 -->
<div align="center">

<img src="./이미지/포스터/포스터예시.jpg" width="620" alt="Placeholder" />

</div>

---

<a id="향후-개선-및-확장-방안"></a>
## 🚀향후 개선 및 확장 방안

- 성능 최적화: <!-- TODO -->
- 신규 기능: <!-- TODO -->
- 품질/접근성: <!-- TODO -->

---

<a id="팀원별-회고록-및-트러블슈팅"></a>
## 📝팀원별 회고록 및 트러블슈팅

### 팀원별 회고
| 이름 | 회고 |
|---|---|
| 김가영 | <!-- TODO --> |
| 김다솜 | <!-- TODO --> |
| 김승욱 | <!-- TODO --> |
| 김정수 | <!-- TODO --> |
| 신민수 | <!-- TODO --> |
| 이서윤 | <!-- TODO --> |

### Troubleshooting
| 문제 | 원인 | 해결 | 참고 |
|---|---|---|---|
| <!-- TODO --> | <!-- TODO --> | <!-- TODO --> | <!-- TODO: 링크/이슈번호 --> |

---
