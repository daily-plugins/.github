# Daily Plugins 조직 프로필

[Daily Plugins](https://github.com/daily-plugins)의 공개 조직 프로필과 공용 브랜드 파일을 관리하는 저장소입니다.

Daily Plugins는 플러그인 저장소 모음입니다. 현재 제공하는 프로젝트는 [Vault용 플러그인 MCP 서버](https://github.com/daily-plugins/Vault) 하나입니다. 이 `.github` 저장소에는 조직 브랜드와 프로필을 관리하며, MCP 서버 소스는 `Vault` 저장소에 있습니다.

## 브랜드 파일

<img src="../../assets/daily-plugins.png" width="128" height="128" alt="Daily Plugins 아이콘" />

| 파일 | 크기 | 형식 |
| --- | --- | --- |
| [daily-plugins.svg](../../assets/daily-plugins.svg) | 1,178바이트 | 편집 가능한 512 × 512 벡터, 투명 배경 |
| [daily-plugins.png](../../assets/daily-plugins.png) | 9,927바이트 | 192 × 192 RGBA PNG, 투명 배경 |

두 파일 모두 10,000바이트 미만입니다. 원본의 긴 S자 연결선, 오른쪽 위로 향한 플러그, 청록색·파란색·라벤더색 흐름을 유지했습니다. 배경과 플러그 홈은 투명하며, 입체 두께와 그림자는 제거했습니다. 작은 PNG는 192 × 192이며 더 큰 크기에는 SVG를 사용합니다.

사용자가 제공한 이미지의 형태와 배치를 기준으로 제작했습니다. 내장 이미지 생성 도구로 원본 유지 방향을 확인한 뒤, 테두리를 정리한 편집 가능한 SVG를 구성했습니다. 배포용 PNG는 같은 SVG에서 `@resvg/resvg-js`로 렌더링했습니다. 다른 앱 아이콘의 경로 데이터는 포함하지 않았습니다.

## 조직 프로필

GitHub는 공개 조직 개요에 [profile/README.md](../../profile/README.md)를 표시합니다. 조직 페이지에서도 이미지를 불러올 수 있도록 절대 raw-content URL을 사용합니다.

계정 아바타는 별도 설정이며 이 저장소로 변경되지 않습니다. 이번 작업은 요청에 따라 프로필 README에만 아이콘을 적용합니다.

출처: [GitHub 조직 프로필 문서](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

[English documentation](../../README.md)
