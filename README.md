# Sisaemdal Tools

Cloudflare에서 구매한 `sisaemdal.com`을 기준으로 만든 사이트 패키지입니다.

## 구성

- `index.html`: 루트 홈페이지. `https://sisaemdal.com/` 접속 시 가장 먼저 보이는 범용 도구 모음 홈입니다.
- `pdf-tools.html`: PDF Tools 소개/기능 선택 페이지입니다.
- `standalone.html`: 실제 PDF 도구 실행 페이지입니다.
- `about.html`: 사이트 소개입니다.
- `privacy.html`: 개인정보처리방침입니다.
- `terms.html`: 이용약관입니다.
- `contact.html`: GitHub Issues 문의 페이지입니다.
- `sitemap.xml`: 검색엔진 제출용 사이트맵입니다.
- `robots.txt`: 검색엔진 크롤링 안내 파일입니다.
- `_headers`: Cloudflare Pages 보안 헤더 예시입니다.
- `_redirects`: `www` 및 짧은 경로 리다이렉트 예시입니다.
- `ads.txt.sample`: AdSense 승인 후 사용할 ads.txt 샘플입니다.

## 배포 전 확인

1. Cloudflare Pages 또는 Workers Custom Domain에 `sisaemdal.com`을 연결합니다.
2. 대표 주소는 `https://sisaemdal.com/`으로 통일하는 것을 권장합니다.
3. `https://www.sisaemdal.com/`은 `https://sisaemdal.com/`으로 리다이렉트하세요.
4. GitHub Issues 문의 주소는 `https://github.com/sisaem/tools/issues`로 반영되어 있습니다.
5. AdSense 승인 후 `ads.txt.sample`의 Publisher ID를 실제 값으로 교체하고 파일명을 `ads.txt`로 변경하세요.

## 추천 URL 구조

- 홈: https://sisaemdal.com/
- PDF Tools: https://sisaemdal.com/pdf-tools.html
- PDF 도구 실행: https://sisaemdal.com/standalone.html
- 개인정보처리방침: https://sisaemdal.com/privacy.html
- 이용약관: https://sisaemdal.com/terms.html
- 문의: https://sisaemdal.com/contact.html
