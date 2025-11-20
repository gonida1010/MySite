# 🌌 Gon's Portfolio Website

> **"우주에서 가장 뛰어난 강아지"**
>
> 반응형 디자인과 동적인 인터랙션이 포함된 개인 포트폴리오 웹사이트입니다.

## 📖 프로젝트 소개 (About Project)

HTML, CSS, Vanilla JavaScript를 사용하여 제작한 개인 포트폴리오 사이트입니다.
사용자가 저의 기술 스택(Skills), 프로젝트 경험(Work), 자격증(License) 등을 한눈에 파악할 수 있도록 구성하였습니다.
모바일 환경에서도 최적화된 **반응형 디자인**을 지원합니다.

### 🔗 배포 주소 (Deployment)
* **Website:** https://github.com/gonida1010
* **Tistory:** [https://pak1010pak.tistory.com/](https://pak1010pak.tistory.com/)

## ✨ 주요 기능 (Key Features)

1.  **동적 인삿말 & 실시간 시계 (Dynamic Greeting & Clock)**
    * 사용자의 접속 시간에 따라 (아침, 오후, 저녁) 상단 로고 옆의 인삿말이 자동으로 변경됩니다.
    * `setInterval`을 활용하여 실시간으로 현재 시간을 초 단위까지 표시합니다.

2.  **프로젝트 필터링 (Project Filtering)**
    * `Front-end`, `Mobile`, `Back-end` 버튼을 클릭하여 카테고리별로 프로젝트를 필터링하여 볼 수 있습니다.
    * `data-filter` 및 `data-category` 속성을 활용하여 JavaScript로 구현하였습니다.

3.  **반응형 네비게이션 바 (Responsive Navbar)**
    * 모바일 화면(768px 이하)에서는 햄버거 메뉴 버튼이 나타나며, 클릭 시 사이드 메뉴가 슬라이드 됩니다.
    * 스크롤 시 메뉴가 자동으로 닫히며, 특정 섹션으로 이동 시 해당 메뉴가 활성화(Active) 됩니다.

4.  **부드러운 스크롤 & Scroll to Top (Smooth Scroll)**
    * 내비게이션 클릭 시 해당 섹션으로 부드럽게 이동합니다.
    * 페이지 하단에 '위로 가기' 버튼을 배치하여 사용자 편의성을 높였습니다.

5.  **시각적 효과 (Visual Effects)**
    * **Text Shadow:** 타이틀 텍스트에 그림자 효과를 주어 가독성과 스타일을 살렸습니다.
    * **Hover Effect:** 버튼 및 프로젝트 카드에 마우스 오버 시 애니메이션 효과가 적용됩니다.

## 🛠 기술 스택 (Tech Stack)

<div align=left>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/FontAwesome-528DD7?style=flat-square&logo=fontawesome&logoColor=white"/>
</div>

## 📂 폴더 구조 (Directory Structure)

```bash
📦 MySite
 ┣ 📂 css
 ┃ ┣ 📜 style.css        # 전체적인 스타일링 및 레이아웃
 ┃ ┗ 📜 media_style.css  # 반응형(모바일) 디자인 처리
 ┣ 📂 images             # 프로필, 배경, 프로젝트 이미지 등
 ┃ ┣ 📜 dog_1.jpg
 ┃ ┗ ...
 ┣ 📜 index.html         # 메인 HTML 구조 및 JS 로직 포함
 ┗ 📜 README.md          # 프로젝트 설명 파일
