# How to setting in local computer

themes의 zip파일 압축풀고 기존 폴더 대치
```sh

# git init 
# git add submodule theme 주소

# how to test in local PC
hugo server

# hugo build : making public folder
hugo
```

---

# Fix Guide

좌측 섹션 추가 필요한 경우
- hugo-resume/layout/index.html 수정
- hugo.toml section에 같은 이름으로 추가
- hugo-resume/i18n/en.json파일에 key value 추가

