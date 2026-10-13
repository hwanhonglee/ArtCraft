# GridCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/gridcraft) · [소스 폴더](../../apps/gridcraft)

## 기능

XLSX 시트, 수식·동적 배열·표·정렬·필터·조건부 서식·차트·피벗테이블을 편집합니다.

- 비슷한 작업 도구: Excel
- 개발 상태: **알파**
- 고정 커밋: `84acf6293b1dc1fc09837524e035d674eb4d6741`
- 설치 Release: [v0.6.1](https://github.com/storytold/gridcraft/releases/tag/v0.6.1)

## 처음 시험할 작업

작은 XLSX 사본 열기 → 알려진 정답으로 수식 결과 비교 → 새 이름으로 저장 → Excel에서 차트·피벗·수식 확인

## 제한사항

- VBA는 지원 범위 밖이며 열 때 삭제될 수 있습니다. Office Scripts와 Excel 추가 기능도 호환되지 않습니다.
- Power Query 편집기, 외부 데이터 새로 고침과 데이터 모델을 지원하지 않습니다.
- 일부 미지원 XLSX 구성과 차트·슬라이서·타임라인·Power Pivot 내용이 저장 중 누락되거나 단순화될 수 있습니다.
- 대형 파일·재계산 성능과 계산 정확성에 알려진 공백이 있습니다. .xls는 부분 가져오기이며 .xls 쓰기는 미지원입니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/gridcraft
cargo run --release -p gridcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/gridcraft/blob/84acf6293b1dc1fc09837524e035d674eb4d6741/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/gridcraft/blob/84acf6293b1dc1fc09837524e035d674eb4d6741/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
- [docs/gaps.md](https://github.com/storytold/gridcraft/blob/84acf6293b1dc1fc09837524e035d674eb4d6741/docs/gaps.md) — 고정 커밋의 기능·상태·공백·조건
