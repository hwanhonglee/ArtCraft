# PdfCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/pdfcraft) · [소스 폴더](../../apps/pdfcraft)

## 기능

PDF 보기·주석·양식·서명, 페이지 정리·병합·분할과 문서 보호를 제공합니다.

- 비슷한 작업 도구: Acrobat
- 개발 상태: **알파**
- 고정 커밋: `7437bde378f43856eada40af25b983812e615e8a`
- 설치 Release: [v0.7.1](https://github.com/storytold/pdfcraft/releases/tag/v0.7.1)

## 처음 시험할 작업

PDF 사본 열기 → 주석 또는 페이지 병합·분할 → 새 PDF 저장 → 다른 PDF 뷰어에서 확인

## 제한사항

- Office 문서를 PDF로 바꾸는 기능은 없으며 Word 내보내기는 배치를 잃을 수 있습니다.
- 형식 변환·공유의 완성도가 낮고 Acrobat과의 대조 품질 검증이 아직 부족합니다.
- 일부 비정상 PDF의 충돌·멈춤이 계속 발견되고 수정되는 단계입니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/pdfcraft
cargo run --release -p pdfcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/pdfcraft/blob/7437bde378f43856eada40af25b983812e615e8a/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/pdfcraft/blob/7437bde378f43856eada40af25b983812e615e8a/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
