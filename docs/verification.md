# 0.4.11 검증 범위 / Verification scope

검증일 / Date: **2026-10-29**. 한 대의 Windows 개발 PC / one Windows development PC.

## 이번 배포 파일 / These release binaries

| 검사 / Check | 결과 / Result |
| --- | --- |
| 실제 관찰, 저장 실패/완료, 중단, 예측 판정, 기록, 영상 시간표 / Observation, save confirmation/failure, stop, scoring, history, timing | C# 52개 통과 / 52 passed |
| 내장 음성·비무음 PCM·영상 시간·음소거·동시 화면/영상 렌더 / Bundled voices, nonzero PCM, timing, mute, concurrent rendering/export | 74개 통과 / 74 passed |
| 원문 없는 VS Code 사건 지표 / Text-free VS Code metrics | 9개 통과 / 9 passed |
| 기본·최소 창 크기 / Default and minimum editor geometry | 통과 / Passed |
| 설치 → 설치 EXE 해시 → 설치 앱 세션 시작·종료 → 제거 → 재설치 / Install, installed hash, launch/session/exit, uninstall, reinstall | 통과 / Passed |
| 앱·설치 파일·설치 등록 버전 / App, installer, registry version | 0.4.11 확인 / Verified |
| 소스 ZIP을 새 폴더에 풀어 네이티브 앱 빌드 / Build native app from freshly extracted source ZIP | 통과 / Passed |
| 공개할 MP4 전체 디코드 / Decode the entire demo MP4 | 통과 / Passed |
| 제거 시 기존 문서·녹화 보존 / Data preserved through uninstall | 문서 2개 SHA-256 및 녹화 2,788개 개수 유지 / Two document hashes and count of 2,788 recording files preserved |

설치 검사는 실제 설치·제거 코드 경로와 설치된 프로그램을 사용했습니다. 설치 마법사의 모든 버튼을 클릭한 검사는 아닙니다. / Lifecycle checks exercised the real installer/uninstaller and installed executable, not every wizard button.

## 실제 사용 장면 / Actual-use evidence

2026-10-29 경기장 디자인의 전용 샘플 창을 조작했습니다. 실제 저장 → 제목에 `?` 입력 → 담담 1점 판정 → 최종 저장이 녹화됐습니다. 101.5초의 실제 앱 창 녹화에서 앱이 25.4초 AVI를 만들었고, AVI 저장 완료를 화면으로 확인했습니다. MP4는 동일 장면의 형식 변환입니다. 샘플은 제작한 문서이며 사용자 문서나 참고 MP3가 아닙니다.

On October 29, the stadium app was used with a dedicated sample document: real save, typing `?` into the title, a one-point result for Damdam, then a final save. The app generated a 25.4-second AVI from 101.5 seconds of actual window recording, with export completion confirmed in the UI. MP4 is a format conversion of that export. No user document or reference MP3 is included.

촬영 후 종료 상태 문구와 0.4.11 배포 표기를 정리했습니다. 본문 전체를 타이핑하는 새 경기장 영상이라고 주장하지 않습니다. / An ended-session label and release metadata were updated after filming. The stadium demo shows a real one-character edit, not a full-body typing demonstration.

이전 VS Code 실제 확장 호스트 8개 통합 검사를 통과한 관찰 소스를 유지했습니다. 이번에는 버전·소개 문서를 변경했고 9개 관찰기 검사를 재실행했습니다. / The observer retains the source previously checked by eight real VS Code extension-host tests; this release reran nine observer assertions after metadata/documentation changes.

## 남은 제한 / Remaining limits

- 다른 PC, Windows 10, 고DPI, 다중 모니터는 미검증. / Other PCs, Windows 10, high DPI and multiple monitors are unverified.
- 코드 서명, Windows Store, VS Code Marketplace 등록 없음. / No code signing or Windows Store/VS Code Marketplace listing.
- 한국어 UI·음성만 제공. / Korean UI and voices only.
- 사건 규칙과 고정 AI 음성 20개로 대사 반복 가능. 의미 이해나 모든 앱 관찰 기능 없음. / Event rules and 20 fixed AI voice lines can repeat; no semantic understanding or universal app support.
- 전용 창 녹화만 지원. 약 3분, 10fps, AVI 내보내기. MP4 직접 저장·지난 녹화 재편집 UI 없음. / Own-window recording only, about three minutes at 10 fps, AVI export; no direct MP4 or past-session editing UI.
- 설정은 재시작하면 기본값. 기록/영상 자동 용량 정리 없음. / Preferences reset; no automatic storage cleanup.
- VS Code 동행 창은 일반 이동 창. 클릭 통과·자동 도킹·외부 화면 녹화 없음. / VS Code companion is a regular movable window, with no click-through, docking or external-window recording.
- Gemini 제작은 응답 fixture로만 검사. 실제 서비스/API 키/요금 검증 없음. / Optional Gemini production has fixture tests only; no live service, key or billing verification.
- 직접 수정한 대사는 Windows 음성 또는 자막으로 대체. Windows 음성의 상업 홍보 영상 재배포 권한은 별도 확인 필요. 제공 영상은 내장 Supertonic 음성만 사용. / Edited lines use Windows speech or captions. Commercial redistribution of Windows-voice promotional audio remains unverified; the supplied demo uses bundled Supertonic audio only.
- 설치 전환·다음 날 재사용·대중성은 측정하지 않음. / Install conversion, next-day retention and popularity have not been measured.

## 자산 / Assets

Original project code, scripts, UI geometry and dialogue are offered under the MIT terms in `LICENSES.txt`, within rights available to the project. The original character sheet was generated for this app with OpenAI image generation; no existing broadcast artwork or real commentator likeness/voice was copied.

The 20 bundled WAVs were generated locally using Supertonic 3 M1/M3 presets, revision `aafc6e32416a594460b32413efc49d7fe4ce6d46`. Its BigScience Open RAIL-M license includes use restrictions. Only generated WAVs are embedded, not model weights or inference libraries. The source backup contains the full license and provenance. Windows fonts and voices are not redistributed. FFmpeg was used for development-time MP4 conversion and is not bundled.

See [LICENSES.txt](../LICENSES.txt) for detailed notices and source links. A free beta is not a claim that every third-party component is unrestricted.
