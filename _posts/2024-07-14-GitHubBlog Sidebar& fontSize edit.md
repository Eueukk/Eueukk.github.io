---
layout: single
title:  "GitHub 좌우 여백 및 폰트 크기 조절"
---

<style>
.custom-heading {
  background-color: black;
  color: white;
  padding: 10px;
}

.full-width-underline {
  width: 100%;
  height: 2px;
  background-color: #1E90FF; /* Dodger Blue */
  margin-top: 10px; /* 제목과 밑줄 사이의 간격 */
}
</style>

### <div class="custom-heading">폰트 크기 조절</div>
<div class="full-width-underline"></div>

1. `_sass/minimal-mistakes/_reset.scss`로 이동 후 Edit(연필 모양)을 누른다.

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled.png)

2. 창 크기에 따라 분류가 된다. 상단부터 기본, Medium, Large, X-Large로 나뉜다.
    - `$small`: 640px (스마트폰)
    - `$medium`: 768px (태블릿)
    - `$large`: 1024px (데스크탑)
    - `$x-large`: 1200px 이상 (와이드 스크린)
3. 알맞게 각각 설정해주고 Commit Change.(전부 같은 크기로 해도 상관 없다)

### <div class="custom-heading">좌우 여백 조절</div>
<div class="full-width-underline"></div>

1. `_sass/minimal-mistakes/_variables.scss`로 이동 후 수정한다.

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled%201.png)

2. `mmistakes`는 사용자의 편의에 따라 레이아웃의 크기를 변경시킬 수 있다.

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled%202.png)

3. 기존 코드는 주석 처리하고 여백을 줄인 후 commit change.

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled%203.png)

4. 변경 후 큼직한 것들이 조금 보기 편해졌다.

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled%204.png)

아직 꾸며야 할 게 많지만, 포스팅 겸 열심히 해보도록 하겠습니다.
