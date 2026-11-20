# dev-bestow.github.io

Dev-BestOW 조직의 GitHub Pages 루트(호스트 단위) 사이트예요.

- `index.html` — 루트로 온 사람·검색 엔진을 [BestOW UI 소개 사이트](https://bestow-ui.com/)로 바로 보내요(canonical 도 새 주소). GitHub Pages 는 루트에 301 을 걸 수 없어 meta refresh 를 쓴다.
- `robots.txt` — 호스트 루트에서만 읽혀요. 사이트맵은 적지 않아요(bestow-ui.com 의 주소는 이 호스트와 달라 네이버가 이 사이트의 사이트맵으로 받지 않음).
- `naver*.html` — 네이버 서치어드바이저 소유 확인 파일. **지우면 확인이 풀려요.** 서치어드바이저에서 이 사이트 등록을 지운 뒤(2026-12 예정)에 지운다.
- `.nojekyll` — Jekyll 처리 끄기.

실제 사이트는 [Dev-BestOW/BestOW-UI](https://github.com/Dev-BestOW/BestOW-UI) 저장소가 사용자 도메인 https://bestow-ui.com/ 에 배포해요(옛 `/BestOW-UI/` 경로는 GitHub 가 같은 경로로 301).
이 저장소에 `BestOW-UI` 폴더를 만들지 마세요(경로가 겹쳐요).
