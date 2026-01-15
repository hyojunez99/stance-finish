# [프로젝트 이름]

> "Run Your Pace" 나만의 페이스로 달리는 러너를 위한 니치 쇼핑몰

## 1. 프로젝트 소개

- **설명:** 기획부터 디자인, 개발까지 직접 참여하였으며, **Mock Data(JSON)**를 활용해 실제 커머스 로직을 구현한 SPA 쇼핑몰 프로젝트입니다.
- **진행 기간:** 2025.12.19 ~ 2025.12.29 (9일)
- **개발 인원:** FrontEnd 5인 (Team Project)
- **배포 링크:** [https://hyojunez99.github.io/stance-finish/]

## 2. 사용 기술 스택 (Tech Stack)

- **Language:** JavaScript (ES6+)
- **Framework:** React.js
- **Styling:** SCSS
- **Data Handling:** Custom Mock Data (JSON)
- **Design & Tool:** **Figma**, Git, GitHub, GSAP

## 3. 기획 및 디자인 (Planning & Design)

- **Tool:** Figma
- **Concept:** 사용자 직관성을 고려한 UI/UX 설계 및 와이어프레임 제작

## 4. 디렉토리 구조

```text
src
│
├── assets # 이미지, 폰트 및 JSON 데이터
│ │
│ ├── data # 화면에 쓰이는 고정 데이터 관리
│ │
│ ├── images # 이미지 파일 보관
│ │
│ └── scss # 공통으로 쓰이는 폰토, 색상, 반응형 관리 폴더
│
├── components # 각 페이지와 공통 영역을 구성하는 컴포넌트를 관리 폴더
│ │
│ ├── common # 여러 페이지에서 공통으로 재사용되는 컴포넌트
│ │
│ ├── detail # 상품 상세 페이지 전용 컴포넌트 폴더
│ │
│ └── main # 메인 페이지(홈) 전용 컴포넌트 폴더
│
├── layout # 공통 레이아웃 구조 (Header, Footer )
│  
└── pages # 라우팅 페이지 (Cart, Detail, Main...)

## 5. 담당 역할

[데이터/이미지 및 메인 페이지 제작, 장바구니 와이어프레임 제작]

- Figma를 활용한 장바구니페이지 와이어프레임 제작
- 상품 및 뉴스 데이터 JSON으로 관리, 이미지 파일 정리
- GSAP 및 ScrollTrigger 활용한 스크롤 애니메이션 적용
- React와 SCSS 구현

[개발: 기능]

-

## 6. 주요 기능

- CategorySection - 메인 페이지 러닝 뉴스 섹션

* RunnigNews.json 데이터 기반 뉴스 카드 렌더링
* GSAP ScrollTrigger 적용, 스크롤 시 애니메이션

- ProductSection - 메인 페이지 베스트셀러 상품 섹션

* Item.json 데이터 기반 “best” 카테고리 상품 렌더링
* 슬라이드 기능: 이전/다음 버튼
* GSAP ScrollTrigger 적용, 스크롤 시 애니메이션
* 할인율 계산 및 가격 표시

- ProductSection2 - 메인 페이지 MD 추천(PACEY PICK) 상품 섹션

* Item.json 데이터 기반 “pick” 카테고리 상품 렌더링
* 상품 클릭 시 상세 페이지 이동 (id 포함 URL)
* GSAP ScrollTrigger 적용, 스크롤 시 애니메이션
* 할인율 계산 및 가격 표시

- MidBlog - 이벤트/프로모션 배너 섹션

* 이벤트 이미지와 텍스트 렌더링

- BottomBlog - 메인 페이지 하단 트렌드 키워드 섹션

* Keyword.json 데이터 기반 키워드 이미지 및 제목 렌더링
* 무한 스크롤 형태로 키워드 반복 노출

- 데이터/이미지 관리

* JSON 데이터 사이트 콘텐츠 관리
* Item.json, Keyword.json, RunnigNews.json 등
* 상품, 키워드, 뉴스 카드 데이터 관리
* 컴포넌트 렌더링에 활용

## 7. 트러블 슈팅

문제 1. 디자인–데이터 흐름 불일치

상황: 디자인 시안 기준으로 UI를 먼저 구현하면서, 실제 사용되는 데이터 구조와 맞지 않아 화면 수정이 반복적으로 발생함

원인: 디자인과 데이터 흐름에 대한 사전 소통 없이 파트별 개발이 진행됨

해결: 팀원들과 각 섹션에서 사용하는 데이터 구조와 컴포넌트 역할을 정리하고 공통 기준을 수립

과정: 디자인 시안을 다시 검토하며 JSON 데이터 구조를 먼저 확정한 뒤 UI를 이에 맞게 수정

## 8. 실행 화면

(구현한 화면 스크린샷 1장 첨부)

```