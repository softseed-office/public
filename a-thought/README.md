# 어떤 문장 / A Thought 공개 페이지

App Store·Play 제출과 앱 설정에서 여는 페이지. 정적 파일만 있고 외부 의존 없음.

| 파일 | 용도 | 쓰는 곳 |
|---|---|---|
| `privacy.html` / `privacy-en.html` / `privacy-ja.html` | 개인정보처리방침 (한/영/일) | App Store Connect·Play Console 개인정보 처리방침 URL, 앱 설정 (`AppLinks.privacyPolicy`) |
| `support.html` / `support-en.html` / `support-ja.html` | 지원·문의 (한/영/일) | App Store Connect 지원 URL |

- 오늘의 문장 파일(`prompts.json`)은 여기 없다 — Firebase Hosting (`softseed-athought` 프로젝트)에서 내보낸다. 원본과 올리는 방법은 앱 저장소 `softseed-office/writing` 의 `docs/v1/원격_문장_운영.md`.
- 앱이 새 정보를 다루게 되면 앱 업데이트 전에 개인정보처리방침부터 고친다.
