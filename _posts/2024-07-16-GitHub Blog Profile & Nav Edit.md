---
layout: single
title:  "GitHub 상단 네비게이션바 목록 및 디자인 수정, 프로필 사진 디자인 수정"
---

<style>
.custom-heading {
  background-color: #333;
  color: white;
  padding: 10px;
  display: inline-block;
  border-radius: 5px;
}

.full-width-underline {
  width: 100%;
  height: 3px;
  background-color: #1E90FF;
  margin-top: 5px;
  border-radius: 5px;
}

.step {
  margin: 20px 0;
  font-size: 1.1em;
}

.step img {
  border: 1px solid #ccc;
  border-radius: 5px;
  margin: 10px 0;
}

.footer-note {
  margin-top: 30px;
  font-size: 1.2em;
  text-align: center;
  background-color: #f9f9f9;
  padding: 20px;
  border-radius: 10px;
  border: 1px solid #ddd;
  color: darkgray;
}
</style>

### <span class="custom-heading">상단 네비게이션바 수정</span>
<div class="full-width-underline"></div>

<div class="step">
1. /_data/navigation.yml 이동 후 우측에 Edit this file을 누르고 편집으로 이동

<img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-16-GitHub%20Blog%20Profile%20%26%20Nav%20Edit%20Img/Untitled.png" alt="Edit navigation file">
</div>

<div class="step">
2. 원하는 상단 네비게이션 목록을 작성해준다. 'title'은 보여지는 목록의 이름이고 'url'은 목록 클릭시 이동되는 url이다.

<img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-16-GitHub%20Blog%20Profile%20%26%20Nav%20Edit%20Img/Untitled%201.png" alt="Navigation list example">
</div>

<div class="step">
3. commit change 후, 잘 되었는지 확인해본다.

<img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-16-GitHub%20Blog%20Profile%20%26%20Nav%20Edit%20Img/Untitled%202.png" alt="Commit changes">
</div>

### <span class="custom-heading">상단 네비게이션바 디자인 수정</span>
<div class="full-width-underline"></div>

<div class="step">
1. /_sass/minimal-mistakes/_masthead.scss 이동 후 우측에 편집(Edit this File)
2. 상단 네비게이션 바 글씨 크기, 굵기, 여백을 수정 할 수 있다.
</div>

### <span class="custom-heading">프로필 사진 등록 및 디자인 수정</span>
<div class="full-width-underline"></div>

<div class="step">
1. 사용할 프로필 이미지를 assets 폴더에 images 폴더를 새로 만든 후 넣어둔다

<img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-16-GitHub%20Blog%20Profile%20%26%20Nav%20Edit%20Img/Untitled%203.png" alt="Add profile image">
</div>

<div class="step">
2. _config.yml로 이동 후 편집
3. # Site Author를 찾아 이동, 
   - name: 해당 블로그 운영자 이름 (한글 넣었는데 오류났었다)
   - avatar: 아까 넣어둔 이미지의 경로를 입력
   - bio: 간단한 소개를 입력합니다.
   - location: 위치를 입력해줍니다.

<img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-16-GitHub%20Blog%20Profile%20%26%20Nav%20Edit%20Img/Untitled%204.png" alt="Edit site author details">
</div>

<div class="step">
4. /_sass/minimal-mistakes/sidebar.scss 이동 후 우측에 편집(Edit this File)
5. 프로필 사진의 CSS를 수정

<img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-16-GitHub%20Blog%20Profile%20%26%20Nav%20Edit%20Img/Untitled%205.png" alt="Edit profile photo CSS">
</div>

<div class="step">
6. 프로필 수정이 잘됐는지 확인

<img src="https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-16-GitHub%20Blog%20Profile%20%26%20Nav%20Edit%20Img/Untitled%206.png" alt="Check profile update">
</div>

<div class="footer-note">
블로그가 점점 나아지는 모습을 보니 은근 재밌네요. 이번 포스팅이 여러분께 많은 도움이 되었기를 바랍니다. 
피드백은 항상 환영입니다. 감사합니다!
</div>
