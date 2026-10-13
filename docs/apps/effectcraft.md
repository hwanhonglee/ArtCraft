# EffectCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/effectcraft) · [소스 폴더](../../apps/effectcraft)

## 기능

컴포지션·레이어·키프레임·표현식·효과와 3D 카메라·조명으로 모션그래픽과 합성 영상을 만듭니다.

- 비슷한 작업 도구: After Effects
- 개발 상태: **알파**
- 고정 커밋: `549e9d825132986d6167c1432cd3328efcbb0278`
- 설치 Release: [v0.9.2](https://github.com/storytold/effectcraft/releases/tag/v0.9.2)

## 처음 시험할 작업

새 컴포지션 → 이미지·문자 레이어 → 위치·불투명도 키프레임 → 짧게 렌더링·재생 확인

## 제한사항

- After Effects .aep/.aepx 프로젝트를 열지 못하며 After Effects 플러그인은 실행되지 않습니다. 자체 .ecproj 형식을 사용합니다.
- 같은 설정이 After Effects와 같은 결과를 내는지 자동 대조 검증이 아직 없습니다.
- macOS가 가장 많이 시험된 플랫폼이며 Windows/Linux의 기본 조작에서 보고된 문제가 있습니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/effectcraft
cargo run --release -p effectcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/effectcraft/blob/549e9d825132986d6167c1432cd3328efcbb0278/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/effectcraft/blob/549e9d825132986d6167c1432cd3328efcbb0278/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
