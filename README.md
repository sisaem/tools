# 시샘달 도구함 (sisaemdal.com)

브라우저에서 파일을 처리하는 무료 웹 도구와 사용 설명 글.

## 구조

- `index.html` 처음 화면(작업 검색)
- 도구: `pdf-tools`, `image-tools`, `text-tools`, `qr-tools`, `calculator-tools`, `more-tools`, `document-tools`, `annual-leave`, `workdays`
- 글: `guide`(목록)와 `*-guide` 10편
- 안내: `about`, `faq`, `contact`, `privacy`, `terms`, `404`
- 공통 스타일: `assets/site.css`
- `_redirects`: 합쳐진 예전 주소를 새 주소로 301 이동
- `_headers`: 보안 헤더, `ads.txt`를 text/plain으로

## 배포 전 확인

1. `contact@sisaemdal.com`이 실제로 메일을 받는지 확인 (Cloudflare Email Routing 등으로 개인 메일에 연결)
2. `https://sisaemdal.com/ads.txt`가 브라우저에서 텍스트 한 줄로 열리는지 확인
3. 공휴일 목록(`workdays`) 갱신 시 페이지 상단 고친 날짜도 함께 수정
