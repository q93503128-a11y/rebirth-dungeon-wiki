# 환생의 던전 위키 개발로그

## 2026-06-23

- 최신 ZIP의 `docs/PROJECT_DEV_MEMORY.md`, `docs/GAME_WIKI_MASTER.md`, `docs/CHANGELOG_V5_44.md`, `docs/PUBLIC_WIKI_SITE.md`를 확인했습니다.
- 공개 위키에 넣을 범위를 유저가 확인 가능한 객관 정보로 제한했습니다.
- 운영자용 정보, 보상 코드 내부 정보, 디버그/테스트 정보는 제외했습니다.
- GitHub 커넥터가 `q93503128-a11y/rebirth-dungeon-wiki`에 정상 연결된 것을 확인했습니다.
- 루트 `index.html`이 없어 Cloudflare Pages에서 404가 발생하던 상태를 확인했습니다.
- 루트 `index.html`을 새로 작성하여 공개 위키 사이트가 바로 뜨도록 구성했습니다.
- 반영 범위: 개요, 직업, 아이템, 던전, 난이도, 성장, 업적/상점 요약.
- 다음 작업: Cloudflare Pages 재배포 후 실제 접속 확인, 필요 시 전체 `wiki/index.html` 원본 수준으로 항목 확장.
