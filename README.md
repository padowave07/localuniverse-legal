# localuniverse-legal

로컬 유니버스 앱(협동조합 청풍)의 법적 고지 페이지. GitHub Pages 로 공개한다.

- privacy.html — 개인정보 처리방침 (앱 내 termsList PRIVACY_POLICY v1 과 동일, 시행 2026-08-28)

## 배포(최초 1회)
```
git init -b main && git add -A && git -c user.name=padowave07 -c user.email=savesea07@gmail.com commit -m "개인정보 처리방침 페이지"
gh repo create padowave07/localuniverse-legal --public --source=. --remote=origin --push
gh api -X POST repos/padowave07/localuniverse-legal/pages -f "source[branch]=main" -f "source[path]=/"
```
→ https://padowave07.github.io/localuniverse-legal/privacy.html
