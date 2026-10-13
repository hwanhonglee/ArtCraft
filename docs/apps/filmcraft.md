# FilmCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/filmcraft) · [소스 폴더](../../apps/filmcraft)

## 기능

타임라인 영상 편집, 트리밍·다중 카메라, 색 보정·키프레임·효과·제목·자막·오디오 믹싱과 출력을 제공합니다.

- 비슷한 작업 도구: Premiere Pro
- 개발 상태: **알파**
- 고정 커밋: `cee1feb185e675a108f78067f71ad86a640ace3d`
- 설치 Release: [v0.7.2](https://github.com/storytold/filmcraft/releases/tag/v0.7.2)

## 처음 시험할 작업

짧은 영상 가져오기 → 컷 편집·제목·음악 추가 → H.264 출력 → 연속 재생과 음향 확인

## 제한사항

- Premiere .prproj 프로젝트를 직접 열지 못합니다. FCP7 XML, AAF, OTIO 등으로 교환해야 합니다.
- VST3/Audio Units/OpenFX 플러그인 호스팅을 지원하지 않습니다.
- 소프트웨어 배포 코덱 출력은 H.264 중심이며 HEVC 출력은 하드웨어 인코더 조건이 있습니다. AV1 출력은 미지원입니다.
- 일부 효과와 출력 렌더링은 CPU에서 처리합니다. 대용량 영상 성능과 실제 카메라·휴대폰 미디어 호환성을 확인해야 합니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/filmcraft
cargo run --release -p filmcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/filmcraft/blob/cee1feb185e675a108f78067f71ad86a640ace3d/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/filmcraft/blob/cee1feb185e675a108f78067f71ad86a640ace3d/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
