# 납작복숭아 정원 — 프로토타입

기록(활동·수면·식단) → 나무 성장 → 수확 → 정원 꾸미기 루프를 검증하는 단일 HTML 프로토타입 목업.

- `index.html` 하나로 동작 (서버·빌드 불필요)
- 정적 사이트 → Vercel에서 그대로 서빙

## 배포 (Vercel)
1. 이 저장소를 GitHub에 푸시
2. vercel.com → New Project → 이 GitHub 저장소 Import
3. Framework Preset: **Other**, Build/Output 설정 없음(그대로 Deploy)
4. 생성된 `https://○○○.vercel.app` 링크로 테스트
