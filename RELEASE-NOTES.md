# 방구석 중계단 0.4.11 · 무료 베타 / Free beta

제목 하나 고쳤을 뿐인데, 결승전이 시작됐다.

두 해설위원이 다음 행동을 예측하고, 실제 수정과 저장으로 승부를 가릅니다. 야간 경기장·LED 전광판·두 캐릭터·내장 AI 음성 20개·전용 창 녹화와 15~30초 하이라이트를 제공합니다.

**처음 설치한다면 `RoomCommentators-0.4.11-Setup.exe`를 받으세요.** 기본 기능은 무료이고 회원가입·API 키가 필요 없습니다. UI와 대사는 한국어입니다.

- [한국어 소개와 사용법](https://github.com/qkdlsem-maker/room-commentators#readme)
- [English introduction](https://github.com/qkdlsem-maker/room-commentators/blob/main/README.en.md)
- [문제 제보 / Report a problem](https://github.com/qkdlsem-maker/room-commentators/issues/new/choose)
- [검증과 제한 / Verification & limitations](https://github.com/qkdlsem-maker/room-commentators/blob/main/docs/verification.md)

**서명 없는 Windows 공개 베타**입니다. .NET Framework 4.8이 필요하며, 다른 PC·Windows 10·고DPI 검증은 남아 있습니다. Windows가 게시자/평판 경고를 표시할 수 있습니다. 출처가 불확실하면 설치를 취소하세요. `SHA256SUMS.txt`에 배포 파일 해시를 제공합니다.

실제 설치·실행·종료·제거·재설치, C# 52개·음성/영상 74개·관찰기 9개 검사가 통과했습니다. 실제 서비스로 검증하지 않은 Gemini 제작 기능은 선택 사항입니다.

첨부 MP4는 실제 경기장 앱에서 한 글자를 입력하고 저장한 장면입니다. 앱 생성 AVI를 MP4로 형식 변환했으며, 가짜 화면/타이핑/점수를 넣지 않았습니다. AI 음성으로 재해설합니다. 촬영 후 종료 상태 문구와 배포 버전 표기를 정리했습니다.

---

You changed a title. They called a championship final.

Two commentators predict your next action. Actual edits and confirmed saves decide the match. A nighttime stadium, LED scoreboard, two original characters and 20 bundled AI voice lines turn small writing decisions into a sports broadcast. Explicit own-window recording creates 15–30-second highlights.

**For a first installation, download `RoomCommentators-0.4.11-Setup.exe`.** Core features are free and require no account or API key. **The app UI and dialogue are Korean.**

This is an **unsigned public Windows beta**, not a stable or store-certified release. It requires .NET Framework 4.8. Other PCs, Windows 10 and high DPI remain unverified. Windows may show a publisher/reputation warning; cancel if the source is uncertain. Check `SHA256SUMS.txt` for release hashes.

Actual install/launch/exit/uninstall/reinstall checks passed, along with 52 core, 74 voice/video and nine observer checks. Optional Gemini production has not been verified against the live service.

The MP4 shows actual use: a one-character title edit and a save. It is a format conversion of an app-generated AVI with bundled AI replay commentary. No fake typing, scores or screens. Release metadata and an ended-session label were updated after filming.

## Downloads

| File | Purpose |
| --- | --- |
| `RoomCommentators-0.4.11-Setup.exe` | Windows installer / 설치 파일 |
| `room-commentators-Windows-0.4.11.zip` | Executable, installer, optional VSIX and Korean guide / 실행 파일 묶음 |
| `roomside-casters-0.4.11.vsix` | Optional Windows VS Code local .txt/.md companion; no VS Code recording |
| `room-commentators-source-0.4.11.zip` | Buildable source, tests and asset provenance / 소스 백업 |
| `room-commentators-stadium-demo-0.4.11.mp4` | Actual-use video / 실제 시연 영상 |
| `SHA256SUMS.txt` | SHA-256 file hashes |

No code-signing purchase, account creation or paid API use was performed for this release. Recording is limited to the built-in editor, about three minutes at 10 fps, with AVI export. See the verification report for the full scope.
