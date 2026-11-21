# archivelab-kr.github.io

`https://archivelab-kr.github.io/`(호스트 맨 위)에 올라가는 파일입니다. 앱 웹사이트는 앱마다 다른 저장소에 있습니다(모아북: `archivelab-kr/moabook` → `/moabook/`, PawShelf: `archivelab-kr/pawshelf` → `/pawshelf/`).

- `robots.txt`: 검색 엔진에 사이트맵 위치를 알립니다. 호스트 맨 위에 있어야만 읽혀서 여기에 둡니다. 앱 웹사이트를 더하면 `Sitemap:` 줄을 더합니다.
- `index.html`: 맨 위 주소의 앱 목록 페이지입니다(모아북 · PawShelf). 앱을 더하면 목록에 한 줄을 더합니다.
- `naver….html` · `google….html` 소유 확인 파일: 네이버 서치어드바이저는 호스트 단위로만 등록할 수 있고, Google Search Console은 호스트 맨 위(`https://archivelab-kr.github.io/`)를 URL 접두어 속성으로 등록해 모든 앱 페이지를 한 속성에서 봅니다. 받은 그대로 두고, 지우면 확인이 풀립니다.
