# Good First Issues

AMP커뮤니티에서 처음시작하는 컨트리 뷰터들을 위해서 뽑은 이슈들을 가지고 컨트리뷰트 절차 배우기

## [1. Add examples to amp-image-slider.md](https://github.com/ampproject/amphtml/issues/18058)

### post

#### First Timers Only
#### 처음 접하는 분에게만 권합니다.

We know figuring out the process for contributing to an open source project can be intimidating, so we created this issue as a way for you to learn the ropes. (If you feel comfortable contributing to open source projects, please leave this issue for someone else.)

#### What you will need to know
#### 알아야 할 것

How to edit markdown files

#### Background
#### 기본지식
The amp-image-slider.md file doesn't have examples on how to use the different attributes. Please add one example each of how to use the different attributes:

disable-hint-reappear
initial-slider-position
step-size

#### Step by step
#### 단계별 진행

  ```
  Claim this issue by adding a comment below. Please only claim this bug if you plan on starting work in the next day or so. (If you join the AMP Project we'll be able to assign this issue to you after you've claimed it.

  이슈를 등록해라. 이 버그를 고치는 작업을 내일이나 바로 시작하는 경우에만 부탁한다.
  당신이 AMP 프로젝트에 들어온다면 이 이슈를 당신이 주장한 이후에 당신에게 할당 할 수 있다.

  If you aren't too familiar with Git/GitHub, see the Getting Started End-to-End Guide for an intro to Git & GitHub, and how to get a copy of the code. You can also refer to the Quick Start Guide for the necessary setup steps with less explanation than the End-to-End guide.

  만약 당신이 Git과 Github이 익숙하지 않다면, Git과 Github 입문자를 위한 'Getting Started End-to-End Guide'를 보고 어떻게 코드를 카피하는지 확인해라. 그리고 'End-to-End guide'보다 설명이 더 간단히 설명 된 'Quick Start Guide'를 통해 설치 단계를 볼 수 있다.

  Follow the instructions for building AMP.

  따라해봐라

  Create a Git branch for making your changes.

  당신의 기여한 코드를 위해서 깃브랜치를 만든다

  Sign the Contributor License Agreement before creating a Pull Request. (If you are contributing code on behalf of a corporation start this process as early as possible.)

  풀리퀘스트를 하기 전에 컨트리뷰터 라이센스 동의를 한다. (회사에서 하는거면 가능한 빨리 해라)

  Commit your changes frequently.

  주기적으로 커밋을 해라

  Push your changes to GitHub.

  깃헙에 기여한 코드를 푸쉬한다.

  Create a Pull Request. Mention closes Issue <this issue number> in the description.

  풀리퀘스트를 만들고 상세내용에 이 issue number를 남긴다.

  Respond to your reviewer's comments (if any).

  리뷰어의 답변을 기다린다.
  ```

Once approved, your changes will be merged. ⚡⚡⚡Congrats on making your first contribution to the AMP Project!⚡⚡⚡ You'll be able to see it live across the web soon!

만약 풀리퀘스트가 허가된다면 당신이 기여한 코드는 머지 될것이다.


## [2. [amp-image-slider] Use the semantic cursor for the dragging bar](https://github.com/ampproject/amphtml/issues/18056)

### post

```
<amp-image-slider> should use cursor: col-resize as an extra affordance that the bar is draggable.

<amp-image-slider> col-resize를 드래그로 조정하기 위해서 커서를 사용해야한다.



Even though you can actually start dragging anywhere, we should still show the cursor when the user is on top of the bar (perhaps with some padding on the left/right).

드래깅은 할 수는 있지만, 커서가 바위에 있을때는 커서가 보여야 한다.
(왼쪽과 오른쪽에 일부 패딩과 함께)


```

## [amp-twitter fails with dynamic data-tweetid](https://github.com/ampproject/amphtml/issues/17953)

### post

```
I am trying to integrate these awesomely 😍 written AMP web components in my website [angular content/resource platform]
but facing issue in it.
the issue i am facing is :
It works perfectly fine when i use the static tweetid in amp twitter component

<amp-twitter width="375" height="472" layout="responsive" data-tweetid="638793490521001985"> </amp-twitter>

but when i try to make dynamic it fails.

<amp-twitter width="375" height="472" layout="responsive" [data-tweetid]="id"> </amp-twitter>

amp-twitter를 웹사이트와 연동중에 문제가 생겻다.
문제는 내가 고정 트위터 아이디를 잘 사용할때는 동작하지만, 동적으로 트위터아이디를 주면(바인딩 써서인듯) 동작하지않는다.

where id is variable with data. 😬
using it with Angular 6.
can you guys explain possible reason.

id는 변수를 데이터로 주었고, 앵귤러를 사용중이다.
이 문제를 해결할 수 있는 사람 있나요 ?
```

