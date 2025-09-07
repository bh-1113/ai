# AI 활용 가이드 (정적 사이트)
이 저장소는 GitHub Pages로 공개할 수 있는 간단한 정적 웹사이트 예시입니다.

## 파일 구성
- `index.html` — 메인 페이지
- `writing.html` — ChatGPT 글쓰기 사용법 (외부 이미지 URL로 스크린샷 표시)
- `images.html` — 이미지 생성 소개
- `speech.html` — 음성 인식 소개
- `data.html` — 데이터 분석 소개
- `chatbot.html` — 챗봇 소개
- `report.html` — 보고서 자동 생성 안내

## 공개 방법 (GitHub Pages)
1. 이 파일들을 저장소 루트에 업로드합니다.
2. GitHub 저장소 → **Settings** → **Pages** → **Source: Deploy from a branch**
3. Branch는 `main`, 폴더는 `/root`(또는 `/docs`에 둘 경우 `/docs`) 설정 후 Save
4. 잠시 후 표시되는 URL로 접속합니다. 예: `https://<사용자명>.github.io/<저장소명>/`

## 메모
- GitHub Pages는 **정적** 사이트이므로 서버 코드(Python 등)는 실행되지 않습니다.
- 버튼 클릭 시 PPT를 자동 생성하려면 별도의 백엔드(예: Render + FastAPI)가 필요합니다.
