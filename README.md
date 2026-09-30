# I AM — 김수현 포트폴리오 웹사이트

SSAFY 16기 교육생 김수현의 개인 소개 및 포트폴리오 웹사이트입니다.  
별도의 복잡한 빌드 과정이나 프레임워크 없이, 순수 웹 표준 기술을 활용해 브라우저에서 가볍고 빠르게 동작하도록 제작되었습니다.

---

## 📌 주요 기능

- **다크 모드 (Dark Mode)**
  - 라이트 / 다크 테마 전환 지원
  - 사용자의 테마 선택 상태를 `localStorage`에 저장하여 유지 및 시스템 기본 테마 연동
- **다국어 지원 (i18n)**
  - 한국어(KO) 및 영어(EN) 실시간 언어 전환
  - 데이터 속성(`data-ko`, `data-en`)을 통한 텍스트 동적 변경
- **로컬 방명록 (Guestbook)**
  - `localStorage`를 활용하여 서버 없이 브라우저 내에서 방명록 작성 및 목록 확인
- **인터랙션 & 반응형 UI**
  - Tailwind CSS 기반 반응형 레이아웃 (모바일 / 태블릿 / 데스크톱)
  - 상단 스크롤 진행률 표시 바
  - `IntersectionObserver`를 활용한 섹션 진입 페이드인 애니메이션

---

## 📂 페이지 구성

| 페이지 | 파일명 | 설명 |
| :--- | :--- | :--- |
| **홈** | `index.html` | 메인 인트로 및 소개 요약 |
| **소개** | `about.html` | 프로필, 인적사항, 성향 및 연락처 |
| **교육** | `education.html` | SSAFY 활동, 학력, 해외개척프로그램(GPP), 봉사캠프 등 |
| **경험** | `experience.html` | 선거캠프, 카페, 교내 근로 등 다양한 아르바이트 및 활동 경험 |
| **취미** | `hobbies.html` | 영화 감상, 러닝, 독서 등 관심사 소개 |
| **방명록** | `guestbook.html` | 방문자 응원 메시지 작성 및 확인 공간 |

---

## 🛠 기술 스택

- **Markup & Styling**: HTML5, [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **Language**: Vanilla JavaScript (ES6+)
- **Storage**: Web Storage API (`localStorage`)
- **Typography**: [Pretendard](https://github.com/orioncactus/pretendard)

---

## 🚀 실행 방법

별도의 패키지 설치나 빌드 과정이 필요하지 않습니다.

1. 저장소를 클론하거나 다운로드합니다.
2. `index.html` 파일을 브라우저(Chrome, Edge, Safari 등)에서 직접 열거나, VS Code의 **Live Server** 확장 프로그램을 사용하여 실행합니다.
