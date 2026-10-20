# cdhnoel-hash.github.io

PocketQuery 앱의 공개 페이지 (GitHub Pages 사용자 사이트).

| 경로 | 내용 |
|---|---|
| `/pocketquery/privacy/` | 개인정보처리방침 (Play Console 에 등록할 URL) |
| `/app-ads.txt` | AdMob 판매자 확인 파일 (AdMob 계정을 만든 뒤 추가) |

개인정보처리방침은 PocketQuery 저장소의 `store/privacy-policy-ko.md` 에서 만든다:

```bash
python ../PocketQuery/store/build_privacy_html.py pocketquery/privacy/index.html
```

"[작성 필요]" 표시가 남아 있으면 공개하지 않는다.
