---
title: "바닐라 JS로 크롬 앱 만들기 1-2강"
excerpt: "크롬 앱 챌린지 사전학습"

categories:
  - Study_chrome
tags:
  - [Study, TIL, JavaScript]

toc: true
toc_sticky: true

date: 2024-01-18
last_modified_at: 2024-01-18
---

# #3. JavaScript on the Browser

## #3.0 The Document Object

JavaScript는 HTML과 상호작용하기 위해 만들어진 언어이다.

따라서 HTML 태그에 직접 간섭할 수 있다.

HTML의 정보는 document라는 객체에 저장되어 있으며 JavaScript로 조회/수정이 가능하다.

## #3.1 HTML in JavaScript

<script src="https://gist.github.com/Seori15/780f7bf74c9922f1e856d4152705552a.js"></script>

위 코드를 실행해보면 JavaScript가 HTML 태그에 영향을 주는 것을 알 수 있다.

## #3.2 Searching For Elements

<script src="https://gist.github.com/Seori15/66e6a33e9112128381f826e4a5bdbc0e.js"></script>

## #3.3-3.5 Events

<script src="https://gist.github.com/Seori15/d216bb6680c82a3751980e3189a01b2c.js"></script>

JavaScript는 event를 감지(listen)할 수 있다.

event의 종류는 MDN이나 console.dir에서 확인할 수 있다.

마우스의 커서 위치, 클릭, 와이파이 등 다양한 이벤트를 활용할 수 있다.

## #3.6-3.8 CSS in JavaScript

<script src="https://gist.github.com/Seori15/ba5c540764bb6e63404e82c4412b09ac.js"></script>

JavaScript에서 CSS 요소를 변경할 때, 위 2번 줄에서처럼 변수를 설정해두는 것을 추천한다.

CSS class명인 “clicked”를 사용한다면 오타가 생겨도 에러가 발생하지 않지만, 변수명 clickedClass를 사용한다면 JavaScript에서 에러를 일으킨다.

또한 add, remove, toggle과 같은 강력한 기능들을 사용할 수 있다.
