# BoulderWay Beta v1.0 — GitHub Pages 배포판

## 무료 배포 (PC에서)
1. https://github.com 에 가입 또는 로그인합니다.
2. 우측 상단 + → New repository → 이름 `boulderway` → Public → Create repository.
3. `Add file` → `Upload files`에서 **ZIP이 아닌 압축 해제한 폴더 안의** `index.html`, `favicon.svg`, `.nojekyll`을 저장소 최상단에 올리고 Commit changes를 누릅니다. (숨김 파일 `.nojekyll`은 선택사항)
4. Settings → Pages → Build and deployment: Deploy from a branch → Branch `main` / `(root)` → Save.
5. 잠시 후 표시되는 `https://사용자이름.github.io/boulderway/` 주소를 엽니다. 최초 반영에는 시간이 걸릴 수 있습니다.

## 주의
- 지도는 외부 OpenStreetMap 서버 연결에 의존하며 웹에 게시해도 403이 해소된다는 보장은 없습니다.
- 지도 서비스 이용 정책과 출처 표시를 준수해야 합니다. 공용 OSM 타일 서버는 대규모 상용 서비스용으로 보장되지 않습니다.
- 기록은 **브라우저 localStorage**에 저장되므로 파일 버전과 Pages 웹주소 사이에서 자동으로 이전되지 않습니다. 기존 앱 MY에서 JSON 백업 후 새 주소의 MY에서 복원하세요.
- GitHub Pages는 정적 웹 호스팅입니다. 회원가입·기기간 자동 동기화는 아직 구현되지 않았습니다.
- 위치 저장은 개인 브라우저에서만 이루어지며 타인과 공유되지 않습니다.
- GitHub 계정과 저장소를 실제 생성하거나 공개 배포한 것은 아닙니다.
