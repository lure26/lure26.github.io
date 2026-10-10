# 🌐 AI English Dictionary & Translator (Gemini Lexicon)

Google Gemini AI 기반의 실시간 영어 사전 및 맞춤형 문장 번역 웹 애플리케이션입니다.
GitHub Pages를 통해 간편하게 무료 호스팅 및 배포할 수 있습니다.

## ✨ 주요 기능

1. **스마트 단어 심층 분석**: 영단어 입력 시 발음 기호, 품사, 간결한 영영풀이, 한국어 주요 뜻, 유의어/반의어, 원어민 예문 제공.
2. **구문 및 문장 자연스러운 번역**: 문장 입력 시 직역 대신 상황에 맞는 한국어 매칭, 뉘앙스/맥락 해설, 핵심 관용구/표현 분석.
3. **음성 인식 (STT) & 발음 읽기 (TTS)**: 마이크 버튼으로 영어 음성 입력 지원 및 원어민 음성 듣기 기능.
4. **검색 기록 & 북마크 기능**: 최근 검색한 단어/문장 자동 저장 및 북마크 리스트 관리.
5. **다크 모드 지원**: 사용자 시스템 및 선호도에 맞춘 다크/라이트 테마 지원.

## 🚀 GitHub Pages 배포 및 `https://lure26.github.io/` 연결 방법

### 1단계: Repository(저장소) 설정 확인
`https://lure26.github.io/` 메인 주소로 바로 웹사이트가 나오게 하려면 **저장소 이름이 정확히 `lure26.github.io`** 이어야 합니다.

* **사례 A**: Repository 이름이 `lure26.github.io` 인 경우 ➡️ 주소: `https://lure26.github.io/`
* **사례 B**: Repository 이름이 `english-dict` 인 경우 ➡️ 주소: `https://lure26.github.io/english-dict/`

### 2단계: 파일 업로드
GitHub 저장소 메인 화면에 다음 두 파일이 있는지 확인하세요.
* `index.html` (반드시 소문자 `index.html`로 폴더 최상단에 위치)
* `README.md`

### 3단계: GitHub Pages 기능 활성화
1. 해당 GitHub 저장소 페이지 상단의 **`Settings`** 클릭.
2. 좌측 메뉴에서 **`Pages`** 클릭.
3. **Build and deployment** 항목의 Source에서 `Deploy from a branch` 선택.
4. Branch를 **`main`** (또는 `master`) / **`/(root)`** 로 선택 후 **`Save`** 클릭.
5. 약 1~3분 후 상단에 `"Your site is live at ..."` 안내가 나오면 배포 완료!

## 🔑 Gemini API Key 발급 및 설정 방법

1. [Google AI Studio](https://aistudio.google.com/) 접속
2. **`Get API key`** 클릭 후 무료 API 키 생성 및 복사
3. 웹사이트 우측 상단 톱니바퀴(**설정**) 아이콘을 클릭하여 API Key 등록