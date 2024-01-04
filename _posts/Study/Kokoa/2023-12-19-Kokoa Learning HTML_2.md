---
title: "코코아톡 챌린지 2강 HTML Part2"
excerpt: "코코아 챌린지 사전학습"

categories:
  - Study_kokoa
tags:
  - [Study, TIL, HTML]

toc: true
toc_sticky: true

date: 2023-12-19
last_modified_at: 2024-01-02
---

### #2.5 More Tags and Head

<script src="https://gist.github.com/Seori15/4686eb7b8b1047f201b418204c2dfa16.js"></script>

HTML 문서의 구조를 전체적을 보면 <head>와 <body>로 나뉜다.

태그 <body>는 지금까지 실습했던, 페이지에 보여지는 부분을

태그 <head>는 그 외 보여지지 않는 부분을 담당한다.

### #2.6 It’s All About the Head

<script src="https://gist.github.com/Seori15/4441f7a999e185490b505bf555a98177.js"></script>

태그 <head> 안에는 사이트가 검색 엔진에서 표시되는 title, description, 언어 설정, 썸네일 등을 설정하는 각종 태그가 위치한다.

### #2.7 More Tags

태그 <head>와 <body>를 포함해서 수많은 HTML 태그들이 존재하지만, 전부 외울 필요는 없다.

더 많은 태그가 궁금하다면 <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">MDN 사이트</a>에서 확인할 수 있다.

앞으로는 직접 개발하면서 필요한 태그들을 익혀서 사용할 수 있도록 한다.

### #2.8 Form Tags

<script src="https://gist.github.com/Seori15/3e5a4ed8a7f66bb2f8051bbb1fe6bcce.js"></script>

태그 <form>을 사용하면 사용자에게 여러 입력값을 받아 브라우저에게 넘겨줄 수 있다.

태그 <label>은 <input>과 함께 사용되어 input 박스로 커서를 연결해주는 역할을 한다.

이 때 태그 <input>의 id attribute와 동일한 값이 매칭되어야 하는데, id는 unique한 값이어야 한다.

적절한 attribute를 사용하면 비밀번호 규칙을 정하거나, 업로드 파일 형식을 제한하는 등 강력한 기능을 지원해준다.

가장 중요한 것은 태그를 달달 외우는 것이 아니라 사용 규칙을 알고 활용할 줄 아는 것이다.

### #2.10 Semantic HTML

<script src="https://gist.github.com/Seori15/645519565346beb97a8d9d7a5236c67b.js"></script>

위 코드가 Semantic HTML 태그를 사용한 예시이다.

HTML에서는 각 구역을 구분하기 위해서 <div>나 <span> 등의 태그를 사용하고는 했다.

위 예시에서 <header>, <main>, <footer> 등의 태그는 전부 기존의 <div>로 사용해도 되지만, 보는 사람에게도 명확하고 브라우저에게도 명시해줄 수 있는 Semantic 태그를 사용하는 것을 추천한다.
