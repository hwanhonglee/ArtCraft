# ArtCraft — 개인용 Craft 앱 13종 모음

ArtCraft 팀의 오픈소스 편집 앱 13개를 `hwanhonglee` 계정으로 포크하고 한 폴더로 받을 수 있게 연결한 개인용 소스 허브입니다. 공식 ArtCraft 제품이나 통합 실행 앱을 새로 만든 저장소는 아닙니다.

**Windows에서 편집 앱을 쓰기만 하려면 설치 파일을 받으면 됩니다. 코드 수정이 목적일 때 이 저장소를 내려받고 빌드하세요.**

- [앱별 기능·제한사항](docs/APPS.md)
- [Windows 설치·소스 실행](docs/WINDOWS.md)
- [원본·포크·고정 커밋·설치 버전](docs/SOURCES.md)
- [업데이트 방법](docs/UPDATES.md)
- [라이선스·상표 조건](LICENSE-NOTICE.md)

## 13개 앱

기능과 제한은 고정된 소스의 공식 문서 기준입니다. 설치용 Release와 최신 소스는 기능이 다를 수 있습니다. 개발 상태는 개발팀의 표기이며 독립적인 앱 실행 검증 결과가 아닙니다.

| 앱 / 소스 폴더 | 비슷한 용도 | 상태 | 주요 기능 | 먼저 알아둘 제한 |
|---|---|---|---|---|
| [PhotoCraft](apps/photocraft) · [상세](docs/apps/photocraft.md) | Photoshop | 초기 알파 | 레이어·마스크·브러시·문자·색 보정으로 사진과 이미지를 편집하고 PSD/PSB를 입출력합니다. | 전문 작업용 Photoshop을 완전히 대체하는 단계가 아닙니다. |
| [LightCraft](apps/lightcraft) · [상세](docs/apps/lightcraft.md) | Lightroom | 알파 | 사진 라이브러리 정리·선별, RAW 현상, 노출·색·톤 커브·부분 보정, 프리셋과 일괄 내보내기를 제공합니다. | 카메라·RAW 압축 방식에 따라 센서 데이터 대신 내장 JPEG 미리보기를 사용하는 경우가 있습니다. |
| [VectorCraft](apps/vectorcraft) · [상세](docs/apps/vectorcraft.md) | Illustrator | 알파 | 벡터 일러스트·로고·아이콘을 만들고 패스·도형·그라디언트·문자를 편집하며 SVG/PDF 등을 입출력합니다. | PDF 호환 .ai를 처리하지만 Illustrator 고유 편집 데이터의 완전한 입출력을 지원하지 않습니다. |
| [FilmCraft](apps/filmcraft) · [상세](docs/apps/filmcraft.md) | Premiere Pro | 알파 | 타임라인 영상 편집, 트리밍·다중 카메라, 색 보정·키프레임·효과·제목·자막·오디오 믹싱과 출력을 제공합니다. | Premiere .prproj 프로젝트를 직접 열지 못합니다. FCP7 XML, AAF, OTIO 등으로 교환해야 합니다. |
| [EffectCraft](apps/effectcraft) · [상세](docs/apps/effectcraft.md) | After Effects | 알파 | 컴포지션·레이어·키프레임·표현식·효과와 3D 카메라·조명으로 모션그래픽과 합성 영상을 만듭니다. | After Effects .aep/.aepx 프로젝트를 열지 못하며 After Effects 플러그인은 실행되지 않습니다. 자체 .ecproj 형식을 사용합니다. |
| [DesignCraft](apps/designcraft) · [상세](docs/apps/designcraft.md) | InDesign | 프리알파 | 페이지·스프레드·프레임·연결된 본문·문단 스타일로 책자와 브로슈어를 편집하며 IDML/PDF/EPUB 등을 처리합니다. | InDesign .indd 문서를 직접 열지 못합니다. 교환은 IDML 중심입니다. |
| [FigCraft](apps/figcraft) · [상세](docs/apps/figcraft.md) | Figma | 알파 | UI 화면 디자인, Auto Layout·컴포넌트·변수·프로토타입과 초기 실시간 협업 기능을 제공합니다. | .fig 파일 읽기는 best effort이며 실제 Figma 문서로 충분히 검증되지 않았습니다. |
| [WordCraft](apps/wordcraft) · [상세](docs/apps/wordcraft.md) | Word | 알파 | 문서·표·스타일·목차·각주·참고문헌·변경 추적을 편집하고 DOCX 등 문서 형식과 PDF를 처리합니다. | 실제 DOCX 문서의 호환성, 차트·SmartArt 보존과 Word에 가까운 페이지 나누기가 아직 개선 대상입니다. |
| [GridCraft](apps/gridcraft) · [상세](docs/apps/gridcraft.md) | Excel | 알파 | XLSX 시트, 수식·동적 배열·표·정렬·필터·조건부 서식·차트·피벗테이블을 편집합니다. | VBA는 지원 범위 밖이며 열 때 삭제될 수 있습니다. Office Scripts와 Excel 추가 기능도 호환되지 않습니다. |
| [DeckCraft](apps/deckcraft) · [상세](docs/apps/deckcraft.md) | PowerPoint | 알파 | 슬라이드·마스터·테마·도형·문자·표·차트·전환·애니메이션을 만들고 PPTX/PDF와 발표 화면을 제공합니다. | 실제 PowerPoint 자료 모음으로 충분한 호환성 검증이 이뤄지지 않았습니다. |
| [PdfCraft](apps/pdfcraft) · [상세](docs/apps/pdfcraft.md) | Acrobat | 알파 | PDF 보기·주석·양식·서명, 페이지 정리·병합·분할과 문서 보호를 제공합니다. | Office 문서를 PDF로 바꾸는 기능은 없으며 Word 내보내기는 배치를 잃을 수 있습니다. |
| [SoundCraft](apps/soundcraft) · [상세](docs/apps/soundcraft.md) | Pro Tools | 프리알파 | 다중 트랙 녹음·편집, 믹서·효과·자동화·MIDI와 음원 출력을 제공합니다. | 오디오 인터페이스·버퍼 크기 선택, MIDI 컨트롤러에서의 녹음, AAF/OMF 세션 교환이 아직 미지원입니다. |
| [CADCraft](apps/cadcraft) · [상세](docs/apps/cadcraft.md) | AutoCAD | 프리알파 | 선·호·치수·레이어·블록·해치·구속 조건을 이용한 도면 작업과 DXF/DWG 입출력을 제공합니다. | 상위 ROADMAP은 프리알파로 명시합니다. 주요 제도·블록·출력·무손실 DWG 저장 워크플로가 아직 완성되지 않았습니다. |

## 13개 소스를 한 번에 받기

Git이 설치된 PowerShell 또는 터미널에서 실행합니다. 앱 설치 명령이 아니라 소스 다운로드 명령입니다.

```powershell
git clone --recurse-submodules --depth 1 --shallow-submodules https://github.com/hwanhonglee/ArtCraft.git
cd ArtCraft
git submodule status
```

이미 일반 `git clone`으로 받았다면:

```powershell
git submodule update --init --depth 1 --jobs 4
```

`apps/` 아래 13개가 각자의 포크에 연결된 Git 서브모듈입니다. 허브는 특정 커밋을 고정합니다. **GitHub Download ZIP에는 서브모듈 소스가 들어오지 않으므로 위 Git 명령을 사용하세요.**

## 설치해서 쓰기

[공식 앱 목록](https://getartcraft.com/apps) 또는 [ArtCraft Launcher](https://github.com/storytold/craft-launcher/releases/latest)에서 설치할 수 있습니다. [Windows 안내](docs/WINDOWS.md)에 13개 앱의 MSI·포터블 ZIP 링크를 적었습니다.

- `ArtCraft_0.41.0_x64-setup.exe`의 ArtCraft는 별도의 **AI 이미지·영상 스튜디오**입니다.
- PhotoCraft·GridCraft·DeckCraft 등 13개는 각자 독립적인 편집 앱입니다.
- **ArtCraft Launcher**는 편집 앱 설치·업데이트·실행을 관리합니다.
- 이 허브의 범위는 13개 편집 앱 소스입니다. AI 스튜디오 본체·Launcher 소스는 별도 참고 링크로 안내합니다.
- 편집 앱은 무료·로컬 작업 중심이며 외부 AI 생성 비용은 별도입니다.
- MCP/CLI 자동화는 앱별 설정이 추가로 필요합니다. 다운로드만으로 ChatGPT 연결이 끝나지는 않습니다.

## 코드 실행 예시

Windows 빌드에는 최신 stable Rust(현재 UI 요구사항을 고려해 1.95 이상)와 MSVC C++ Build Tools가 필요합니다.

```powershell
cd apps/photocraft
cargo run --release -p photocraft
```

다른 앱은 해당 폴더에서 같은 이름의 패키지를 실행합니다. 앱별 `README.md`, `AGENTS.md`, 개발 문서를 우선 확인하세요.

## 구성

| 위치 | 내용 |
|---|---|
| `apps/<앱이름>` | 13개 포크 소스: Git 서브모듈 |
| `docs/apps/<앱이름>.md` | 한국어 기능·사용 예시·제한사항·공식 근거 |
| `docs/WINDOWS.md` | 설치 파일 사용과 Rust 빌드의 차이 |
| `docs/UPDATES.md` | 원본 → 포크 → 허브 업데이트 순서 |
| `docs/SOURCES.md` | 확인 시각·고정 커밋·Release 버전 |
| `app-catalog.json` | 기계가 읽을 수 있는 동일 정보 |
| `LICENSE-NOTICE.md` | 코드·외부 자산·상표 조건 |

기존 파일은 사본으로 시험하고 새 이름으로 저장한 뒤 원래 프로그램에서 다시 확인하세요. 특히 GridCraft의 VBA·복잡한 XLSX, CADCraft의 미지원 객체, PPTX/DOCX 교환은 제한사항을 먼저 읽으세요.
