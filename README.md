# 방구석 중계단 · Room Commentators

**제목 하나 고쳤을 뿐인데, 결승전이 시작됐다.**

한국어 · [English](README.en.md)

혼자 쓰는 글에 두 명의 해설위원이 과몰입합니다. 호들은 흥분하고, 담담은 태연하게 받아칩니다.
이번엔 당신의 **다음 행동에 서로 다른 예측**까지 겁니다. 실제 수정과 저장으로 승부가 나고, 3점 선취로 경기가 끝납니다.

**0.4.11 무료 베타 · Windows 네이티브 앱 · 한국어 UI와 음성**

[설치 파일 받기](https://github.com/qkdlsem-maker/room-commentators/releases/download/v0.4.11/RoomCommentators-0.4.11-Setup.exe) · [릴리스와 실제 시연](https://github.com/qkdlsem-maker/room-commentators/releases/tag/v0.4.11) · [문제 제보](https://github.com/qkdlsem-maker/room-commentators/issues/new/choose)

![실제 앱의 야간 경기장 화면. 샘플 문서, 실제 판정과 점수.](docs/stadium-preview.jpg)

## 첫 경기

1. 설치한 뒤 시작 메뉴에서 **방구석 중계단**을 엽니다.
2. 전용 글쓰기 창에서 **중계 시작**을 누르고 제목을 씁니다.
3. 두 사람의 예측을 들은 뒤 제목을 고치거나 저장해 보세요.
4. 누가 맞혔는지 지켜봅니다. 작업을 멈추면 해설도 조용히 기다립니다.

음성·자막·빈도·장난 강도·중계석 배치를 조절할 수 있습니다. 버튼으로 일시정지·음소거·종료합니다.
회원가입, 친구 초대, 결제, API 키 없이 기본 기능을 쓸 수 있습니다.

## 작은 작업이 경기장이 됩니다

- 야간 경기장, LED 전광판, 팀별 예측판, 두 캐릭터의 중계석.
- 실제로 확인된 제목 수정·본문 변화·파일 저장에 반응합니다. 글의 품질을 평가하지 않습니다.
- 먼저 3점을 얻은 해설위원이 승리합니다. 경기 기록은 다음 실행에도 남습니다.
- 직접 시작한 녹화에서 연결된 예측과 판정을 골라 **15~30초 하이라이트**를 만듭니다.
- 대사를 검토·수정하고 AVI로 저장합니다. 공유는 선택입니다.

[25초 실제 화면 영상 다운로드](https://github.com/qkdlsem-maker/room-commentators/releases/download/v0.4.11/room-commentators-stadium-demo-0.4.11.mp4)

영상은 실제 앱 녹화에서 생성한 AVI를 MP4로 변환한 샘플입니다. 제목에 물음표 한 글자를 직접 입력하고 저장했습니다. 화면이나 판정을 합성하지 않았습니다. 내장 AI 음성으로 재해설하며, 마이크/타이핑 소리를 녹음한 영상은 아닙니다. 촬영 후 배포 버전 표기와 종료 상태 문구를 정리했습니다.

## 지원 범위와 베타의 한계

전용 글쓰기 창에서 전체 흐름을 지원합니다. 선택적인 VS Code 확장은 Windows의 로컬 `.txt`/`.md` 사건만 관찰하며, VS Code 화면을 녹화하지 않습니다. Word·한글·브라우저는 지원하지 않습니다.

`.NET Framework 4.8`이 필요합니다. 이 개발 PC에서 설치·실행·종료·제거를 확인했으며, Windows 10·다른 PC·고DPI·다중 모니터 검증은 남아 있습니다. 앱 UI와 대사는 한국어입니다.

**설치 파일은 서명되지 않았습니다.** Windows에서 게시자/평판 경고가 나올 수 있습니다. 출처가 불확실하면 설치를 취소하고 릴리스의 `SHA256SUMS.txt`를 확인하세요. 안정판이나 스토어 인증판이 아닙니다.

20개의 기본 AI 음성과 사건 규칙을 사용해 대사가 반복될 수 있습니다. 문장 의미를 이해하는 AI는 아닙니다. 녹화는 약 3분/10fps, AVI 저장만 지원합니다. 설정은 재실행하면 기본값으로 돌아가며 경기 기록은 유지됩니다.

[설치·사용법](docs/guide.md) · [개인정보](docs/privacy.md) · [검증과 알려진 제한](docs/verification.md) · [자산 라이선스](LICENSES.txt)

## 소스와 제보

[실행 가능한 소스 백업](https://github.com/qkdlsem-maker/room-commentators/releases/download/v0.4.11/room-commentators-source-0.4.11.zip)은 빌드 스크립트·테스트·20개 음성의 출처를 포함합니다. 이 저장소에는 소개와 지원 문서를 게시합니다.

문제가 생긴 행동과 기대한 결과를 [제보 양식](https://github.com/qkdlsem-maker/room-commentators/issues/new/choose)에 알려주세요. 이슈는 공개되므로 개인 문서와 API 키는 제외해 주세요.
