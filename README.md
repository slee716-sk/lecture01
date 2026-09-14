# lecture01 — 이수경 소개 페이지

실용화법 수업 「5분 자유주제 발표」 내용을 정리한 개인 소개 페이지입니다.

- 발표 주제: 정차된 차량을 박았을 때의 올바른 대처 방법
- 단일 `index.html` (외부 의존성 없음, Google Fonts만 사용)
- 배포 주소: https://lecture01.tnrud3.workers.dev

## 로컬에서 보기

`index.html`을 브라우저에서 열면 됩니다.

## 배포 (Cloudflare)

```
npx wrangler deploy
```

`wrangler.jsonc`의 `assets.directory`가 `.`이라 이 폴더가 그대로 정적 사이트로 올라갑니다.
`.assetsignore`에 적힌 파일(`.git`, `README.md`, 설정 파일)은 업로드에서 제외됩니다.
