# A Fisherman’s Tale 한글패치

> **설치는 [ZECOLE VR 런처](https://github.com/zecole-vr/zecole-launcher)로 하세요.**  
> 런처 하나로 이 한글패치를 설치·업데이트·원본 복구할 수 있습니다. → **[ZECOLE_Launcher.exe 받기](https://github.com/zecole-vr/zecole-launcher/releases/latest/download/ZECOLE_Launcher.exe)** (설치 없이 바로 실행)

VR 유튜브 크리에이터 **제콜(ZECOLE)** 님이 제작한 비공식 한글패치입니다.

게임 자막과 메뉴·설정·조작 안내·로딩 화면 등 인터페이스를 한글화했습니다. 영어 음성은 유지합니다.
번역 패치 v1.0.0

## 지원 버전

**런처 하나로 PCVR과 Quest를 모두 지원합니다.** 런처 왼쪽 목록의 **A Fisherman's Tale**에서 Steam판과 Quest판을 고를 수 있습니다.

| 게임 플랫폼 | 지원 게임 |
|---|---|
| Steam · PCVR | Steam 빌드 16681690 |
| Meta Quest · Standalone | 1.087 / 버전 코드 25 |

`Code → Download ZIP`과 GitHub의 `Source code` 파일은 설치용이 아닙니다. Quest판은 Windows PC에서 USB로 설치합니다.

## 설치법

1. 정식 게임을 설치하고 완전히 종료합니다.
2. [ZECOLE VR 런처](https://github.com/zecole-vr/zecole-launcher/releases/latest/download/ZECOLE_Launcher.exe)를 실행하고 왼쪽 목록에서 **A Fisherman's Tale**을 고릅니다.
3. Quest판은 개발자 모드를 준비하고 USB로 연결한 뒤 헤드셋에서 USB 디버깅을 허용합니다.
4. 설치할 플랫폼(Steam 또는 Quest)을 고르고 **한글패치 설치**를 누릅니다.
5. 완료 메시지 후 게임을 실행합니다. **화면 언어 English / 음성 언어 English / 자막 켜짐**으로 설정합니다.

Quest는 원본 백업과 한글 데이터 생성·전송에 수 분이 걸릴 수 있습니다. 완료 전에 케이블을 뽑거나 게임을 실행하지 마세요.
Steam은 필요한 경우 Windows 관리자 권한을 요청합니다. 실행 중인 게임을 자동 강제 종료하지 않습니다.
같은 한글패치가 있으면 파일을 확인하고 설치 기록을 갱신합니다. 게임 버전과 해시가 지원 범위 밖이면 중단합니다.
새 한글패치 버전이 나오면 런처가 **업데이트 있음**으로 알려 주며, 같은 화면에서 설치하면 됩니다.

## 제거·원본 복구

게임을 종료하고 런처에서 복구할 플랫폼을 고른 뒤 **원본 복구**를 누르세요. Quest는 USB 연결이 필요합니다.
Steam은 추가한 한글 PAK만 제거합니다. Quest는 검증된 영어 원본 OBB를 복원하며 APK 재설치/앱 삭제를 하지 않습니다.
저장 데이터는 유지되며 백업도 보관합니다. 다른 모드나 별도 음성 교체까지 복구하는 도구는 아닙니다.

백업·설치 기록·로그는 `%LOCALAPPDATA%\ZECOLE\A-Fishermans-Tale\Steam` 또는 `Quest` 아래에 저장됩니다.
예전 설치기 EXE로 설치했어도 런처가 같은 Windows 사용자의 기록과 백업을 이어서 사용합니다. 플랫폼을 바꾸어도 다른 플랫폼의 게임·백업은 변경하지 않습니다.
Quest의 이전 ZIP판 백업(`%LOCALAPPDATA%\zecole-vr\A-Fishermans-Tale-Quest\기기번호`)은 원본 해시 확인 후 복사하여 사용합니다.
기기 OBB 폴더의 `.zecole-original` 백업도 확인합니다. 이전 백업을 패치 파일로 덮어쓰지 않습니다.
Steam 이전 ZIP판은 알려진 패치 해시로 인식하여 기록을 만듭니다. 기존 `zecole-patch-backups`는 유지합니다.
중단 후에는 다시 연결하고 런처에서 설치/복구를 실행하세요. 불명확한 파일/백업은 자동 삭제하지 않으므로 오류 로그와 함께 문의해 주세요.
게임 업데이트 후에는 지원 여부를 확인하세요. 다른 버전에 과거 원본 백업을 강제로 적용하지 않습니다.

## 필요한 환경

- Windows 10/11 64비트, Microsoft Edge WebView2 Runtime, .NET Framework 4.8. 공식 페이지: [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/), [.NET 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48).
- Steam: 게임 드라이브와 백업 드라이브에 각각 32MB 이상.
- Quest: PC 백업 드라이브 15GB, 기기 5GB 여유 공간. 복구는 PC 3GB / 기기 5GB. 처음 한 번 연결 도구(ADB)를 약관 동의 후 받습니다.
- 한글패치 데이터 다운로드와 버전 확인에는 인터넷이 필요합니다.

## 폰트·출처

**나눔고딕(Nanum Gothic)** 일반체와 굵은체를 사용하며 게임 내 크기와 거리를 조정했습니다. 폰트를 따로 설치할 필요는 없습니다.
나눔고딕의 저작권 고지(NHN Corporation) 및 SIL Open Font License 1.1 전문을 `licenses/NanumGothic-OFL.txt`에 동봉합니다.
외부 도구·라이브러리 고지는 `licenses`와 `COMPONENTS.json`에 포함했습니다.
게임/배너 자산의 권리는 원저작자에게 있습니다. 설치기 코드의 권리를 번역·폰트·게임 자산 전체에 일괄 적용하지 않습니다.

## 오역·미번역 제보

오역이나 미번역을 발견하시면 [GitHub Issues](https://github.com/zecole-vr/a-fishermans-tale-korean-patch/issues/new/choose)에 남겨 주세요.
문제가 나온 챕터·상황과 사용 플랫폼을 적어 주시고, **가능하면 스크린샷도 함께 첨부**해 주세요.

제작: VR 유튜브 크리에이터 제콜 · [YouTube](https://www.youtube.com/@zecole) · [GitHub](https://github.com/zecole-vr/a-fishermans-tale-korean-patch)
