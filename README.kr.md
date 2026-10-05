# Awesome Single-File Tools [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa20e105be61d1284d73385f/badge.svg)](https://github.com/sindresorhus/awesome)

[English](README.md) | [한국어](README.kr.md)

> 디지털 주권, 완벽한 개인정보 보호, 최상의 휴대성을 위해 설계된 무의존성(Zero-Dependency), 로컬 퍼스트(Local-First), 단일 파일 HTML 도구 및 프레임워크 큐레이션 리스트입니다.

단일 파일 HTML 도구는 현대적 웹 브라우저만 있다면 별도의 서버 설정, `npm install`, 복잡한 빌드 파이프라인이나 백그라운드 데이터 수집(Telemetry) 없이 완벽하게 동작합니다. 파일 더블클릭 하나만으로 코드를 직접 검토하고 수정하며, 여러분의 소프트웨어와 데이터에 대한 완전한 소유권을 유지하세요.

---

## 📜 선언문 및 철학 (Manifesto & Philosophy)

- **로컬 퍼스트 & 완전한 오프라인 지원 (Local-First & Offline-Ready)**: 모든 데이터는 사용자의 물리적 기기에만 남습니다. 숨겨진 네트워크 요청은 존재하지 않습니다.
- **외부 의존성 제로 (Zero External Dependencies)**: 필요한 모든 핵심 요소(HTML, CSS, JavaScript)가 오직 하나의 단일 파일 안에 존재합니다.
- **지적 자치권 (Intellectual Sovereignty)**: 사용자가 직접 코드를 검사하고, 수정하며, 포크(Fork)하여 영구히 보존할 수 있는 순수한 형태의 소프트웨어를 지향합니다.
- **시민 개발자 친화적 (Citizen Developer Friendly)**: 표준 텍스트 에디터만으로도 누구나 자유롭게 가공하고 커스텀할 수 있는 가독성 높은 코드로 구성됩니다.

🌐 *[크리스탈 월드 프로젝트 홈페이지](https://crystal-world-project.github.io/crystal-world/index.html)에서 전체 생태계 쇼케이스를 경험해 보세요.*

---

## 📑 목차 (Table of Contents)

- [🌟 핵심 앵커 프로젝트 (Featured Anchor Project)](#-핵심-앵커-프로젝트-featured-anchor-project)
- [🧠 지식 관리 & PKM (Knowledge Management & PKM)](#-지식-관리--pkm-knowledge-management--pkm)
- [🛠️ 유틸리티 & 생산성 (Utilities & Productivity)](#️-유틸리티--생산성-utilities--productivity)
- [🎨 미디어, 그래픽 & 창작 (Media, Graphics & Creation)](#-미디어-그래픽--창작-media-graphics--creation)
- [💻 개발자 도구 & API 클라이언트 (Developer Tools & API Clients)](#-개발자-도구--api-클라이언트-developer-tools--api-clients)
- [🤝 기여 가이드라인 (Contribution Guidelines)](#-기여-가이드라인-contribution-guidelines)
- [📄 라이선스 (License)](#-라이선스-license)

---

## 🌟 핵심 앵커 프로젝트 (Featured Anchor Project)

### 🧸 [Teddy Wiki Lite](https://crystal-world-project.github.io/crystal-world/teddy-wiki-lite.html) `v1.3`
TiddlyWiki에서 영감을 받은 초경량, 무의존성, 단일 파일 HTML 개인 위키 및 지식 관리 도구입니다.
- **주요 특징**:
  - 다중 태그 기반 AND 쿼리 필터링 엔진 내장 (`Array.every`).
  - 편집 및 마크다운 미리보기가 매끄럽게 연결되는 인터페이스.
  - `postMessage` 기반의 안전한 교차 iframe 통신 프로토콜 지원.
  - 다차원 지식 매트릭스 결합을 위한 자체 완비형 JSON 저장 구조.
- **운영 조직**: [crystal-world-project](https://github.com/crystal-world-project)

---

## 🧠 지식 관리 & PKM (Knowledge Management & PKM)

- **[TiddlyWiki Classic / Standalone](https://tiddlywiki.com/)** - 비선형 개인 웹 노트이자 단일 파일 웹 앱 패러다임을 개척한 전설적인 단일 파일 위키.
- **[Teddy Wiki](https://crystal-world-project.github.io/crystal-world/index.html)** - 단일 파일 HTML 기반 인메모리 개인 지식 베이스 및 위키 시스템.
- **[Teddy Wiki Lite](https://crystal-world-project.github.io/crystal-world/teddy-wiki-lite.html)** - 다중 태그 쿼리 기능을 탑재한 초경량 단일 파일 마크다운 위키.
- **[Three Shifts, Six Inversions — Knowledge Graph](https://0603wangxiao.github.io/36wx/kg/)** - 주역과 동양 철학적 프레임워크(삼변육반)를 단일 HTML 캔버스로 시각화한 386 KB 지식 그래프 *(중국어 / 인터랙티브 동양 철학 프레임워크)*. 노드 확대·축소·이동 및 클릭을 통해 정의와 출처 확인 가능. 외부 요청 없음 — 100% 오프라인 작동.
- *(단일 파일 기반 아웃라이너, 저널링 템플릿, 플래시카드 도구 제보를 환영합니다)*

---

## 🛠️ 유틸리티 & 생산성 (Utilities & Productivity)

- *(단일 파일 칸반 보드)*
- *(로컬 뽀모도로 타이머 & 습관 트래커)*
- *(오프라인 계산기 & 의사결정 매트릭스 엔진)*

---

## 🎨 미디어, 그래픽 & 창작 (Media, Graphics & Creation)

- **[Bento Slides](https://bento.page/)** - 하나의 HTML 파일 안에 슬라이드 데크, 에디터, 발표자 모드, 대화형 차트까지 모두 담아낸 오픈소스 로컬 퍼스트 프레젠테이션 도구.
- **[Nano Blake](https://crystal-world-project.github.io/crystal-world/index.html)** - 부드러운 Ken Burns 애니메이션 효과와 Web Speech API 음성 합성을 지원하는 단일 파일 슬라이드쇼 & 비디오 메모 엔진.
- *(단일 파일 SVG/Canvas 드로잉 캔버스 & 이미지 에디터)*

---

## 💻 개발자 도구 & API 클라이언트 (Developer Tools & API Clients)

- **[Crystal Dock](https://crystal-world-project.github.io/crystal-world/index.html)** - iframe 샌드박싱과 `postMessage` 프로토콜을 활용하여 빌드 과정 없이 격리된 웹 도구들을 연결하는 초경량 단일 파일 모듈러 메타 플랫폼.
- *(브라우저 내 정규식 테스트 도구 & HTML 샌드박스)*
- *(단일 파일 REST API 클라이언트 & GitHub API GUI 관리자)*
- *(JSON 포맷터 & 오프라인 Base64 / 토큰 인코더)*

---

## 🤝 기여 가이드라인 (Contribution Guidelines)

뛰어난 단일 파일 도구 및 애플리케이션의 추천과 기여를 언제나 환영합니다! 프로젝트가 등재되기 위해서는 다음 기준을 충족해야 합니다:

1. **단일 파일 구조**: 전체 애플리케이션 로직(HTML, CSS, JavaScript)이 반드시 단 하나의 독립된 `.html` 파일 안에 위치해야 합니다.
2. **로컬 퍼스트 (Local-First)**: 외부 서버나 API 없이 오프라인 환경에서도 핵심 기능이 완벽하게 작동해야 합니다 (사용자가 직접 설정한 토큰 연동 제외).
3. **핵심 CDN 의존성 제로**: 오프라인 동작을 저해하는 동적 외부 스크립트 로딩이 없어야 합니다.
4. **데이터 프라이버시**: 백그라운드 분석, 추적 코드 또는 데이터 수집(Telemetry)이 일체 없어야 합니다.

### 등재 신청 양식 (Submission Format)

> `- **[도구 이름](https://링크-주소)** - 목적과 핵심 기능을 설명하는 명확한 한 문장 요약.`

---

## 📄 라이선스 (License)

본 프로젝트는 MIT 라이선스에 따라 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참고하세요.  
**[Crystal World Project](https://github.com/crystal-world-project)**에서 열정을 담아 만들고 유지관리합니다.
