---
title: "코코아톡 챌린지 4강 Advanced CSS"
excerpt: "코코아 챌린지 4강"

categories:
  - Study_kokoa
tags:
  - [Study, TIL, CSS]

toc: true
toc_sticky: true

date: 2024-01-08
last_modified_at: 2024-01-09
---

# #4 Advanced CSS

JavaScript 없이 CSS에서도 애니메이션 효과를 적용할 수 있도록 발전함!!

## #4.1 Transitions

<script src="https://gist.github.com/Seori15/5049e552c0148af1de842cdd4f10eff6.js"></script>

Transition을 적용할 때 주의사항

1. 변할 상태(hover)가 아닌 원상태에 코드를 작성한다.
2. 변할 상태(hover)에 적용되어 있지 않은 효과는 transition에도 적용되지 않는다.

Transition Easing에는 cubic-bezier라는 강력한 커스텀 옵션을 포함하여 다양한 옵션이 있다.

- inear
- ease
- ease-in
- ease-out
- ease-in-out
- cubic-bezier

## #4.2 Transformations

X, Y, Z축 3D 방향으로 rotate, scale, translate 등 다양한 변형을 줄 수 있다.

Transformation도 마찬가지로 transition이 가능하기 때문에, 여러 애니메이션 효과를 구현할 수 있다.

## #4.3 Animations

<script src="https://gist.github.com/Seori15/16d8943cfcdc442e6c4fb5534bb921ee.js"></script>

애니메이션은 transition과 상관 없이 효과를 상시적용 할 수도 있다.

애니메이션 step이 2개면 from ~ to, 더 많다면 숫자로도 표현할 수 있다.

## #4.5 Media Queries

<script src="https://gist.github.com/Seori15/a5617a0637cf64a31f0504f3cfbb3bce.js"></script>

사용자들은 PC, 휴대폰, 태블릿 등 다양한 기기로 웹에 접속하는데, 각자 화면의 크기가 다르다.

Media query를 통해 각 화면 크기를 상정하여 개발할 수 있다.

이외에 프린트할 때의 화면 설정도 가능하다.
