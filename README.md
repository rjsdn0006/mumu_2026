# 가평 촌캉스 · 2026.10.17–18

Pretendard를 사용하는 정적 여행 일정 사이트입니다.

## Vercel 배포

이 저장소를 Vercel에서 Import합니다. Framework Preset은 **Other**, Output Directory는 **dist**입니다. Build Command와 Install Command는 비워 두세요. `vercel.json`에 출력 경로가 지정되어 있습니다.

## 파일

- `dist/index.html`: 사이트와 일정·게임 기능
- `dist/hero-autumn.webp`: 사용자 지정 hero 이미지
- `vercel.json`: 배포 설정

지도와 경로는 Leaflet, OpenStreetMap, OSRM 외부 서비스를 사용합니다. 일정 변경과 체크리스트는 방문자의 브라우저에 저장되며 다른 기기와 공유되지 않습니다. 지도 목적지는 마일리 인근 기준입니다.
