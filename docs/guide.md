# 설치와 사용 / Installation and use

## 한국어

릴리스에서 `RoomCommentators-0.4.11-Setup.exe`를 내려받아 실행합니다. 현재 사용자에게 설치되며 관리자 권한을 요청하지 않습니다. 시작 메뉴에서 방구석 중계단을 실행하세요. 설치 파일은 서명되지 않았으며 출처가 불확실하면 설치를 취소하세요.

중계 시작 → 제목·본문 편집 → 예측·판정 → 종료가 기본 흐름입니다. `Ctrl+S`는 실제 파일 저장입니다. `F8` 일시정지, `F9` 음소거, `Esc` 종료는 앱에 포커스가 있을 때 동작합니다. 설정에서 음량·자막·빈도·장난 강도·중계석 위치와 크기를 조절합니다.

영상은 녹화 시작 → 15초 이상 작업 → 녹화 종료 → 대사 검토 → 영상 만들기 → 재생 → AVI 저장 순서입니다. 약 3분까지만 녹화하며 영상에는 최대 두 사건을 선택합니다. 전체 화면·마이크는 녹화하지 않습니다. 자막을 바꾼 경우 Windows 한국어 음성이 없으면 자막만 출력됩니다.

VS Code 동행: 확장 메뉴의 **VSIX에서 설치**로 `roomside-casters-0.4.11.vsix`를 선택하세요. 로컬 `.txt`/`.md`에서 명령 팔레트의 **방구석 중계단: 이 문서 중계 시작**을 실행합니다. 다른 문서 선택 시 자동 일시정지합니다. 외부 화면 녹화는 지원하지 않습니다.

제거: Windows 설정 → 앱 → 설치된 앱 → 방구석 중계단. 저장한 문서·영상·경기 기록은 남습니다. 보관 위치는 `%LOCALAPPDATA%\RoomCommentators`입니다. 녹화는 수백 MB가 될 수 있으며 자동 정리는 없습니다.

## English

Download and run `RoomCommentators-0.4.11-Setup.exe` from the release. It installs for the current user without administrator privileges. Launch **방구석 중계단** from Start. The installer is unsigned; cancel if you are uncertain of its source.

Choose **중계 시작** (Start), write a title/body, listen to predictions, then edit/save to settle them. `Ctrl+S` actually saves a file. `F8` pauses, `F9` mutes and `Esc` stops while the app has focus. Settings control volume, captions, frequency, teasing and booth layout.

For video: explicitly start recording, work for at least 15 seconds, stop recording, review dialogue, create the video, preview and save AVI. Recording lasts about three minutes maximum; up to two events are selected. No full-desktop or microphone recording. Edited lines use Windows Korean speech if installed, otherwise captions.

Optional VS Code companion: use **Install from VSIX** for `roomside-casters-0.4.11.vsix`. Open a local `.txt`/`.md` and run **방구석 중계단: 이 문서 중계 시작** from the command palette. Switching documents pauses observation. Recording external windows is unsupported.

Uninstall in Windows Settings → Apps → Installed apps. Saved documents, recordings and match history remain under `%LOCALAPPDATA%\RoomCommentators`. Recordings can use hundreds of MB; no automatic cleanup is provided.
