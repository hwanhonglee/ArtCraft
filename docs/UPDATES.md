# 원본·포크·허브 업데이트

허브는 생성 시점의 소스 커밋을 고정합니다. `git pull`만 하면 원본 최신 버전까지 자동으로 합쳐지지는 않습니다.

## 허브에 기록된 버전 받기

```powershell
git pull --ff-only
git submodule sync --recursive
git submodule update --init --recursive --depth 1
git submodule status
```

## 원본 변경을 내 포크에 반영하기

각 포크의 GitHub 페이지에서 **Sync fork**를 사용할 수 있습니다. GitHub CLI를 쓰는 경우 한 앱씩:

```powershell
gh repo sync hwanhonglee/photocraft --source storytold/photocraft
```

내 수정과 충돌하면 강제 동기화하지 말고 해당 앱의 작업 브랜치에서 병합 또는 rebase를 검토하세요. 자동 업데이트·예약 작업을 만들지는 않았습니다.

## 허브의 고정 커밋 바꾸기

포크를 동기화한 뒤, ArtCraft 루트에서 PhotoCraft를 갱신하는 예시:

```powershell
git -C apps/photocraft fetch origin main
git -C apps/photocraft switch --detach origin/main
git add apps/photocraft
```

다른 앱은 [SOURCES.md](SOURCES.md)에 기록한 브랜치를 사용하세요. 서브모듈의 detached HEAD는 특정 커밋을 고정한 정상 동작입니다. 앱을 수정하려면 앱 폴더에서 별도 작업 브랜치를 만드세요.

커밋을 바꾸면 `app-catalog.json`, `docs/SOURCES.md`와 앱별 제한사항·설치 Release 안내를 함께 갱신하세요. 필요한 실행·파일 교환 검증을 마친 뒤 허브 커밋을 올립니다. **포크 업데이트와 허브 포인터 업데이트는 서로 다른 작업입니다.**
