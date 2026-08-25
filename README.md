# mybaseballstar 약관 문서

앱에서 여는 이용약관과 개인정보 처리방침의 **원본**입니다.
GitHub Pages 로 게시됩니다.

- https://mybaseballstar.tomsworkers.io/terms
- https://mybaseballstar.tomsworkers.io/privacy

앱 저장소(`everydaystudy/mabas-app`)는 비공개라 Pages 를 쓸 수 없어서
문서만 여기로 분리했습니다. **양쪽에 두면 갱신할 때 어긋나므로 원본은
여기 하나뿐입니다.**

앱은 위 URL 을 열기만 합니다(설정 > 정보). 문구를 고치면 앱을 다시 내지
않아도 반영됩니다.

## 스토어 제출 메모

**App Store 프라이버시 라벨은 이 문서와 어긋나면 안 된다.**

처리방침이 [저장한다]고 적은 것을 라벨에서 `Data Not Collected` 로 내면
리젝 사유가 된다. 익명 식별자와 푸시 토큰은 **`Identifiers` > `User ID`**
로 신고해야 한다.

앱이 실제로 저장하는 것(처리방침 2.1):

| 항목 | 라벨 분류 |
|---|---|
| 익명 인증 식별자 | Identifiers · User ID |
| FCM 푸시 토큰 | Identifiers · User ID |
| 팔로우한 선수 · 알림 설정 | 앱 기능용 (Linked to identifier) |

광고 식별자·분석 SDK 는 쓰지 않으므로 그 항목들은 해당 없음이다.

개인정보처리방침 URL 과 이용약관(EULA) URL 은 **별개 항목**으로 각각 제출한다.

## 주소

`CNAME` 파일이 커스텀 도메인을 정한다. DNS 는 GoDaddy 에 있고
`mybaseballstar` CNAME 이 `everydaystudy.github.io` 를 가리킨다.

⚠️ **이 주소는 App Store 에 제출하고 앱에 상수로 박혀 있다**
(`lib/screens/settings_screen.dart` 의 `_legalBase`). 바꾸려면 양쪽을
같이 고쳐야 하고, 이미 배포된 앱은 옛 주소를 계속 부른다.
