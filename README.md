# A Fisherman’s Tale 한글패치

VR 유튜브 크리에이터 **제콜(ZECOLE)** 님이 제작한 비공식 한글패치입니다.

게임 자막과 메뉴·설정·조작 안내·로딩 화면 등 인터페이스를 한글화했습니다. 영어 음성은 유지합니다.
번역 패치 v1.0.0 / Windows 통합 설치 도구 v1.1.3 (빌드 20261021.2)

## 다운로드와 지원 버전

**설치 파일 하나로 PCVR과 Quest를 모두 지원합니다.**

GitHub 로그인 없이 다운로드할 수 있습니다. 오역·미번역 제보를 작성할 때에는 GitHub 로그인이 필요합니다.

[최신 통합 설치기 EXE 다운로드](https://github.com/zecole-vr/a-fishermans-tale-korean-patch/releases/download/v1.1.3/A-Fishermans-Tale_PCVR-Quest_Windows_v1.0.0_Setup_1.1.3.exe) · [최신 릴리스](https://github.com/zecole-vr/a-fishermans-tale-korean-patch/releases/latest)

`A-Fishermans-Tale_PCVR-Quest_Windows_v1.0.0_Setup_1.1.3.exe`

| 게임 플랫폼 | 지원 게임 |
|---|---|
| Steam · PCVR | Steam 빌드 16681690 |
| Meta Quest · Standalone | 1.087 / 버전 코드 25 |

EXE와 설명서·라이선스를 담은 동일 이름의 **암호 없는 ZIP**도 제공합니다.
ZIP은 전부 압축 해제한 뒤 EXE를 실행해 주세요. `Code → Download ZIP`은 설치용 배포 파일이 아닙니다.
릴리스의 `SHA256SUMS_Setup_1.1.3.txt`에서 새 배포 파일의 체크섬을 확인할 수 있습니다. Quest용은 Windows PC에서 USB로 설치하는 도구입니다.

배포 릴리스 **v1.1.3**는 설치 도구 버전이며, 번역 패치 버전은 별도로 관리합니다. 업데이트마다 새 태그와 릴리스를 게시합니다.

**설치기 1.1.2 이하 사용자는 위 EXE를 직접 내려받아 실행해 주세요.** 기존 설치기의 검색 방식으로는 새 릴리스를 인식하지 못할 수 있습니다. 백업과 설치 기록은 유지됩니다.

Quest의 긴 경로 오류를 보완하고 임시 작업 경로를 `%LOCALAPPDATA%\AFT\w`로 단축했습니다. 원본 추출 후 경로 오류가 발생했다면 새 설치기로 다시 시도해 주세요.

## 설치법

1. 정식 게임을 설치하고 완전히 종료합니다.
2. 통합 EXE를 실행합니다.
3. Quest는 개발자 모드를 준비하고 USB로 연결한 뒤 헤드셋에서 USB 디버깅을 허용합니다.
4. Steam 게임이나 연결된 Quest 중 하나만 발견되면 플랫폼이 자동 선택됩니다. 둘 다 있으면 상단에서 **Steam · PCVR** 또는 **Meta Quest · Standalone**을 선택합니다.
5. **한글패치 설치**를 누릅니다. 선택한 플랫폼에 대상이 여러 개이거나 자동 탐색이 실패하면 폴더/기기를 선택합니다.
6. 완료 메시지 후 게임을 실행합니다. **화면 언어 English / 음성 언어 English / 자막 켜짐**으로 설정합니다.

Quest는 원본 백업과 한글 데이터 생성·전송에 수 분이 걸릴 수 있습니다. 완료 전에 케이블을 뽑거나 게임을 실행하지 마세요.
Steam은 필요한 경우 Windows 관리자 권한을 요청합니다. 실행 중인 게임을 자동 강제 종료하지 않습니다.
같은 한글패치가 있으면 파일을 확인하고 설치 기록을 갱신합니다. 게임 버전과 해시가 지원 범위 밖이면 중단합니다.

## 제거·원본 복구

게임을 종료하고 통합 EXE에서 복구할 플랫폼을 선택하고 **제거 · 원본 복구**를 누르세요. Quest는 USB 연결이 필요합니다.
Steam은 추가한 한글 PAK만 제거합니다. Quest는 검증된 영어 원본 OBB를 복원하며 APK 재설치/앱 삭제를 하지 않습니다.
저장 데이터는 유지되며 백업도 보관합니다. 다른 모드나 별도 음성 교체까지 복구하는 도구는 아닙니다.

백업·설치 기록·로그는 `%LOCALAPPDATA%\ZECOLE\A-Fishermans-Tale\Steam` 또는 `Quest` 아래에 저장됩니다.
설치기를 이동하거나 다시 받아도 같은 Windows 사용자에서 이 기록을 사용합니다. 플랫폼을 바꾸어도 다른 플랫폼의 게임·백업은 변경하지 않습니다.
기존 분리형 EXE 1.0.0 사용자는 통합 EXE를 직접 내려받아 실행해 주세요. 기존 설치 기록과 백업 경로를 이어서 사용합니다. 분리형 설치기의 자동 업데이트 검색은 새 통합 파일 이름을 인식하지 못할 수 있습니다.
Quest의 이전 ZIP판 백업(`%LOCALAPPDATA%\zecole-vr\A-Fishermans-Tale-Quest\기기번호`)은 원본 해시 확인 후 복사하여 사용합니다.
기기 OBB 폴더의 `.zecole-original` 백업도 확인합니다. 이전 백업을 패치 파일로 덮어쓰지 않습니다.
Steam 이전 ZIP판은 알려진 패치 해시로 인식하여 기록을 만듭니다. 기존 `zecole-patch-backups`는 유지합니다.
중단 후에는 다시 연결하고 EXE에서 설치/복구를 실행하세요. 불명확한 파일/백업은 자동 삭제하지 않으므로 오류 로그와 함께 문의해 주세요.
게임 업데이트 후에는 지원 여부를 확인하세요. 다른 버전에 과거 원본 백업을 강제로 적용하지 않습니다.

## 필요한 환경

- Windows 10/11 64비트, Microsoft Edge WebView2 Runtime, .NET Framework 4.8.
- Python과 패치 엔진은 EXE에 포함됩니다. Quest용에는 ADB 36.0.0 및 repak 0.2.3이 포함됩니다.
- WebView2와 .NET은 Windows에 설치된 것을 사용합니다. 미설치 시 시작 안내창에서 [예]를 누르면 필요한 Microsoft 공식 설치 페이지가 열립니다. 설치 후 [다시 시도]를 누르거나 재부팅 후 EXE를 다시 실행하세요. 이미 설치돼 있으면 바로 런처가 열립니다. 공식 페이지: [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/), [.NET 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48).
- Steam: 게임 드라이브와 백업 드라이브에 각각 32MB 이상. EXE 임시 실행용 200MB 이상.
- Quest: PC 백업 드라이브 15GB, 기기 5GB 여유 공간. 복구는 PC 3GB / 기기 5GB. EXE 임시 실행용 200MB 이상.
- 내장 패치 설치는 인터넷 없이 가능합니다. GitHub 버전 확인과 업데이트 다운로드에는 인터넷이 필요합니다.

통신 오류나 GitHub API 제한으로 최신 버전을 조회하지 못하면 **버전 확인 실패**로 표시됩니다. ‘다시 확인’으로 재시도할 수 있습니다.
별도 개발 환경이 없는 새 Windows PC 및 고배율 DPI 실기 검증은 아직 완료하지 않았습니다.

## 폰트·출처

**나눔고딕(Nanum Gothic)** 일반체와 굵은체를 사용하며 게임 내 크기와 거리를 조정했습니다. 폰트를 따로 설치할 필요는 없습니다.
나눔고딕의 저작권 고지(NHN Corporation) 및 SIL Open Font License 1.1 전문을 `licenses/NanumGothic-OFL.txt`에 동봉합니다.
외부 도구·라이브러리 고지는 `licenses`와 `COMPONENTS.json`에 포함했습니다. 실행 중 도움말에서도 라이선스 폴더를 열 수 있습니다.
게임/배너 자산의 권리는 원저작자에게 있습니다. 설치기 코드의 권리를 번역·폰트·게임 자산 전체에 일괄 적용하지 않습니다.

## 오역·미번역 제보

오역이나 미번역을 발견하시면 [GitHub Issues](https://github.com/zecole-vr/a-fishermans-tale-korean-patch/issues/new/choose)에 남겨 주세요.
문제가 나온 챕터·상황과 사용 플랫폼을 적어 주시고, **가능하면 스크린샷도 함께 첨부**해 주세요.

제작: VR 유튜브 크리에이터 제콜 · [YouTube](https://www.youtube.com/@zecole) · [GitHub](https://github.com/zecole-vr/a-fishermans-tale-korean-patch)

