---
title: "코코아톡 챌린지 3강 CSS Part2"
excerpt: "코코아 챌린지 사전학습"

categories:
  - Study_kokoa
tags:
  - [Study, TIL, CSS]

toc: true
toc_sticky: true

date: 2024-01-04
last_modified_at: 2024-01-04
---

## #3.8 IDs and Classes

CSS를 적용하려고 할 때, 우리는 selector가 필요하다.

HTML 태그 이외에도 ID와 Class를 selector로 사용할 수 있다.

ID는 유일하게 사용되어야 하며 #으로 호출한다.

Class는 중복으로 사용 가능하며 한 box에 여러 class도 적용 가능하다. .으로 호출한다.

## #3.10-3.11 Flexbox

<script src="https://gist.github.com/Seori15/b9fe2db7cdc713d45500a33c29d7c16e.js"></script>

적용을 위해 자식이 아닌 부모에게 display: flex를 명시한다.

justify-content는 main axis, align-items는 cross axis에 적용된다.

main axis의 방향은 flex-direction 속성에 의해 지정된다.

## #3.12 Position

- fixed : 첫 기준점 혹은 지정한 위치에 고정된다.
- relative: 첫 기준점에서 top, bottom, left, right 값만큼 이동한 곳에 위치한다.
- absolute: 기준점이 relative인 부모가 된다.

## #3.14-3.16 Pseudo selector

HTML 문서에 id나 class를 추가하기보다는 pseudo selector를 사용하는 편이 훨씬 깔끔하다.

- Pseudo selector 활용
  - first-child
  - last-child
  - nth-child(2)
  - nth-child(2n+1)
  - p span : p에 속하는 span
  - p > span : p의 바로 밑 자식인 span
  - p + span : p의 자식이 아닌 바로 다음 span
  - p ~ span : p의 자식이 아닌, 바로 다음이 아니어도 형제인 span
- attribute 활용
  - input : required
  - input[placeholder~=”name”]

## #3.17 States

Status는 HTML 블록의 상태를 나타낸다.

- active : 현재 블록이 선택되어 있음.
- hover : 마우스 커서가 블록 위에 있음.
- focus : 키보드로 선택되어 있음.
- focus-within : 자식이 선택되어 있음.
- visited : 선택된 적 있음. ex)하이퍼링크를 누르고 나면 보라색이 됨

## #3.19 Colors and Variables

<script src="https://gist.github.com/Seori15/87105630c54bb82ad9096e90f5b991d6.js"></script>

HTML CSS문에서 다음과 같이 변수를 선언하여 활용할 수 있다.
