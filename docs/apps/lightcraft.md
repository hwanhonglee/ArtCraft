# LightCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/lightcraft) · [소스 폴더](../../apps/lightcraft)

## 기능

사진 라이브러리 정리·선별, RAW 현상, 노출·색·톤 커브·부분 보정, 프리셋과 일괄 내보내기를 제공합니다.

- 비슷한 작업 도구: Lightroom
- 개발 상태: **알파**
- 고정 커밋: `b3d392b4994ee99dc389890f006600769d0c4ff5`
- 설치 Release: [v0.7.1](https://github.com/storytold/lightcraft/releases/tag/v0.7.1)

## 처음 시험할 작업

사진 폴더 가져오기 → 별점·선택 표시 → 노출·색 보정 → 사본 JPEG 내보내기

## 제한사항

- 카메라·RAW 압축 방식에 따라 센서 데이터 대신 내장 JPEG 미리보기를 사용하는 경우가 있습니다.
- 카메라 색 보정은 일부 기종에서 추정치를 사용하며 측정 기반 보정이 부족합니다.
- 피사체·하늘 마스크는 전통적인 휴리스틱 방식입니다. AI 마스크·노이즈 제거와 동등하지 않습니다.
- HDR 화면 표시와 Lightroom Classic의 Print/Book/Map 모듈 등에 공백이 있습니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/lightcraft
cargo run --release -p lightcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/lightcraft/blob/b3d392b4994ee99dc389890f006600769d0c4ff5/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/lightcraft/blob/b3d392b4994ee99dc389890f006600769d0c4ff5/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
- [docs/raw-parity.md](https://github.com/storytold/lightcraft/blob/b3d392b4994ee99dc389890f006600769d0c4ff5/docs/raw-parity.md) — 고정 커밋의 기능·상태·공백·조건
