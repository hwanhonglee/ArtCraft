# PhotoCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/photocraft) · [소스 폴더](../../apps/photocraft)

## 기능

레이어·마스크·브러시·문자·색 보정으로 사진과 이미지를 편집하고 PSD/PSB를 입출력합니다.

- 비슷한 작업 도구: Photoshop
- 개발 상태: **초기 알파**
- 고정 커밋: `6f85054288a564f9fbbccb99268ffdb34e581584`
- 설치 Release: [v0.8.2](https://github.com/storytold/photocraft/releases/tag/v0.8.2)

## 처음 시험할 작업

사본 PSD 열기 → 레이어·마스크 수정 → 새 이름으로 PSD와 PNG 저장 → 원래 프로그램에서 다시 확인

## 제한사항

- 전문 작업용 Photoshop을 완전히 대체하는 단계가 아닙니다.
- AI·생성형 기능, 일부 도구, 타이포그래피·전문 워크플로와 Photoshop 플러그인 호환성에 공백이 있습니다.
- PSD 지원은 모든 실제 문서의 동일 렌더링·무손실 저장을 보장하지 않습니다. 원본 사본으로 열기·저장·결과 비교를 먼저 하세요.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/photocraft
cargo run --release -p photocraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/photocraft/blob/6f85054288a564f9fbbccb99268ffdb34e581584/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/photocraft/blob/6f85054288a564f9fbbccb99268ffdb34e581584/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
- [docs/development.md](https://github.com/storytold/photocraft/blob/6f85054288a564f9fbbccb99268ffdb34e581584/docs/development.md) — 고정 커밋의 기능·상태·공백·조건
- [docs/brand/LICENSE-brand.txt](https://github.com/storytold/photocraft/blob/6f85054288a564f9fbbccb99268ffdb34e581584/docs/brand/LICENSE-brand.txt) — 고정 커밋의 기능·상태·공백·조건
