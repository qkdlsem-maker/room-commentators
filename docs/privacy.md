# 개인정보 / Privacy

## 한국어

기본 기능은 기기 안에서 동작합니다. 계정, 분석/추적 전송, 전역 키보드 감시, 마이크 수집, 전체 화면 상시 녹화는 없습니다. 사용자가 시작한 지원 대상의 세션만 관찰하며 일시정지/종료로 즉시 중단합니다. 음소거는 소리만 중단합니다.

전용 편집기의 글은 직접 저장할 때 기기에 기록됩니다. 녹화는 명시적으로 시작한 앱 창을 이미지로 보관합니다. 경기 기록에는 날짜·점수·승자만 보관하고 원문을 넣지 않습니다. VS Code는 선택 문서의 세션별 제목 식별자·길이·삭제량·저장 사건만 로컬 중계 창으로 전달하며 원문/경로를 보내지 않습니다.

`%LOCALAPPDATA%\RoomCommentators`의 `Documents`, `Recordings`, `Season`, `VoicePacks`에 해당 자료가 저장됩니다. 자동 업로드·공유·업데이트 다운로드·자동 용량 정리는 없습니다. 앱 제거 후에도 개인 자료는 보존합니다.

선택적인 Gemini 제작 창에서 사용자가 키를 넣고 제작을 누를 때만 고정 대사와 말투 지시를 Google에 보냅니다. 작업 문서·화면·경기 기록은 보내지 않습니다. 키는 파일에 저장하지 않고 창을 닫으면 입력을 지웁니다. 기본 음성에는 이 기능이 필요 없습니다. 실제 서비스 검증은 남아 있고 요금/서비스 조건은 사용자 Google 프로젝트에 따릅니다.

GitHub 릴리스 다운로드와 이슈는 GitHub 서비스입니다. 이슈는 공개되므로 비밀번호·API 키·개인 원고를 올리지 마세요. 앱이 제보를 자동 전송하지 않습니다.

## English

Core features run locally. There are no accounts, analytics uploads, global keylogging, microphone collection or continuous desktop recording. Only an explicitly started, supported session is observed. Pause/stop ends observation; mute affects audio only.

Writing is saved locally when you choose Save. Explicit recordings store images of this app window. Match history contains dates, scores and winners, not document content. The VS Code companion passes a session-specific title identifier, length, deletions and save events locally; it does not send raw text or paths.

Data lives under `%LOCALAPPDATA%\RoomCommentators` in `Documents`, `Recordings`, `Season` and `VoicePacks`. No automatic uploads, sharing, update downloads or storage cleanup. Uninstalling preserves personal files.

The optional Gemini voice-production window sends fixed commentary lines and style instructions to Google only after you enter your key and choose Generate. It does not send your writing, screen or match history. The key is not saved to a file and its field is cleared on close. Core voices need no API. Live service verification remains incomplete; your Google project's terms and quotas/pricing apply.

Release downloads and issue reports use GitHub. Reports are public; exclude passwords, API keys and private writing. The app never files a report automatically.
