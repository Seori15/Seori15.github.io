---
title: "코코아톡 챌린지 6강 Chats Find Screen"
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

## #6.3 Chats Screen TIL

<p align="center">
<img src="https://drive.usercontent.google.com/download?id=1Gm23HixHCgQv5fBcyKb3ROJhdgK2FYRZ" width="80%">
</p>

[Chats Find Screen on Github](https://github.com/Seori15/2024_Kokoa_Clone/commit/8514d054be6ac635bbf7703e9cb00029ec7b2f4e)

Chats 화면은 Friends 화면에서 대부분 그대로 가져왔기 때문에 어려운 요소는 없었다.

Chats 화면에서 인상깊었던 점은

1. 원래 있던 nav-notification CSS 클래스를 nav-notification과 badge와 2개로 나눠 적용하면서, 기존 디자인을 유지하면서 새로운 화면에 활용할 수 있었다.

2. user-component\_\_column:last-child에 `display: flex`를 적용하면서 기존 Friends 화면의 정렬이 무너졌는데, 이를 새로운 div로 감싸서 해결하였다.

## #6.4 Find Screen TIL

<p align="center">
<img src="https://drive.usercontent.google.com/download?id=1xv2RS1fNGjqa5-tajSWlLJAUZHnAcnGM" width="80%">
</p>

[Chats Find Screen on Github](https://github.com/Seori15/2024_Kokoa_Clone/commit/8514d054be6ac635bbf7703e9cb00029ec7b2f4e)

이 정도 오니까 지금까지 했던 일들의 반복이다.

Find 화면에는 글과 아이콘이 정말 많았는데, CSS로 이걸 만들기에는 정말 노가다가 아닐 수 없다.

포기하지 않고 끝까지 집중했더니 보기에 뿌듯한 화면이 완성되었다.

특이했던 점은 해쉬태그 부분이다. 해쉬태그는 `text-transform: uppercase` 옵션으로 대문자로 만들어주었다. 대문자 또한 디자인의 영역이기 때문이다.

반복되는 CSS를 어떻게 처리할 지 고민하는 것과 class 작명 센스가 우수한 프론트엔드 개발자의 조건이라는 생각이 든다.
