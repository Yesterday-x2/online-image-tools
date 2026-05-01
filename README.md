# 통합 이미지 유틸리티 온라인 배포본

이 폴더는 정적 호스팅에 그대로 올릴 수 있는 배포용 파일입니다.

## 파일

- `index.html`: 실제 이미지 도구와 광고 슬롯 자리
- `privacy.html`: 개인정보 처리방침
- `terms.html`: 이용 안내
- `contact.html`: 문의 페이지

## 배포

GitHub Pages, Cloudflare Pages, Vercel 같은 정적 호스팅에 이 폴더를 업로드하면 됩니다.

## 광고

AdSense 자동 광고 스크립트는 `index.html`의 `<head>`에 들어 있습니다.

`ads.txt`에는 다음 판매자 정보가 들어 있습니다.

```txt
google.com, pub-3470479809322768, DIRECT, f08c47fec0942fa0
```

## 주의

현재 도구는 사용자가 선택한 파일을 서버로 업로드하지 않고 브라우저 안에서 처리합니다.
