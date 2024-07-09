---
layout: single
title:  "GitHub 블로그 만드는 방법"
---

### 해당 영상참고해서 만들었습니다.
[GitHub 블로그 생성 방법](https://www.youtube.com/watch?v=ACzFIAOsfpM)


## Git 블로그 생성 방법

<p style="font-size:14px;">만드는 과정 (대략 10분)</p>

1. 아래 링크를 클릭하고 마음에 드는 테마를 선택합니다.
   [https://github.com/topics/jekyll-theme](https://github.com/topics/jekyll-theme)

   여기서는 스타를 많이 받은 minimal-mistakes를 사용합니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%201.png" style="width: 100%; max-width: 600px;">

2. Fork 합니다.

   도큐먼트를 꼼꼼히 확인합니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%202.png" style="width: 100%; max-width: 600px;">

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%203.png" style="width: 100%; max-width: 600px;">

   포크된 레포지토리로 가서 셋팅에 들어간 후 본인 깃허브 아이디(여기서는 Eueukk)를 그대로 적고 `.github.io`를 뒤에 붙여서 입력 후 리네임 클릭.

   [https://mmistakes.github.io/minimal-mistakes/docs/configuration/](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)

3. 포크된 레포지토리 파일 중 `_config.yml` 파일에 들어가 url을 수정합니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%204.png" style="width: 100%; max-width: 600px;">

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%205.png" style="width: 100%; max-width: 600px;">

   `Edit this file`을 클릭 후 

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%206.png" style="width: 100%; max-width: 600px;">

   URL을 수정해야 합니다. 주석 처리된 해당 부분을 지우고

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%207.png" style="width: 100%; max-width: 600px;">

   해당 부분에 본인의 깃허브 아이디를 입력합니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%208.png" style="width: 100%; max-width: 600px;">

   이후 `Commit changes`를 눌러서 저장하면 블로그가 생성 완료됩니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%209.png" style="width: 100%; max-width: 600px;">

   다시 포크된 레포지토리로 돌아가 해당 부분을 복사(ctrl+c)하여 주소창에 붙여넣기(ctrl+v)하고 해당 URL로 접속합니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%2010.png" style="width: 100%; max-width: 600px;">

   해당 부분을 복사해서 주소창에 붙여넣으면 블로그가 생성되어 있는 것을 볼 수 있습니다.

4. 새로운 포스팅을 생성합니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%2011.png" style="width: 100%; max-width: 600px;">

   원래 깃허브 블로그 레포지토리로 들어가서 `Add file`을 클릭하여 `+Create new file`을 클릭합니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%2012.png" style="width: 100%; max-width: 600px;">

   해당 부분에 `_posts`를 입력한 후 `/`를 입력합니다.

   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%2013.png" style="width: 100%; max-width: 600px;">

   오늘 날짜를 입력 후 `-xxxx`를 입력 (해당 부분이 포스트의 URL 부분이 됩니다). 그 후 이어서 `.md`(마크다운) 확장자를 입력합니다.

   [https://jekyllrb.com/docs/posts/](https://jekyllrb.com/docs/posts/)
   
   위 주소로 들어가 블로그 포스트 가이드가 나온다 마크다운문법으로 만들어야하는것 같음
   
   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%2014.png" style="width: 100%; max-width: 600px;">


   레이아웃에 포스트도 있는 듯합니다. #은 헤더를 나타냅니다.
    
   <img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-09-CreateGitHubBlogImg/Untitled%2015.png" style="width: 100%; max-width: 600px;">
5. Jupyter notebook 파일을 다운로드 받아 업로드 합니다.
   다운로드 받은 .md 파일 명을 변경 합니다.
    
6. 테마도 변경해 볼 수 있습니다.
   _config.yml 에 테마 있음

7. 에디터:
   - [Typora 에디터](https://typora.io/)

typora에디터가 유료화되어버린듯하다.

첫 블로그 포스팅인데 앞으로 열심히 해보겠습니다.
