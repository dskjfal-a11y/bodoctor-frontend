# 보닥터 (Bodoctor) Frontend

AI 보험 진단·상담 서비스 보닥터의 프론트엔드 (단일 HTML).

## 구성
- `index.html` — 모든 마크업 · 스타일 · 스크립트가 들어있는 단일 파일
- 외부 의존성: Pretendard 웹폰트, marked.js (CDN)

## 백엔드 연결
파일 상단의 `BACKEND` 상수가 hostname을 보고 자동 분기:
- localhost → `http://localhost:8787`
- 그 외 → `https://bodoctor-backend.onrender.com` (Render 배포 URL로 교체 필요)

## 배포 (Vercel)
1. 이 폴더를 GitHub 리포에 푸시
2. Vercel에서 import (Framework Preset: Other)
3. 배포 완료
