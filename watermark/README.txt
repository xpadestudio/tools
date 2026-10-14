DRY RAG - XPADE / DOTHOME DEPLOYMENT

1. 이 ZIP 파일의 압축을 풉니다.
2. 닷홈 public_html 아래에 watermark 폴더를 만듭니다.
3. 압축을 푼 파일 전체를 public_html/watermark/ 안에 업로드합니다.
4. https://xpade.dothome.co.kr/watermark/ 로 접속합니다.
5. 화면 왼쪽 아래에 DRY RAG v1.3.3이 표시되는지 확인합니다.

중요:
- index.html이 public_html/watermark/index.html 위치에 있어야 합니다.
- 이전 버전 파일을 먼저 삭제한 뒤 새 파일을 올리는 것을 권장합니다.
- assets 폴더의 구조를 변경하지 마세요.
- 영상은 서버로 업로드되지 않고 사용자의 브라우저 안에서만 처리됩니다.
- MI-GAN 모델은 AI 고품질 모드를 처음 실행할 때 인터넷에서 한 번 내려받아
  해당 브라우저에 캐시합니다. Google Flow/Veo 정밀 복원에는 이 다운로드가 필요 없습니다.
- Chrome 또는 Edge 최신 버전을 권장합니다.

문제 해결:
- 빈 화면: /watermark/assets/ 폴더가 모두 업로드됐는지 확인하세요.
- 404 오류: watermark 폴더 안에 index.html이 있는지 확인하세요.
- AI 모델 다운로드 실패: 브라우저의 추적 차단 또는 네트워크 정책을 확인하세요.
- 서버에서 .htaccess 사용이 제한된 경우에도 기본 기능은 작동할 수 있습니다.

Xpade Studio
https://www.threads.com/@xpade_kr
