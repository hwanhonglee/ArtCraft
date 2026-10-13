# WordCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/wordcraft) · [소스 폴더](../../apps/wordcraft)

## 기능

문서·표·스타일·목차·각주·참고문헌·변경 추적을 편집하고 DOCX 등 문서 형식과 PDF를 처리합니다.

- 비슷한 작업 도구: Word
- 개발 상태: **알파**
- 고정 커밋: `159b84f54c74e9e82fb3109b758ae7dd6f4e3ab0`
- 설치 Release: [v0.6.1](https://github.com/storytold/wordcraft/releases/tag/v0.6.1)

## 처음 시험할 작업

DOCX 사본 열기 → 문단·표 수정 → 새 DOCX/PDF 저장 → Word와 페이지 비교

## 제한사항

- 실제 DOCX 문서의 호환성, 차트·SmartArt 보존과 Word에 가까운 페이지 나누기가 아직 개선 대상입니다.
- 화면에서 비슷하게 보여도 왕복 저장 후 객체·쪽수·문단 배치가 달라질 수 있습니다.
- 맞춤법·문법·UI 언어와 한국어 입력·출력 지원은 각각 구분해서 확인하세요. 한국어 전문 교정 기능은 검증하지 않았습니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/wordcraft
cargo run --release -p wordcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/wordcraft/blob/159b84f54c74e9e82fb3109b758ae7dd6f4e3ab0/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/wordcraft/blob/159b84f54c74e9e82fb3109b758ae7dd6f4e3ab0/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
