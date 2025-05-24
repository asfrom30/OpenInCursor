# OpenInCursor

> 이 프로젝트는 [OpenInCode](https://github.com/sozercan/OpenInCode)와 [iTerm2 Finder 통합 가이드](https://schlining.medium.com/integrate-iterm2-v-3-with-your-macs-finder-f3825acd3e0b)에서 영감을 받았습니다.

OpenInCursor는 macOS Finder에서 현재 경로를 Cursor 에디터로 즉시 열 수 있게 해주는 도구입니다.

## 빌드 방법

1. **Script Editor** 열기
2. `src/` 폴더의 스크립트 파일을 Script Editor로 열기
3. **파일 > 내보내기** (File > Export) 선택
4. **파일 포맷**을 **Application**으로 설정
5. 원하는 위치에 저장하면 실행 가능한 바이너리(.app)가 생성됩니다

빌드된 앱을 Finder 툴바에 드래그하여 사용할 수 있습니다.

## 설치 방법

1. 빌드된 바이너리 파일(.app)을 **Applications** 폴더로 이동
2. Finder 창을 열고 툴바 영역에서 **우클릭**
3. **툴바 사용자 정의** (Customize Toolbar) 선택
4. Applications 폴더에서 OpenInCursor.app을 Finder 툴바로 **드래그**
5. **완료** 클릭

이제 Finder에서 어떤 폴더에 있든 툴바의 OpenInCursor 아이콘을 클릭하면 해당 경로가 Cursor에서 열립니다.
