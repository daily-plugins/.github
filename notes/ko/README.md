# Daily Plugins 조직 프로필

Daily Plugins는 플러그인 저장소 모음입니다. 현재 제공하는 프로젝트는 [Vault용 플러그인 MCP 서버](https://github.com/daily-plugins/Vault) 하나입니다.
이 `.github` 저장소에는 공개 조직 프로필과 브랜드 파일을 관리합니다. 서버 소스는 `Vault`에 있습니다.

## 브랜드 파일

<img src="../../assets/daily-plugins.png" width="200" height="200" alt="Daily Plugins 원본 3D 플러그와 S자 연결선" />

| 파일 | 바이트 | 용도 |
| --- | --- | --- |
| [daily-plugins.png](../../assets/daily-plugins.png) | 1,452,787 | 검은 배경을 포함한 사용자 제공 원본 그대로이며 조직 프로필에 사용 |
| [daily-plugins-transparent.png](../../assets/daily-plugins-transparent.png) | 446,766 | 입체 형태와 색상을 유지한 배경 제거 편집본이며 원본과 픽셀 단위로 같지는 않음 |
| [daily-plugins-compact.png](../../assets/daily-plugins-compact.png) | 6,215 | 192 × 192 투명 PNG, 10,000바이트 미만 |
| [daily-plugins.svg](../../assets/daily-plugins.svg) | 8,519 | 경량 PNG를 내장한 독립 SVG, 10,000바이트 미만 |

원본 이미지는 바이트 단위로 그대로 보관합니다. 투명 배경판은 내장 이미지 생성 도구에 실루엣, S자 굴곡, 플러그, 입체 두께, 음영, 청록·파랑·라벤더 색을 유지하고 배경만 제거하도록 지시해 만들었습니다. 이 편집본에는 작은 테두리 차이가 생길 수 있습니다. 경량판은 팔레트 압축을 사용합니다.

SVG는 래스터 이미지를 담는 형식이며 **패스를 편집하는 벡터가 아닙니다**. 단순화한 그림으로 대체하지 않고 제공된 이미지의 외형을 유지하기 위한 구성입니다. 고해상도 PNG에는 경량판의 10KB 제한을 적용하지 않습니다.

## 조직 프로필

[profile/README.md](../../profile/README.md)는 조직 개요에 원본 이미지를 표시합니다. 계정 아바타는 변경하지 않았습니다.

로컬 작업 폴더 구조:

```text
daily-plugins/
├── .github/   Organization profile and brand assets
└── vault/     Vault plugin MCP server
```

[English documentation](../../README.md)
