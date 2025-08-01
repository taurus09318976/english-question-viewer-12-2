# 📚 #18차 2 English Question Viewer

중고등학생 영어문항 검토 시스템 - Quill.js Delta Format

## 🌟 기능

- **파일 브라우저**: 좌측 사이드바에서 JSON 파일 목록 확인
- **검색 기능**: 파일명으로 빠른 검색
- **3가지 보기 모드**:
  - 문항 보기: 구조화된 문항 표시
  - 원본 JSON: 원본 데이터 확인
  - HTML 렌더링: 웹 친화적 표시

## 🚀 사용 방법

1. 웹브라우저에서 `index.html` 파일을 열거나 GitHub Pages에서 접속
2. 좌측 파일 목록에서 원하는 JSON 파일 선택
3. 상단 탭을 통해 다양한 보기 모드 전환

## 📁 프로젝트 구조

```
/
├── index.html          # 메인 HTML 파일
├── viewer.js           # JavaScript 로직
├── README.md          # 프로젝트 설명
└── ENG_*.json         # 영어 문항 데이터 파일들 (96개)
```

## 📊 데이터 정보

- **총 파일 수**: 96개의 JSON 파일
- **데이터 형식**: Quill.js Delta Format
- **파일명 패턴**: ENG_[숫자ID].json

## 🌐 온라인 접속

GitHub Pages를 통해 온라인에서 접속할 수 있습니다.

## 💻 로컬 개발

로컬에서 실행하려면:

1. 이 저장소를 클론
2. 웹 서버를 통해 실행 (파일:// 프로토콜로는 CORS 문제로 인해 작동하지 않음)

```bash
# Python 3 내장 서버 사용 예시
python -m http.server 8000

# Node.js http-server 사용 예시
npx http-server
```

## 🔧 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Quill.js
- **스타일링**: CSS Grid, Flexbox
- **데이터 형식**: JSON

## 📄 라이선스

이 프로젝트는 교육 목적으로 제작되었습니다.

---

© 2024 English Question Viewer Project 