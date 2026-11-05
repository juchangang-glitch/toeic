MY TOEIC QUEST - 안드로이드 설치형 웹앱(PWA) 초안

구성
- index.html: 앱 본체
- manifest.webmanifest: 홈 화면 설치 정보
- sw.js: 오프라인 캐시
- 학습 기록은 브라우저 localStorage에 저장됩니다.

안드로이드 설치
1. 이 프로젝트를 HTTPS를 지원하는 웹 호스팅(GitHub Pages 등)에 올립니다.
2. 안드로이드 Chrome에서 배포 주소를 엽니다.
3. 메뉴(⋮) > 앱 설치 또는 홈 화면에 추가를 선택합니다.
4. 설치 후 MY TOEIC QUEST 아이콘으로 실행합니다.

중요
- 이 파일은 APK가 아니라 안드로이드에 홈 화면 설치가 가능한 PWA 프로젝트입니다.
- 현재 환경에는 Android SDK/Gradle 빌드 도구가 없어 APK 바이너리는 생성하지 않았습니다.
- 실제 교재의 세부 Day별 목차는 제공되지 않아, 진도 구간과 학습 유형 중심으로 일정이 자동 배정됩니다.
- 시작일은 앱 설정에서 변경할 수 있습니다.
