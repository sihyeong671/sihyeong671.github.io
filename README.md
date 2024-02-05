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

theme/hugo-resume.zip파일 압축해제후 기존 폴더 대체하기

**좌측 섹션 추가 필요한 경우**
- hugo-resume/layout/index.html 수정
- hugo.toml section에 같은 이름으로 추가
- hugo-resume/i18n/en.json파일에 key value 추가

**skills 추가 필요한 경우**
- data/skills.json에 추가
- 아이콘은 [devicon](https://devicon.dev/)에서 검색후 추가


**projects 정렬 방법**
- weight 조정하여 순서 정렬

# Deploy

가끔 안될 때 [공식 docs](https://gohugo.io/hosting-and-deployment/hosting-on-github/) 확인 필요
github action 현재 repo대로 수정 필요함
로컬에서 `hugo`명령어 이용해서 public 폴더 만들고 commit하고 PR
