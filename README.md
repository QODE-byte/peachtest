# 삐약농장 — 펫 키우기 프로토타입

기록(활동·수면·식단 3축) → 농작물 → 요리 → **펫 키우기** 핵심 루프를 검증하는 단일 HTML 목업.

- 기록 체크 → 🌾 농작물 (하루 1/2/3개 할수록 더 많이, 비처벌)
- 요리하기 → 🍲 요리 (레시피는 누적 기록으로 순차 해금)
- 펫에게 먹이주기 → 성장(🥚→🐣→🐤) / 펫 쓰다듬기 → 기분↑
- 상점: 농작물·요리 판매 → 🪙 → 꾸미기 배치
- `index.html` 하나로 동작 (서버·빌드 불필요), 정적 → Vercel 그대로 서빙

## 배포 (Vercel)
1. 이 저장소를 GitHub에 푸시
2. vercel.com → New Project → 이 저장소 Import
3. Framework Preset: **Other**, Build/Output 설정 없음(그대로 Deploy)
4. 생성된 `https://○○○.vercel.app` 링크로 테스트

> 이전 "납작복숭아 정원(나무 성장)" 버전은 프로젝트 루트 `peach_grove_prototype.html`에 보존되어 있습니다.
