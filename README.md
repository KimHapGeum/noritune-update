# Noritune

내 노래를 반주로 만들어 부르는 Windows PC 노래방 프로그램이에요.

## 설치

[Releases](https://github.com/KimHapGeum/noritune-update/releases/latest)에서 `Noritune_<버전>_x64-setup.exe`를 받아 실행하세요.
설치한 뒤에는 프로그램이 켜질 때 새 버전을 스스로 확인해요.

"Windows의 PC 보호" 파란 창 (SmartScreen): 추가 정보 → 실행을 누르면 설치됩니다.

- Windows 10/11 64비트
- 처음 켤 때 반주 분리에 필요한 부품을 받아요 (그래픽카드용 약 3GB, 디스크 약 8GB)
- 지우기: 설정 → 앱 → 설치된 앱(또는 제어판 → 프로그램 추가/제거)에서 Noritune 제거

## Privacy policy (개인정보)

This program will not transfer any information to other networked systems unless specifically requested by the user or the person installing or operating it, except as listed below.
Noritune은 계정이 없고, 사용 기록을 모으거나 보내지 않습니다. 곡·가사·설정은 이 PC에만 저장됩니다. 아래 기능만 인터넷에 접속합니다.

| 언제 | 어디로 | 보내는 것 | 끄는 법 |
|---|---|---|---|
| 처음 켤 때, 새 버전에서 부품이 바뀔 때 | PyPI, download.pytorch.org, GitHub (python-build-standalone) | 내려받기 요청 | 없음 (반주 분리에 꼭 필요) |
| 반주 방식을 처음 쓸 때 | 분리 모델·음성 인식 모델 저장소 (GitHub, Hugging Face) | 내려받기 요청 | 그 방식을 쓰지 않으면 받지 않음 |
| 곡을 넣을 때 | lrclib.net (가사 찾기) | 곡 제목·가수·길이 | 아직 없음 (가사가 든 노래방 영상은 찾지 않음) |
| 유튜브에서 곡을 찾거나 받을 때 | YouTube (yt-dlp) | 검색어·영상 주소 | 쓰지 않으면 접속 없음 |
| 재생 화면 배경이 "유튜브 뮤비"일 때 (기본값) | YouTube (검색, 영상 재생) | 곡 제목·가수 | 설정 → 재생 화면 배경 → 기본 배경화면 |
| 켤 때 | GitHub (새 버전 확인) | 확인 요청 | 없음 |
| 일주일에 한 번 | GitHub (yt-dlp 업데이트) | 확인 요청 | 설정 → 업데이트 → yt-dlp 자동 업데이트 끄기 |
| 멀티 방에 있을 때 | 멀티 서버 (hapgeum.synology.me, 개발자의 NAS) | 닉네임, 방 코드, 채팅, 예약한 영상 번호·제목, 재생 상태 | 설정 → 멀티 끄기 (기본은 꺼짐) |
| 멀티 방에 있을 때 | 같은 방 친구 PC (직접) 또는 멀티 서버 (중계) | 목소리 (곡 중에는 부르는 사람만). 직접 연결이면 서로의 IP 주소가 보임 | 설정 → 멀티 → 중계 서버만 쓰기 / 내 마이크 끄기 |

멀티 서버는 메시지와 목소리를 전달만 하고 저장·녹음하지 않습니다. 서버 기록에는 시각, 방 코드의 해시, 오류 종류만 남고(IP·내용 없음) 오래된 기록부터 지워집니다. IP 주소는 요청 폭주를 막는 데에만 메모리에서 쓰고 저장하지 않습니다.

접속하는 곳의 개인정보 처리는 각 서비스의 정책을 따릅니다 ([YouTube](https://policies.google.com/privacy), [GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement), [Hugging Face](https://huggingface.co/privacy), [PyPI](https://policies.python.org/pypi.org/Privacy-Notice/)).

## 알아 두세요

개인 사용 목적의 프로그램이에요. 프로그램으로 받거나 만든 노래·반주·가사를 다른 사람과 공유하지 마세요 (저작권).
