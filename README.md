# hoho studio 웹사이트

[hohostudio.co.kr](https://hohostudio.co.kr) 정적 사이트.

## 구조

- `index.html` — 홈 (placeholder, 추후 회사·앱 랜딩으로 확장)
- `privacy.html` — 키즈 건강 비서 개인정보처리방침
- `terms.html` — 키즈 건강 비서 이용약관
- `style.css` — 공통 스타일

평범한 정적 HTML. 빌드 단계 없음.

## 로컬 확인

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## 배포

Cloudflare Pages + GitHub 연동. `main` 브랜치 push 시 자동 배포.

## 페이지 추가

새 HTML 파일 만들고 `<head>`에 `<link rel="stylesheet" href="/style.css" />`만 넣으면 동일한 톤으로 따라옴.
