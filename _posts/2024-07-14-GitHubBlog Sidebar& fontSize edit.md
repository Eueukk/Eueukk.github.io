# GitHub 좌우 여백및 폰트크기 조절

### 폰트 크기 조절

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled.png)

1. _sass / minimal-mistakes / _reset.scss로 이동 후 Edit(연필모양)을 누른다.
2. 창 크기에 따라 분류가 된다. 상단부터 기본, Medium, Large, X-Large로 나뉜다.
    - `$small`: 640px (스마트폰)
    - `$medium`: 768px (태블릿)
    - `$large`: 1024px (데스크탑)
    - `$x-large`: 1200px 이상 (와이드 스크린)
3. 알맞게 각각 설정 해주고 Commit Change.(전부 같은 크기로 해도 상관 없다)

### 좌우 여백 조절

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled%201.png)

**1. _sass/minimal-mistakes/_variables.scss로 이동 후 수정한다.**

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled%202.png)

**2. mmistakes는 사용자의 편의에 따라 레이아웃의 크기를 변경 시킬 수 있다.**

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled%203.png)

3. 기존 코드는 주석 처리 여백을 줄이고 이 후 commit change.

![Untitled](https://github.com/Eueukk/Eueukk.github.io/raw/master/_posts/2024-07-14-GitHubBlog%20Sidebar%26%20fontSize%20edit%20Img/Untitled%204.png)

4. 변경 후 큼직한 것들이 조금 보기 편해 졌다.

아직 꾸며야 할게 많은데 포스팅 겸 열심히 해보도록 하겠습니다.