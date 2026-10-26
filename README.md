# 수성시스템스 홈페이지

주식회사 수성시스템스 회사소개 홈페이지 — https://suseongsystems.com

정적 사이트(HTML 한 장)이며 GitHub Pages로 게시합니다. 빌드 과정이 없어서 `main` 브랜치에 올린 파일이 그대로 공개됩니다.

## 구성

| 경로 | 내용 |
| --- | --- |
| `index.html` | 홈페이지 본문 (3D 라인 애니메이션 포함) |
| `fonts/` | Pretendard 서브셋 (SIL OFL, 회사 디자인 시스템) |
| `js/three.min.js` | three.js r128 (MIT) |
| `og-image.png` | 카카오톡·네이버 링크 공유 이미지 (1200×630) |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | 사이트 아이콘 |
| `logo.png` | 검색엔진 구조화 데이터용 로고 |
| `robots.txt`, `sitemap.xml` | 검색엔진 등록용 |
| `CNAME` | 사용자 도메인 `suseongsystems.com` |
| `404.html` | 없는 주소로 들어왔을 때 보여 주는 페이지 |

## 도메인 연결 (가비아 DNS)

- `@` A 레코드 4개: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- `www` CNAME: `manjinchoi.github.io.`
- 회사 메일(하이웍스)용 MX·TXT 레코드는 건드리지 않습니다.
- GitHub Pages 설정에서 **Enforce HTTPS**를 켜 두었습니다. `http://`와 `www.` 주소는 모두 `https://suseongsystems.com/`으로 넘어갑니다.

## 검색엔진 등록

- `index.html`의 `<head>` 안에 네이버 서치어드바이저 소유확인 태그(`<meta name="naver-site-verification" …>`)가 들어 있습니다. 지우면 소유확인이 풀리므로, `index.html`을 새로 만들 때도 이 줄은 그대로 둡니다.
- 사이트맵: https://suseongsystems.com/sitemap.xml — 내용을 크게 바꾸면 `lastmod` 날짜도 고칩니다.
