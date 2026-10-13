# DeckCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/deckcraft) · [소스 폴더](../../apps/deckcraft)

## 기능

슬라이드·마스터·테마·도형·문자·표·차트·전환·애니메이션을 만들고 PPTX/PDF와 발표 화면을 제공합니다.

- 비슷한 작업 도구: PowerPoint
- 개발 상태: **알파**
- 고정 커밋: `d5e30557eb9a846cd3eda43aa1552d88e25339b3`
- 설치 Release: [v0.6.1](https://github.com/storytold/deckcraft/releases/tag/v0.6.1)

## 처음 시험할 작업

PPTX 사본 열기 → 간단한 슬라이드 수정 → 새 PPTX/PDF 저장 → PowerPoint에서 배치·발표 확인

## 제한사항

- 실제 PowerPoint 자료 모음으로 충분한 호환성 검증이 이뤄지지 않았습니다.
- 일부 댓글 스레드와 미디어 옵션 등은 PPTX 왕복 저장에서 누락될 수 있습니다.
- 템플릿·슬라이드 쇼·매크로 변형 파일은 일반 .pptx로 저장되며, SmartArt는 원본 의미 구조를 완전히 편집하는 구현이 아닙니다.
- 회사 템플릿·내장 글꼴·복잡한 차트·애니메이션은 PowerPoint에서 재확인해야 합니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/deckcraft
cargo run --release -p deckcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/deckcraft/blob/d5e30557eb9a846cd3eda43aa1552d88e25339b3/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/deckcraft/blob/d5e30557eb9a846cd3eda43aa1552d88e25339b3/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
- [docs/gaps.md](https://github.com/storytold/deckcraft/blob/d5e30557eb9a846cd3eda43aa1552d88e25339b3/docs/gaps.md) — 고정 커밋의 기능·상태·공백·조건
