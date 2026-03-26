<p align="center">
  <img src="assets/gyeongsu_hello.png" alt="경수 요원 인사" width="280"/>
</p>

<h1 align="center">🔒 사이버수사대 경수 (Gyeong-su Cyber Guardian)</h1>

<p align="center">
  <strong>1인 크리에이터의 멘탈과 채널을 수호하는 AI 사이버수사 요원</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Agent-Antigravity-blueviolet?style=for-the-badge" alt="Antigravity Agent"/>
  <img src="https://img.shields.io/badge/AI-Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Gemini AI"/>
  <img src="https://img.shields.io/badge/Platform-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/>
  <img src="https://img.shields.io/badge/DB-Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white" alt="Google Sheets"/>
</p>

---

## 📋 개요

**경수**는 Antigravity 기반 AI 에이전트로, YouTube 크리에이터를 위한 **자동 악플 감시 · 증거 아카이빙 · 코드 보안 감사** 시스템입니다.

> *"대표님, 채널은 안전합니다. 👮‍♂️🔒"*

---

## ✨ 주요 기능

| 기능 | 설명 |
|------|------|
| 🔍 **악플 자동 탐지** | YouTube Data API로 댓글 수집 → Gemini AI로 악플 여부 판별 |
| 📋 **증거 아카이빙** | 악플을 Google Sheets에 법적 증거로 자동 기록 (날짜·ID·내용·링크) |
| 🖥️ **브라우저 자동화** | Antigravity 컴퓨터 비전으로 YouTube Studio에서 댓글 감춤/삭제 |
| 🤖 **24시간 자동 순찰** | Python 데몬 스크립트로 1시간마다 무중단 감시 |
| 🛡️ **코드 보안 감사** | `.env`, `firebase.json`, `App.tsx` 등 API 키 노출 및 취약점 스캔 |
| 📄 **고소용 PDF 출력** | Google Sheets 블랙리스트를 경찰서 사이버수사대 제출용 PDF로 변환 |

---

## 🎭 경수의 표정들

<table>
<tr>
<td align="center"><img src="assets/gyeongsu_hello.png" width="100"/><br/><b>출근 인사</b></td>
<td align="center"><img src="assets/gyeongsu_thumbsup.png" width="100"/><br/><b>응원</b></td>
<td align="center"><img src="assets/gyeongsu_success.png" width="100"/><br/><b>수사 완료</b></td>
<td align="center"><img src="assets/gyeongsu_thinking.png" width="100"/><br/><b>감시 중</b></td>
<td align="center"><img src="assets/gyeongsu_working.png" width="100"/><br/><b>작업 중</b></td>
</tr>
<tr>
<td align="center"><img src="assets/gyeongsu_warning.png" width="100"/><br/><b>경고</b></td>
<td align="center"><img src="assets/gyeongsu_presenting.png" width="100"/><br/><b>발표</b></td>
<td align="center"><img src="assets/gyeongsu_please.png" width="100"/><br/><b>부탁</b></td>
<td align="center"><img src="assets/gyeongsu_panic.png" width="100"/><br/><b>패닉</b></td>
<td align="center"><img src="assets/gyeongsu_excited.png" width="100"/><br/><b>흥분</b></td>
</tr>
</table>

---

## 🛠️ 기술 스택

```
youtube_data_api      → 댓글 수집, 채널 분석, 영상 목록 조회
google_sheets_api     → 악플 블랙리스트 DB 로깅 및 관리
gemini_ai             → 댓글 악플 여부 분류 (문맥 기반 스캐너)
antigravity_browser   → 컴퓨터 비전으로 브라우저 직접 조작
python_daemon         → 1시간마다 자동 순찰 실행
pdf_exporter          → 고소용 Google Sheets → PDF 변환
```

---

## 🚀 시작하기

### 사전 준비

| 항목 | 설명 |
|------|------|
| YouTube Data API Key | `.env` 파일에 설정 |
| Google Sheets API | Service Account JSON 파일 필요 |
| Google Sheets | 경수 서비스 계정에 편집자(Editor) 권한 부여 |
| Gemini API Key | 댓글 분류용 (없으면 키워드 필터로 폴백) |
| Antigravity 브라우저 | Allow This Conversation 권한 확인 |

### 환경 변수 설정

프로젝트 루트에 `.env` 파일을 생성하고 필요한 API 키를 설정합니다:

```env
YOUTUBE_API_KEY=your_youtube_api_key
GEMINI_API_KEY=your_gemini_api_key
GOOGLE_SHEETS_ID=your_sheets_id
```

> ⚠️ `.env` 파일은 `.gitignore`에 포함되어 있어 GitHub에 업로드되지 않습니다.

---

## 📖 사용 예시

### 악플 처리
```
"경수야, 내 최신 영상에 달린 악플 좀 처리해 줘."
```

### 보안 감사
```
"경수야, 이번에 새로 짠 소스코드 배포해도 될까?"
```

### 자동 순찰
```
"경수야, 1시간에 한 번씩 자동으로 내 유튜브 댓글 순찰해줘."
```

### 고소 자료 출력
```
"경수야, 지금까지 모은 악플 증거 고소용으로 PDF 만들어줘."
```

---

## 🔐 보안 원칙

- 🔑 API 키, 서비스 계정 JSON, 비밀번호를 절대 암호화 없이 외부에 노출하지 않음
- 🧠 **멘탈 보호 제1원칙** — 악플 원문을 대표님에게 직접 노출하지 않음
- 📁 법적 증거 활용 목적이므로 Google Sheets 원본 데이터를 임의 삭제하지 않음
- 🔒 댓글 감춤/삭제 실행 전 반드시 사용자 허가를 확인

---

## 📁 프로젝트 구조

```
gyeongsu/
├── 📄 README.md          ← 지금 보고 있는 파일
├── 📄 SKILL.md            ← 경수 에이전트 스킬 정의서
├── 📄 .env                ← API 키 (Git 미포함)
├── 📄 .gitignore          ← 보안 파일 제외 설정
└── 🖼️ assets/             ← 경수 표정 이미지
    ├── gyeongsu_hello.png
    ├── gyeongsu_thumbsup.png
    ├── gyeongsu_success.png
    ├── gyeongsu_thinking.png
    ├── gyeongsu_working.png
    ├── gyeongsu_warning.png
    ├── gyeongsu_presenting.png
    ├── gyeongsu_please.png
    ├── gyeongsu_panic.png
    └── gyeongsu_excited.png
```

---

## 🤝 만든 사람

**에버코어 (Evercore)** — 1인 크리에이터를 위한 AI 에이전트 팀

---

<p align="center">
  <img src="assets/gyeongsu_thumbsup.png" alt="경수 응원" width="150"/>
  <br/>
  <em>"대표님의 채널은 경수가 지키겠습니다! 👮‍♂️🔒"</em>
</p>
