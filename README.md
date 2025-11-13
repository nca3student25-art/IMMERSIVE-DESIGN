# IMMERSIVE STUDIO

구글 스티치로 디자인한 이머시브 스튜디오 웹사이트입니다.

## 🚀 Railway 배포 방법

### 1. Railway 프로젝트 생성

1. [Railway](https://railway.app/)에 로그인합니다
2. "New Project" 클릭
3. "Deploy from GitHub repo" 선택
4. 이 리포지토리를 선택합니다

### 2. 자동 배포

Railway가 자동으로 다음을 감지합니다:
- `package.json` 파일을 통해 Node.js 프로젝트 인식
- `start` 스크립트를 실행하여 서버 시작
- PORT 환경 변수를 자동으로 설정

### 3. 배포 완료

배포가 완료되면 Railway에서 제공하는 URL을 통해 웹사이트에 접속할 수 있습니다.

## 🛠️ 로컬 개발

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm start
```

서버가 실행되면 `http://localhost:3000`에서 확인할 수 있습니다.

## 📁 프로젝트 구조

```
.
├── index.html        # 메인 HTML 파일
├── screen.png        # 스크린샷 이미지
├── server.js         # Express 서버
├── package.json      # 프로젝트 설정
└── README.md         # 문서
```

## 🎨 기술 스택

- HTML5
- Tailwind CSS
- Google Fonts (Space Grotesk)
- Material Symbols Icons
- Express.js (서버)

## 📝 라이선스

MIT
