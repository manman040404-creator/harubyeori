# 하루벼리 GitHub Pages 배포용 v0.4

추가 기능:
- 전체 백업: 글 기록 + 사진 + 사진 메모를 JSON 파일로 저장
- 백업 불러오기: 다른 컴퓨터/휴대폰에서 JSON 파일로 기록 복원
- 기존 v0.3/v0.2/v0.1 텍스트 기록 자동 이전
- 사진은 IndexedDB에 저장하고, 전체 백업 시 JSON에 포함

주의:
- 전체 백업 JSON에는 개인 사진 데이터가 포함됩니다. 지인에게 보내거나 클라우드에 올릴 때 주의하세요.
- 사진이 많으면 JSON 파일 용량이 커질 수 있습니다.
- 날짜별 대표 사진 1~2장 용도에 적합합니다.

업로드:
이 폴더 안의 파일들을 GitHub 저장소 최상단(root)에 덮어쓰기 업로드하세요.

필수 파일:
index.html
manifest.webmanifest
sw.js
icon-192.png
icon-512.png
.nojekyll
README.txt
