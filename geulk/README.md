# 긁 공개 페이지

App Store·Play 제출과 앱 설정에서 여는 페이지. 정적 파일만 있고 외부 의존 없음.

| 파일 | 용도 | 쓰는 곳 |
|---|---|---|
| `privacy.html` / `privacy-en.html` / `privacy-ja.html` | 개인정보처리방침 (한/영/일) | App Store Connect·Play Console 개인정보 처리방침 URL, 앱 설정 (iOS `AppInfo.document`, Android `AppInfo.documentUrl`) |
| `terms.html` / `terms-en.html` / `terms-ja.html` | 이용약관 (한/영/일) | 앱 설정 |

- 앱은 기기 언어가 한국어면 한국어, 일본어면 `-ja`, 그 밖이면 `-en` 문서를 연다. 내용을 고칠 때는 세 언어를 함께 고친다 — 다르면 한국어가 우선한다고 영·일 문서에 적어 두었다.
- 앱 저장소: `softseed-office/Geulk` (Issue #52 · 설정 화면 iOS #45 · Android #46).
- 앱이 새 정보를 다루게 되면(고객센터 문의 → Slack, Geulk #51 등) 앱 업데이트 전에 개인정보처리방침부터 고친다.
