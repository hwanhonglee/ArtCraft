# SoundCraft

[전체 목록](../APPS.md) · [Windows 안내](../WINDOWS.md) · [내 포크](https://github.com/hwanhonglee/soundcraft) · [소스 폴더](../../apps/soundcraft)

## 기능

다중 트랙 녹음·편집, 믹서·효과·자동화·MIDI와 음원 출력을 제공합니다.

- 비슷한 작업 도구: Pro Tools
- 개발 상태: **프리알파**
- 고정 커밋: `a96cf50a3a661edbe1541af6a0c709735082e0f0`
- 설치 Release: [v0.6.1](https://github.com/storytold/soundcraft/releases/tag/v0.6.1)

## 처음 시험할 작업

짧은 WAV 가져오기 → 두 트랙 편집·믹스 → WAV 출력 → 파형·음량·연속 재생 확인

## 제한사항

- 오디오 인터페이스·버퍼 크기 선택, MIDI 컨트롤러에서의 녹음, AAF/OMF 세션 교환이 아직 미지원입니다.
- 기존 DAW 세션을 그대로 옮겨 동등하게 작업하는 수준은 아닙니다.
- 녹음 장치·지연·플러그인과 언어 지원은 실제 환경에서 별도로 시험해야 합니다.

## 소스 실행

Windows 환경 준비는 [Windows 안내](../WINDOWS.md)를 보세요. ArtCraft 루트에서 다음을 실행합니다.

```powershell
cd apps/soundcraft
cargo run --release -p soundcraft
```

공식 소스 README의 실행 패키지 기준입니다. 이번 작업에서 Windows 빌드·앱 실행을 시험한 것은 아닙니다.

## 공식 근거

- [README.md](https://github.com/storytold/soundcraft/blob/a96cf50a3a661edbe1541af6a0c709735082e0f0/README.md) — 고정 커밋의 기능·상태·공백·조건
- [ROADMAP.md](https://github.com/storytold/soundcraft/blob/a96cf50a3a661edbe1541af6a0c709735082e0f0/ROADMAP.md) — 고정 커밋의 기능·상태·공백·조건
