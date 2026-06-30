# 썰쌔미 바다생물 잡기 v1

Vercel 배포용 React + Vite + MediaPipe 손 인식 모션게임입니다.

## 포함 기능

- 카메라 기반 손 인식 모드
- 터치/마우스 모드
- 카메라 화면 위에 바다생물이 떨어지는 AR 느낌
- 점수
- 30초 제한 시간
- 모바일/태블릿/PC 반응형

## GitHub 업로드 시 파일 구조

GitHub 저장소 첫 화면에 아래 파일이 바로 보여야 합니다.

- index.html
- package.json
- vite.config.js
- vercel.json
- src 폴더
- public 폴더
- README.md

ZIP 파일 자체를 올리면 안 됩니다.
압축을 푼 뒤 안의 파일들을 올려야 합니다.

## Vercel 설정

Framework Preset: Vite  
Build Command: npm run build  
Output Directory: dist  
Root Directory: ./  

## 주의

카메라는 보안 정책상 https:// 또는 localhost 환경에서만 안정적으로 작동합니다.
안드로이드/아이패드에서 HTML 파일을 직접 열면 카메라가 막힐 수 있습니다.
