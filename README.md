# 안녕하세요, 김현진입니다

AI/LLM, Flutter, iOS, python, docker, gcp 기반 제품을 설계하고 구현하는 풀스택 엔지니어입니다.

사용자 문제를 AI 기술로 해결하는 서비스를 개발하고 있습니다.

📧 이메일: [bustina9@gmail.com](mailto:bustina9@gmail.com) / [hyunjin@koriai.com](mailto:hyunjin@koriai.com)

🏠 위치: 서울, 대한민국

## Contact
[![GitHub](https://img.shields.io/static/v1?style=for-the-badge&message=GitHub&color=181717&logo=GitHub&logoColor=FFFFFF&label=)](https://github.com/koriai)
[![LinkedIn](https://img.shields.io/static/v1?style=for-the-badge&message=LinkedIn&color=0A66C2&logo=LinkedIn&logoColor=FFFFFF&label=)](https://www.linkedin.com/in/khi999/)

## Skills

### AI / LLM
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-5A0FC8?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0wIDE4Yy00LjQxIDAtOC0zLjU5LTgtOHMzLjU5LTggOC04IDggMy41OSA4IDgtMy41OSA4LTggOHoiLz48L3N2Zz4=&logoColor=white)

- **LLM Integration**: OpenAI GPT, Claude API, Gemini API 연동 및 프롬프트 엔지니어링
- **MCP (Model Context Protocol)**: MCP 서버 설계 및 구현
- **On-Device AI**: Apple Intelligence (Foundation Models), Core ML
- **AI OCR**: 문서 분석 및 정보 추출 파이프라인 구축

### Mobile / Frontend
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=Flutter&logoColor=white)

- **iOS**: Swift, SwiftUI, MVVM, 클린 아키텍처, App Store 배포
- **Cross-Platform**: Flutter, Dart

### Backend / Cloud
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=Firebase&logoColor=black)

- **Backend**: Python, Django
- **Cloud**: Google Cloud Run, Firebase (Auth, Firestore, Functions, Hosting)
- **DevOps**: Docker, CI/CD

## 학력 & 경력
- 성균관대학교 학사: 2009–2015
- 삼성디스플레이: 2016–2017
- 성균관대학교 석사: 2018–2020
- Kori AI: 2020–현재
- BodyFriend: 2024–2025
- Apple Developer Academy @ POSTECH: 2025

---

## Projects

### 1) Nutrition MCP Server - 음식&가공식품 영양정보 MCP 서버

[![MCP](https://img.shields.io/badge/MCP-Server-5A0FC8?style=flat-square)](https://modelcontextprotocol.io)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-3178C6?style=flat-square)](https://www.typescriptlang.org/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=flat-square)](https://www.docker.com/)

- **목적**: 음식과 가공식품의 영양 정보를 자연어로 조회
- **사용 기술**: TypeScript, MCP SDK, SQLite, Docker, Google Cloud Run
- **주요 기능**
  - 14개 MCP 도구 설계 및 구현 (검색, 영양 계산, TDEE, 탄단지 비율 검색 등)
  - stdio/HTTP 듀얼 모드 지원
  - Cloud Run 원격 배포 + 로컬 프록시 아키텍처
- **AI 기술**: Model Context Protocol, LLM Tool Design, Prompt Engineering

[MCP Address](https://nutrition-mcp-service-kurmt635bq-du.a.run.app/mcp
)

---

### 2) 부메랑 - 부동산 계약 AI 분석 서비스

<p>
  <img src="./images/boomerang-1.png" alt="Boomerang Screenshot 1" height="240">
  <img src="./images/boomerang-2.png" alt="Boomerang Screenshot 2" height="240">
</p>

[![Download on the App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/app/id6754898424)

- **목적**: AI OCR로 부동산 계약서류를 분석하여 사용자 불안감 해소
- **사용 기술**: iOS, Swift, MVVM, AI OCR
- **주요 기능**
  - 계약서류 AI 기반 OCR 및 텍스트 추출
  - 추출 내용 기반 위험 요소 분석 및 안내
- **AI 기술**: Document AI, OCR Pipeline, 텍스트 분석

---

### 3) AAC 이으미 - On-Device AI 의사소통 보조 앱

<p>
  <img src="./images/AAC-1.png" alt="AAC Screenshot 1" height="240">
  <img src="./images/AAC-2.png" alt="AAC Screenshot 2" height="240">
</p>

[![Download on the App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/app/id6752591284)

- **목적**: 발화가 어려운 자폐성 장애인을 위한 AAC(보완대체의사소통) 앱
- **사용 기술**: iOS, Swift, MVVM, Apple Intelligence
- **주요 기능**
  - 사용자 맞춤 커스터마이징 CRUD
  - **On-Device AI(Apple Intelligence)** 기반 문맥 보조
  - 발화 내용 기반 **생성형 AI 일기** 자동 제작
- **AI 기술**: Apple Foundation Models, On-Device LLM, 생성형 AI

---

<details>
  <summary><b>기타 프로젝트</b></summary>

---

### 4) 지켜줄Cam - Gemini 기반 개인정보 보호 카메라

<p>
  <img src="./images/privacycam-1.png" alt="PrivacyCam Screenshot 1" height="420">
  <img src="./images/privacycam-2.png" alt="PrivacyCam Screenshot 2" height="420">
</p>

[![Download on the App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/app/id6752826136)

<a href="https://play.google.com/store/apps/details?id=com.koriai.jiwoocam">
  <img src="https://play.google.com/intl/ko/badges/static/images/badges/ko_badge_web_generic.png" alt="Google Play에서 다운로드" width="120"/>
</a>

- **목적**: 원클릭으로 개인정보(얼굴, 차량번호 등)를 자동 검출 및 블러 처리
- **사용 기술**: iOS, Swift, MVVM, Gemini API
- **백엔드**: Firebase Cloud Run + Python Django (Gemini 호출 서버)
- **AI 기술**: Gemini Vision API, 이미지 분석, Object Detection

---

### 5) TarotMe - Apple Intelligence 타로 앱 (iOS 26 출시 예정)

<p>
  <img src="./images/tarot-2.png" alt="TarotMe Screenshot 2" height="420">
  <img src="./images/tarot-1.png" alt="TarotMe Screenshot 1" height="420">
</p>

- **목적**: 속마음을 표현하기 어려운 사용자를 위한 AI 타로 해석 앱
- **사용 기술**: iOS, Swift, MVVM, Apple Intelligence, GPT API
- **출시 예정**: iOS 26 정식 출시일
- **AI 기술**: Apple Foundation Models, GPT 연동, 클린 아키텍처 기반 멀티 LLM 지원

---

### 6) SR-report - 반도체 불량 분석 웹 서비스
[웹 서비스 바로가기](https://app.koriai.com)

<p>
  <img src="./images/srreport-3.png" alt="SR-report Screenshot" height="360">
</p>

<details>
<summary><b>더 많은 스크린샷 보기</b></summary>
<p>
  <img src="./images/srreport-1.png" alt="SR-report 1" height="200">
  <img src="./images/srreport-2.png" alt="SR-report 2" height="200">
  <img src="./images/srreport-4.png" alt="SR-report 4" height="200">
  <img src="./images/srreport-5.png" alt="SR-report 5" height="200">
  <img src="./images/srreport-6.png" alt="SR-report 6" height="200">
  <img src="./images/srreport-7.png" alt="SR-report 7" height="200">
</p>
</details>

<a href="https://play.google.com/store/apps/details?id=com.koriai.report">
  <img src="https://play.google.com/intl/ko/badges/static/images/badges/ko_badge_web_generic.png" alt="Google Play에서 다운로드" width="120"/>
</a>

- **프론트엔드**: Flutter
- **백엔드**: Python, Django, Docker
- **클라우드**: Google Cloud, Firebase

---

### 7) Total War: WARHAMMER III Roster Simulator
[웹 서비스 바로가기](https://ttw-roster.web.app)

<p>
  <img src="./images/ttw-3.png" alt="TTW Roster Simulator" height="360">
</p>

<details>
<summary><b>더 많은 스크린샷 보기</b></summary>
<p>
  <img src="./images/ttw-1.png" alt="TTW 1" height="200">
  <img src="./images/ttw-2.png" alt="TTW 2" height="200">
  <img src="./images/ttw-4.png" alt="TTW 4" height="200">
</p>
</details>

- **프론트엔드**: Flutter
- **백엔드**: Python
- **클라우드**: Google Cloud, Firebase Hosting

---

### 8) Clips Viewer
[웹 서비스 바로가기](https://clips-u.web.app)

<p float="left">
  <img src="./images/clips-1.png" alt="Clips Viewer Mobile" width="100" height="380">
  <img src="./images/clips-2.png" alt="Clips Viewer Desktop" width="340" height="380">
</p>

- **목적**: 유튜브 클립 모아보기
- **프론트엔드**: Flutter
- **클라우드**: Firebase (Hosting, Firestore)

</details>
