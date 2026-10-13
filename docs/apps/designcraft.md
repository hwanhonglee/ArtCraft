# DesignCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/designcraft) · [소스 폴더](../../apps/designcraft)

## 기능

페이지·스프레드·프레임·연결된 본문·문단 스타일로 책자와 브로슈어를 편집하며 IDML/PDF/EPUB 등을 처리합니다.

- 비슷한 작업 도구: InDesign
- 개발 상태: **프리알파**
- 고정 커밋: `e862e0a613c0793c6fea7cfd37ad4145ed6cf686`
- 설치 Release: [v0.7.1](https://github.com/storytold/designcraft/releases/tag/v0.7.1)

## 처음 시험할 작업

새 책자 또는 IDML 사본 → 페이지·문자·그림 배치 → PDF 출력 → 페이지별 비교

## 제한사항

- InDesign .indd 문서를 직접 열지 못합니다. 교환은 IDML 중심입니다.
- 실제 InDesign IDML 문서의 왕복 저장과 렌더링 일치가 충분히 검증되지 않았습니다.
- 글꼴·본문 조판 차이로 줄바꿈·페이지 수·넘치는 텍스트가 달라질 수 있습니다. 인쇄물은 PDF를 페이지별로 확인해야 합니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/designcraft
cargo run --release -p designcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/designcraft/blob/e862e0a613c0793c6fea7cfd37ad4145ed6cf686/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/designcraft/blob/e862e0a613c0793c6fea7cfd37ad4145ed6cf686/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
- [docs/gaps.md](https://github.com/storytold/designcraft/blob/e862e0a613c0793c6fea7cfd37ad4145ed6cf686/docs/gaps.md) — 고정 커밋의 기능·상태·공백·조건
