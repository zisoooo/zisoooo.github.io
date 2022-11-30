
## 프로젝트 build 과정 설명
- 1. Repository 생성
- 2. Repository 연동
- 3. 예시 문서 작성 후 repoistory에 push
- 4. Jekyll 설치 후 local repository에 반영
- 5. Jekyll Blog Theme 적용
- 6. 실습 내용 정리 post 작성
- 7. 댓글 기능 삽입(Disqus)
- 8. Google Analytics 기능 추가
- 9. favicon 추가

## 주요 내용 정리 
### 1. Repository 생성
- 나의 github에 'zisoooo.github.io' repository 생성

### 2. Repository 연동
- 생성한 repository를 local에 구축하는 과정
- 'git clone <내 원격저장소 주소>를 터미널에 입력하여 연동함

### 3. 예시문서 작성 후 repository에 push
- html 문서를 작성하고 [git add . ->  git commit  ->  git push]순으로 하여 push 진행

### 4. jekyll
- 실습에서 배웠던 jekyll로  Github 블로그 과제 수행
- 로컬이었던 Mac에서는 jekyll이 설치가 되지 않았던 관계로 VM에 jekyll 설치하여 과제 진행
- jekyll을 저장소에 반영하여 zisoooo.github.io로 접속하여 jekyll 화면 띄우기 성공

### 5. Blog theme 적용
- 기존 테마가 밋밋해 보였기 때문에 블로그에서 jekyll [monos](http://jekyllthemes.org/themes/monos/)테마 다운받아 테마 적용


### _config.yml
- _config.yml에서 블로그의 Title을 'Jisu's Blog', Subtitle을 'HW Blog'로 변경함

### 7. 댓글 추가
- disqus 사이트에서 댓글을 달기 위한 html코드를 복사하여 post.html에 이 기능을 나의 블로그 post에 반영

### 8. Google analytics 기능 추가
- Google analytics 사이트에 들어가서 회원가입 후 
### 9. favicon 적용
- 블로그에 하트 모양의 favicon을 적용함
- [favicon generator사이트](https://www.favicon-generator.org)에서 favicon을 추가하는 코드를 생성하여 ./_includes/head.html의 상단에 추가함
```
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/site.webmanifest">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="theme-color" content="#ffffff">
```



