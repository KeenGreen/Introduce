# 조민서 포트폴리오 - 정적 웹사이트 파일

이 폴더에는 조민서의 포트폴리오 웹사이트를 정적 파일로 변환한 내용이 들어있습니다.

## 파일 구조
- `index.html` - 메인 HTML 파일
- `assets/` - CSS, JavaScript, 이미지 파일들
  - `index-CiNWRViT.css` - 스타일시트
  - `index-BFhoqK2g.js` - JavaScript 코드
  - `profile-photo-CF8WXi0S.jpg` - 프로필 사진

## 사용 방법

### 1. 로컬에서 실행
웹브라우저에서 `index.html` 파일을 직접 열거나, 로컬 웹서버를 실행하세요:

```bash
# Python 3이 설치된 경우
python -m http.server 8000

# Node.js가 설치된 경우
npx serve .
```

### 2. 웹 호스팅 서비스에 업로드
이 폴더의 모든 파일을 다음과 같은 웹 호스팅 서비스에 업로드할 수 있습니다:
- GitHub Pages
- Netlify
- Vercel
- AWS S3 Static Website Hosting
- 기타 정적 웹사이트 호스팅 서비스

### 3. 주의사항
- 모든 파일들이 상대 경로로 연결되어 있으므로 폴더 구조를 그대로 유지해야 합니다
- 웹서버 환경에서 실행하는 것을 권장합니다 (CORS 정책으로 인해 로컬 파일로 직접 열 때 일부 기능이 제한될 수 있음)

## 포함된 기능
- 반응형 디자인 (모바일, 태블릿, 데스크톱 지원)
- 프로필 정보 및 경력 사항
- 연구 활동 포트폴리오 (Google Drive 링크)
- 카카오페이증권 지원 동기
- AI 연계 리서치 아이디어

## 생성일
2025년 1월 2일