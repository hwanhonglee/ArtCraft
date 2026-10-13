# VectorCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/vectorcraft) · [소스 폴더](../../apps/vectorcraft)

## 기능

벡터 일러스트·로고·아이콘을 만들고 패스·도형·그라디언트·문자를 편집하며 SVG/PDF 등을 입출력합니다.

- 비슷한 작업 도구: Illustrator
- 개발 상태: **알파**
- 고정 커밋: `0d0ea352df99044589a7ce0efc7004f7a5b6b7c0`
- 설치 Release: [v0.10.0](https://github.com/storytold/vectorcraft/releases/tag/v0.10.0)

## 처음 시험할 작업

SVG 사본 열기 → 패스·색·문자 수정 → SVG/PDF 출력 → 대상 프로그램에서 재확인

## 제한사항

- PDF 호환 .ai를 처리하지만 Illustrator 고유 편집 데이터의 완전한 입출력을 지원하지 않습니다.
- 3D/Materials, 일부 래스터 효과와 도구의 세부 동작에 공백이 있습니다.
- Affinity 문서는 읽기 중심이며 지원되지 않는 효과 등이 있습니다. Affinity 형식 저장은 지원하지 않습니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/vectorcraft
cargo run --release -p vectorcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/vectorcraft/blob/0d0ea352df99044589a7ce0efc7004f7a5b6b7c0/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/vectorcraft/blob/0d0ea352df99044589a7ce0efc7004f7a5b6b7c0/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
