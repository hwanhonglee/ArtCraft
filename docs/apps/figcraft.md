# FigCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/figcraft) · [소스 폴더](../../apps/figcraft)

## 기능

UI 화면 디자인, Auto Layout·컴포넌트·변수·프로토타입과 초기 실시간 협업 기능을 제공합니다.

- 비슷한 작업 도구: Figma
- 개발 상태: **알파**
- 고정 커밋: `e56856f4016c76fbc862ac2fb4fd3fb43a68f396`
- 설치 Release: [v0.5.1](https://github.com/storytold/figcraft/releases/tag/v0.5.1)

## 처음 시험할 작업

템플릿 선택 → 화면·컴포넌트·Auto Layout 편집 → 프로토타입과 출력 확인

## 제한사항

- .fig 파일 읽기는 best effort이며 실제 Figma 문서로 충분히 검증되지 않았습니다.
- 협업은 초기 구현입니다. Figma 같은 계정·팀·클라우드 운영 기능은 아직 없습니다.
- 자체 WebAssembly 플러그인을 사용하며 Figma 플러그인과 호환되지 않습니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/figcraft
cargo run --release -p figcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/figcraft/blob/e56856f4016c76fbc862ac2fb4fd3fb43a68f396/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/figcraft/blob/e56856f4016c76fbc862ac2fb4fd3fb43a68f396/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
