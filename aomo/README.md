# AOMO 공개 페이지

App Store·Play 제출과 앱 로그인·설정에서 여는 페이지. 정적 파일만 있고 외부 의존 없음.

| 파일 | 용도 | 쓰는 곳 |
|---|---|---|
| `terms.html` | 이용약관 (한국어) | 앱 로그인 푸터·설정 (iOS `AppLinks.termsOfService`, Android `AppLinks`) |
| `privacy.html` | 개인정보처리방침 (한국어) | App Store Connect·Play Console 개인정보 처리방침 URL, 앱 로그인 푸터·설정 (iOS `AppLinks.privacyPolicy`) |

- 앱 저장소: `softseed-office/aomo` (Issue #98 · iOS #99 · Android #100).
- 내용은 출시 전 기준 초안이다. 법무 확정본과 생체정보(얼굴) 법적 검토(aomo #27) 결과가 나오면 이 파일을 고친다 — 주소는 그대로 둔다.
- 앱이 새 정보를 다루게 되면(서버 백업, 푸시 토큰, 결제 등) 앱 업데이트 전에 개인정보처리방침부터 고친다.
