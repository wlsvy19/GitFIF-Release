# GitFIF

**GitFIF**는 GitKraken처럼 그래프 기반으로 Git 이력을 보고, 여러 저장소를 탭으로 관리할 수 있는 데스크톱 Git 클라이언트입니다. 이름은 **Flame In Frozen**의 약자로, “머리는 차갑게, 가슴은 뜨겁게” Git 작업을 다루자는 뜻을 담았습니다.

![GitFIF Desktop 화면](assets/gitfif-desktop.png)

이 저장소는 GitFIF 실행 파일 다운로드 전용 저장소입니다. Windows와 macOS에서 바로 설치하거나 실행할 수 있는 배포 파일만 제공합니다.

## 만든 이유

GitKraken Desktop 무료 버전은 private repository나 self-hosted repository를 열 때 업그레이드를 요구합니다.

GitFIF는 이 불편함에서 출발했습니다. private repository도 보기 좋은 그래프 UI로 편하게 열고, pull/push/commit/diff 같은 일상적인 Git 작업을 무료로 사용할 수 있게 만드는 것이 목표입니다.

GitFIF는 GitKraken과 별개의 독립 프로젝트입니다. GitKraken은 해당 소유자의 상표입니다.

## 핵심 방향

- private repository와 self-hosted repository도 무료로 사용할 수 있는 Git 클라이언트
- GitKraken처럼 커밋 이력을 그래프 형태로 한눈에 확인
- 여러 프로젝트를 탭으로 열고 전환
- 변경 파일, staged/unstaged 상태, diff, commit, pull, push를 한 화면에서 처리
- Windows에서 먼저 안정적으로 사용하고, macOS에서도 이어서 사용할 수 있도록 배포

## 주요 기능

- 여러 Git 프로젝트 탭 관리
- 커밋 그래프, branch/tag, commit message, author, date/time, SHA 컬럼 표시
- 컬럼 표시 여부 설정 및 컬럼 너비 조절
- branch와 author 기준 커밋 필터링
- Pull, Push, Fetch, Rebase 등 Git 동기화 작업
- Unstaged/Staged 파일 관리
- 커밋 메시지 작성, commit, commit and push
- 변경 파일 diff 확인
- Hunk View, Inline View, Split View
- Repository Management 화면

## 다운로드

| OS | 파일 |
| --- | --- |
| Windows x64 설치 파일 | [GitFIF-Windows.exe](https://github.com/wlsvy19/GitFIF-Release/releases/latest/download/GitFIF-Windows.exe) |
| macOS Apple Silicon | [GitFIF-macOS.dmg](https://github.com/wlsvy19/GitFIF-Release/raw/main/downloads/GitFIF-macOS.dmg) |

## 사용 방법

### Windows

1. `GitFIF-Windows.exe`를 다운로드해 실행합니다.

### macOS

1. `GitFIF-macOS.dmg`를 다운로드합니다.
2. DMG 파일을 엽니다.
3. `GitFIF.app`을 실행하거나 Applications 폴더로 옮겨 사용합니다.

## 무결성 확인

다운로드 파일의 SHA-256 해시는 [SHA256SUMS.txt](SHA256SUMS.txt)에서 확인할 수 있습니다.

## 라이선스

GitFIF는 무료로 사용할 수 있습니다. 개인, 학습, 내부 업무, 개발 목적의 설치와 사용을 허용합니다.

다만 GitFIF의 저작권과 소유권은 wlsvy19에게 있습니다. GitFIF, 소스 코드, 패키징된 실행 파일, 수정 버전을 판매하거나 유료 상품/서비스/번들에 포함하는 행위는 사전 서면 허가 없이 금지됩니다.

자세한 내용은 [LICENSE](LICENSE)를 확인하세요.
