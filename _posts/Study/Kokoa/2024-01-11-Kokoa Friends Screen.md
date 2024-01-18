---
title: "코코아톡 챌린지 6강 Friends Screen"
excerpt: "코코아 챌린지 6강"

categories:
  - Study_kokoa
tags:
  - [Study, TIL, HTML, CSS]

toc: true
toc_sticky: true

date: 2024-01-11
last_modified_at: 2024-01-12
---

## #6.2 Friends Screen TIL

<p align="center">
<img src="https://drive.google.com/uc?id=1yZZXc21KEn7Cebci7_FervTEnN-6Z5Dr" width="80%">
</p>

[Sign Up Screen on Github](https://github.com/Seori15/2024_Kokoa_Clone/commit/71bebaa22e6db3cbec22190d4c720bc6990530fa)

이번에는 Friends 화면을 구현하면서 공통 components인 nav-bar와 screen-header를 작업하였다.

여러 화면에 공통으로 등장하는 components는 만들어두고 상황에 맞게 조금씩만 변형하여 사용하면 된다.

어제 css 파일을 분리하고 variables도 사용했었는데, 그 연장선을 계속 연습하는 오늘이었다.

### \*border-box

nav-bar에 padding을 주고 화면 밑에 fix하는 과정에서, nav-bar가 오른쪽 화면 밖으로 벗어나는 현상이 발생했다.

이는 padding과 width 설정이 충돌했기 때문에 발생했다.

CSS가 padding과 width 둘 다 만족시키려고 하다 보니 실제 box의 크기가 100% + padding이 된 것.

`box-sizing: border-box` 옵션은 CSS가 실제 box의 크기를 건들지 않도록 막는다.

### Screen Header

이 header의 경우 4개의 화면에서 공통으로 사용하므로 components로 분류하였다.

class 작명은 참 어렵다.

### User Component

Friends 창에서 사진/이름/설명 3개로 구성된 component가 다른 화면에서도 반복적으로 사용된다.

처음에 클론할 화면을 볼 때는 이게 반복되어 사용되는 건지, 어떤 구조로 이루어져 있을 지 가늠이 전혀 안됐었는데, 한 번 따라치고 나니까 화면 구성에 대한 감이 잡히고 있다.

user-component\_\_avatar--xl, user-component\_\_avatar--sm라는 class를 만들었다.

위에서 말했던 component의 사진 크기가 화면마다 다르게 적용되고 있다.

따라서 기존 class를 활용하여 크기만 조절해준다면 우리가 만들어둔 component로 충분히 활용할 수 있다.
