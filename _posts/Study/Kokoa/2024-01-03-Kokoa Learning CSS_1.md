---
title: "코코아톡 챌린지 3강 CSS Part1"
excerpt: "코코아 챌린지 사전학습"

categories:
  - Study_kokoa
tags:
  - [Study, TIL, CSS]

toc: true
toc_sticky: true

date: 2024-01-03
last_modified_at: 2024-01-03
---

# #3 Learning CSS

### #3.0 How to Add CSS to HTML

<script src="https://gist.github.com/Seori15/8044ecf3a8f47cf951cdb165af36d864.js"></script>

HTML 문서에 CSS를 적용하는 방법 2가지

1. style 태그에 CSS문을 작성한다. (inline CSS)
2. .css 파일을 만들고 link한다. (external CSS)

### #3.1 Writing Our First CSS Lines

<script src="https://gist.github.com/Seori15/7197a945dca86dc54306e66253a5f416.js"></script>

CSS문의 작성 방법은 위와 같다.

HTML 태그에 {}를 붙여 속성과 속성값을 부여해준다.

속성에는 띄어쓰기를 쓰지 않으며 속성값에는 항상 세미콜론(;)을 붙이자.

### #3.2 What Does Cascading Mean

<script src="https://gist.github.com/Seori15/79418a0b72f5aa34042e0a614a51fe36.js"></script>

CSS는 Cascading 적용 방식을 차용한다.

가장 밑줄, 가장 마지막에 적힌 내용이 최종적으로 적용된다.

위 예시에서는 토마토색만 적용된다.

### #3.3 Blocks and Inlines

HTML의 여러 box 요소들은 Block과 Inline으로 나뉜다.

Block은 줄바꿈을 강제하여 자기 옆에 다른 요소가 있을 수 없지만, Inline은 그 반대이다.

대부분은 Block이나 span, a, image는 Inline이다.

이는 CSS의 display 속성에 의해 바뀔 수 있다.

### #3.4-3.7 Margin

Box는 margin, border, padding을 갖는다.

border를 기준으로 바깥은 margin, 안은 padding이 된다.
