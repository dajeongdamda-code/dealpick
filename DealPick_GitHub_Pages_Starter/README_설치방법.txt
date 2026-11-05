DealPick GitHub Pages 공식 사이트 시작 패키지
===============================================

0. 중요: 사이트 게시 전에 다음 텍스트를 모든 HTML에서 실제 값으로 수정해야 합니다.
  [[공개_문의_이메일_입력]]  -> 게시해도 되는 실제 지원 이메일
  [[실제_운영자_또는_사업자_명칭]] -> 실제 운영자/사업자 명칭
  이용약관·개인정보처리방침은 초안입니다. 실질적인 데이터 처리 내용과 비교하고, 틀린 내용은 고치세요.

1. github.com/new 이동 후 Repository name = dealpick, Public, Add README 체크 -> Create repository
2. 저장소 Code 화면에서 Add file -> Upload files 클릭
3. 이 ZIP의 내용물인 index.html, guide.html, terms.html, privacy.html, style.css, .nojekyll을 모두 선택해 업로드
   [중요] ZIP 자체를 올리지 말고, 압축을 푼 파일들을 올리세요. 루트에 두어야 합니다.
4. Commit changes 클릭
5. Settings -> Pages -> Build and deployment -> Deploy from a branch -> main / (root) -> Save
6. 주소: https://<github사용자명>.github.io/dealpick/
   접속 후 이용약관과 개인정보처리방침 링크가 열리는지 확인

TikTok Developer 앱 입력 예시
---------------------------------
Official website (Desktop): https://<사용자명>.github.io/dealpick/
Terms of Service URL: https://<사용자명>.github.io/dealpick/terms.html
Privacy Policy URL: https://<사용자명>.github.io/dealpick/privacy.html

TikTok URL properties (2026-11 기준)
---------------------------------
- 'Domain' 으로 github.io 전체 도메인을 확인하지 마세요. 이 도메인은 GitHub가 소유합니다.
- 'URL prefix' 를 선택하고 https://<사용자명>.github.io/dealpick/ 를 입력해 검증 시도하세요.
- TikTok가 제공한 signature 파일을 다운로드해 저장소 루트에 파일 이름과 내용 그대로 업로드하세요.
- GitHub Pages에 배포된 파일 URL이 200으로 열리는지 확인 후 TikTok에서 Verify를 진행하세요.
- 실제 소유권 확인은 TikTok 서버에서 수행하므로 성공을 보장할 수 없습니다.

주의사항
---------------------------------
- Client Key/Client Secret, OAuth 토큰, SNS 개인 계정 인증 정보는 GitHub에 절대 업로드하지 마세요.
- 웹사이트를 만든 것만으로 TikTok 게시 권한이 승인되지는 않습니다.
- TikTok 공식 App Review Guidelines는 개인 전용 앱의 심사 승인을 제한합니다.
- 쇼핑 광고용 콘텐츠의 사진 사용 권한과 제휴 수수료 고지는 별도로 확인해야 합니다.
