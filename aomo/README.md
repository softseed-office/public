# AOMO 공개 페이지

App Store·Play 제출과 앱 로그인·설정에서 여는 페이지. 정적 파일만 있고 외부 의존 없음.

| 파일 | 용도 | 쓰는 곳 |
|---|---|---|
| `terms.html` / `terms-en.html` | 이용약관 (한/영) | 앱 로그인 푸터·설정 (iOS `AppLinks.Document.termsOfService`) |
| `privacy.html` / `privacy-en.html` | 개인정보처리방침 (한/영) | App Store Connect·Play Console 개인정보 처리방침 URL, 앱 로그인 푸터·설정 (iOS `AppLinks.Document.privacyPolicy`) |

- 앱은 표시 언어가 한국어면 한국어 문서, 그 밖(영어·일본어)이면 `-en` 문서를 연다. 내용을 고칠 때는 두 언어를 함께 고친다 — 다르면 한국어가 우선한다고 영문 끝에 적어 두었다.

- 앱 저장소: `softseed-office/aomo` (Issue #98 · iOS #99 · Android #100).
- 내용은 출시 전 기준 초안이다. 법무 확정본과 생체정보(얼굴) 법적 검토(aomo #27) 결과가 나오면 이 파일을 고친다 — 주소는 그대로 둔다.
- 앱이 새 정보를 다루게 되면(서버 백업, 푸시 토큰, 결제 등) 앱 업데이트 전에 개인정보처리방침부터 고친다.
