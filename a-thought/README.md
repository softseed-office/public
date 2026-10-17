# 어떤 문장 / A Thought 공개 페이지

App Store·Play 제출과 앱 설정에서 여는 페이지. 정적 파일만 있고 외부 의존 없음.

| 파일 | 용도 | 쓰는 곳 |
|---|---|---|
| `privacy.html` / `privacy-en.html` / `privacy-ja.html` | 개인정보처리방침 (한/영/일) | App Store Connect·Play Console 개인정보 처리방침 URL, 앱 설정 (`AppLinks.privacyPolicy`) |
| `support.html` / `support-en.html` / `support-ja.html` | 지원·문의 (한/영/일) | App Store Connect 지원 URL |
| `press.html` + `press/` | 프레스 킷 (영어) — 소개·사실 정보, 스크린샷·크리에이티브 자산 3개 언어 원본 PNG, 아이콘 1024 | App Store 피처링 추천 보충 자료, 출시 게시물·기자 (writing #153) |

- 오늘의 문장 파일(`prompts.json`)은 여기 없다 — Firebase Hosting (`softseed-athought` 프로젝트)에서 내보낸다. 원본과 올리는 방법은 앱 저장소 `softseed-office/writing` 의 `docs/v1/원격_문장_운영.md`.
- 앱이 새 정보를 다루게 되면 앱 업데이트 전에 개인정보처리방침부터 고친다.
- `press/` 이미지는 앱 저장소 `docs/appstore/screenshots/<언어>/`·`creative/` 에서 복사한다. 스크린샷을 다시 찍으면 여기도 바꾼다 (`preview/` 는 `sips --resampleWidth 480`(스크린샷)·`1200`(크리에이티브) JPEG).
- `press.html` 은 출시(2026-11-10) 전까지 `noindex`. 출시하면 빼고 스토어 링크를 넣는다.
