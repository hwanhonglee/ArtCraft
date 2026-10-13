# CADCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/cadcraft) · [소스 폴더](../../apps/cadcraft)

## 기능

선·호·치수·레이어·블록·해치·구속 조건을 이용한 도면 작업과 DXF/DWG 입출력을 제공합니다.

- 비슷한 작업 도구: AutoCAD
- 개발 상태: **프리알파**
- 고정 커밋: `033ee15e0146eac3a686c832580fdd804542fe13`
- 설치 Release: [v0.6.2](https://github.com/storytold/cadcraft/releases/tag/v0.6.2)

## 처음 시험할 작업

간단한 DXF 사본 열기 → 선·치수 편집 → 새 파일 저장 → AutoCAD 또는 원래 뷰어에서 객체·축척 비교

## 제한사항

- 상위 ROADMAP은 프리알파로 명시합니다. 주요 제도·블록·출력·무손실 DWG 저장 워크플로가 아직 완성되지 않았습니다.
- 모델링하지 못하는 도면 객체는 저장 중 유지되지 않습니다. DWG/DXF 원본을 덮어쓰지 마세요.
- DWG 쓰기는 R2000 형식이며 AutoCAD 전체 기능·객체·확장 생태계 호환을 보장하지 않습니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/cadcraft
cargo run --release -p cadcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/cadcraft/blob/033ee15e0146eac3a686c832580fdd804542fe13/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/cadcraft/blob/033ee15e0146eac3a686c832580fdd804542fe13/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
