# 두링 (Doo-Ring)

> 연인들을 위한 미션 기반 기록 서비스  
> **사진**, **채팅**, **소감 작성**으로 함께한 순간을 앱 안에서 추억하세요.

---

## 🧩 프로젝트 구성

두링은 아래의 주요 컴포넌트로 구성된 서비스입니다:

| Repository | 설명 |
|------------|------|
| [`dooring-mobile-rn`](https://github.com/Doo-Ring/dooring-mobile-rn) | React Native 기반 메인 앱 |
| [`dooring-modile-webview`](https://github.com/Doo-Ring/dooring-modile-webview) | 앱 내부에서 띄워지는 WebView 콘텐츠 |
| [`dooring-api-server`](https://github.com/Doo-Ring/dooring-api-server) | Django 기반의 API 서버 |
| [`dooring-mobile-app`](https://github.com/Doo-Ring/dooring-mobile-app) | **레거시 앱 (보존용)** – 초기 버전 |

---

## 🧱 기술 스택

- **Frontend**
  - React Native (Expo)
  - React + Vite + TailwindCSS (WebView)
- **Backend**
  - Django REST Framework
- **Infra**
  - Docker / Nginx
  - MySQL
  - S3 / MinIO (for image storage)

---

## 🚀 서비스 기능 요약

- 커플 미션 생성 및 인증
- 사진 업로드 및 기록
- 채팅 및 소감 남기기
- 웹뷰 기반의 미션 상세 UI

---

## 🛠️ 사용법 및 개발 가이드

각 리포지토리별 README에서 확인할 수 있습니다.