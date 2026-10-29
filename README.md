# YT Downloader

YouTube 영상과 Shorts를 원하는 화질·코덱·자막으로 저장하는 Windows 프로그램입니다.
설치 없이 파일 하나로 실행되고, 서버 없이 내 PC에서만 동작하며, YouTube 로그인이 필요 없습니다.

## 다운로드

**[YT-Downloader.exe 받기 (약 8 MB)](https://github.com/CHOL2ing/yt-downloader-releases/releases/latest/download/YT-Downloader.exe)**
· [모든 버전 보기](https://github.com/CHOL2ing/yt-downloader-releases/releases)

Windows 10/11 (64비트). 받은 파일을 원하는 폴더에 두고 실행하면 됩니다.

## 처음 실행할 때

1. 영상 처리 도구(yt-dlp, Deno, FFmpeg)를 각 공식 배포처에서 한 번 받습니다. (약 150 MB, 체크섬 검증)
2. 바탕화면·시작 메뉴 바로가기를 만들지 고를 수 있습니다.

## 실행할 때 경고가 뜨면

아직 코드 서명이 없는 개인 프로그램이라 Windows가 경고를 띄울 수 있습니다.

- **"Windows의 PC 보호"** 파란 창 → **[추가 정보]** → **[실행]**
- **"스마트 앱 컨트롤이 이 앱을 차단했습니다"** → 스마트 앱 컨트롤이 켜진 PC에서는 실행할 수 없습니다.
  `Windows 보안 → 앱 및 브라우저 컨트롤 → 스마트 앱 컨트롤 설정`에서 끈 뒤 실행해 주세요.
- **아무 창도 뜨지 않으면** → 오래된 Windows 10에는 화면 표시 엔진이 없을 수 있습니다.
  [Microsoft Edge WebView2 런타임](https://developer.microsoft.com/microsoft-edge/webview2/)의 "Evergreen Bootstrapper"를 설치한 뒤 다시 실행해 주세요.

## 업데이트

새 버전이 나오면 프로그램을 켤 때 알려 드립니다. **[지금 업데이트]**를 누르면 서명을 확인한 뒤 프로그램 파일을 바꾸고 다시 시작합니다.
영상 처리 도구 yt-dlp는 실행할 때마다 자동으로 최신 버전이 됩니다.

## 삭제

프로그램의 **정보 → 프로그램 삭제**를 누르면 바로가기, 받은 도구, 설정, 프로그램 파일을 지우고 종료합니다. (받아 둔 영상은 지우지 않습니다)

## 이용 안내

본인이 올린 영상, 크리에이티브 커먼즈(CC) 영상, 개인 학습용으로만 사용해 주세요.
이 프로그램은 오픈소스 [yt-dlp](https://github.com/yt-dlp/yt-dlp), [FFmpeg](https://ffmpeg.org), [Deno](https://deno.com)를 함께 사용합니다.

만든이: CHOL2ing
