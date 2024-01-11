---
title: "코코아톡 챌린지 6강 Sign Up Screen Part2"
excerpt: "코코아 챌린지 6강"

categories:
  - Study_kokoa
tags:
  - [Study, TIL, HTML, CSS]

toc: true
toc_sticky: true

date: 2024-01-10
last_modified_at: 2024-01-11
---

## #6.1 Sign Up Screen TIL

<p align="center">
<img src="https://drive.google.com/uc?id=1yFLVVDCcwBM2rB-u10W7xXAk1KN1ssFl" width="80%">
</p>

[Sign Up Screen Part2 on Github](https://github.com/Seori15/2024_Kokoa_Clone/commit/591a5d630851e63ceec349167599620a9c5e1ea4)

어제 완성하지 못한 form 부분의 CSS를 완성했다.

계속해서 flex box를 다루는 예제를 통해 flex-direction에 대한 개념이 잡히기 시작했다. 세로로 줄세우려면 column!!

전에는 styles.css 파일에 모든 CSS문을 작성했지만 오늘은 화면별로 용도별로 폴더에 구분지어 파일을 분리하였다.

status-bar나 다음에 작성할 navigation bar는 여러 화면에서 공통적으로 쓰이기 때문에 components 폴더에,

특정 화면에만 사용되는 경우 screens 폴더에 각자 저장함으로써 styles.css의 가독성도 좋아지고 원하는 코드를 찾기 쉬워졌다.

### \*BEM CSS

본 강의에서 BEM의 장/단점을 체감하기 위해서 BEM 방식과 일반 방식을 혼용하며 진행하였다.

welcome-header class 부분은 BEM CSS를, login-form id 부분은 일반적인 CSS를 적용하였다.

개인적인 생각으로는 CSS문이 워낙 세분화되어 있고 적용할 블록이 늘어날수록 BEM이 훨씬 눈에 잘 들어온다고 느꼈다.

### \*Reset CSS

작성한 HTML 파일의 body를 보면 margin 8px이 자동으로 적용되어 있다.

브라우저는 자동으로 레이아웃을 적용하는데, 이를 모두 초기화하고자 할 때 사용한다.

HTML 파일에 붙이면 지저분해지므로 메인이 되는 styles.css 파일에 import하여 사용하자.

### \*CSS :not()

수많은 id나 class, pseudo element 선택자들에도 불구하고 우리가 원하는 CSS를 적재적소에 맞춰 적용하기는 쉽지 않다. 그럴 땐 not()이 도움이 될 것이다. 선택자에 not을 사용하면 일종의 조건문처럼 사용이 가능하다.
