Face Liquify v1.9.5 PWA

배포 방법
1. 이 폴더의 파일 구조를 그대로 HTTPS 웹서버에 업로드합니다.
2. 앱 진입 파일은 index.html 입니다.
3. Service Worker 때문에 file:// 로 직접 열면 PWA 설치/캐시가 동작하지 않습니다. 로컬 테스트는 localhost를 사용하세요.
4. 첫 실행에는 Human 라이브러리/얼굴 모델 다운로드를 위해 인터넷 연결이 필요할 수 있습니다. 이후 불러온 CDN/모델 리소스는 Service Worker 런타임 캐시에 저장됩니다.
5. index-dev.html은 수정용 원본이며 실제 배포에서는 제거해도 됩니다.

아이콘/테마 컬러: #D4FB08
