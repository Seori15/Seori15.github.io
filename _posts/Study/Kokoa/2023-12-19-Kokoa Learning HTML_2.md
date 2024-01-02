---
title: "코코아톡 챌린지 2강 HTML Part1"
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

# #2. Learning HTML

웹사이트의 기본 뼈대를 이루는 HTML부터 살펴보자!

## #2.1 Our First HTML File and Errors

```HTML
Hello! This is my first HTML file!
```

HTML 파일을 작성하고 브라우저에서 열면, 위 텍스트가 그대로 출력된다.

여기서 우리가 짚고 가야할 부분이 있다.

1. 위 파일은 HTML 문법에 맞춰 작성되지 않았다. 그저 텍스트일 뿐이다.
2. 그러나 브라우저는 아무런 오류 없이 내용을 보여주고 있다.

즉, 브라우저는 HTML 파일에 에러가 있든 없든 아무 경고 없이 화면을 띄운다.

## #2.2 Our First HTML Tag

```HTML
<animal>강아지</animal> (HTML 문법에 <animal>이라는 태그는 없다.. 예시일 뿐)
```

HTML에서 태그는 브라우저에게 의미를 전달하는 역할을 한다.

위 예시의 경우 ‘강아지는 animal이야’ 라고 브라우저에게 알려주는 것이다.

강아지라는 content의 시작과 끝을 animal이라는 태그가 감싸는 구조로 되어 있다.

```HTML
<h1>Hello this is my website!</h1>
<h2>Hello this is my website!</h2>
```

HTML 태그의 아주 명확한 예시로 <h1> ~ <h6> 태그가 있다.

위 코드를 브라우저에서 열면, 저절로 크기와 굵기가 정해진다.

HTML 문법상 <h1> ~ <h6>이 정의되어 있으며, 브라우저가 이를 이해하고 올바르게 표시해주고 있다는 뜻이다.

## #2.3 More Tags and Prettier

```HTML
<ul>
    <li>table</li>
    <li>laptop</li>
    <li>desktop</li>
</ul>

<ol>
    <li>table</li>
    <li>laptop</li>
    <li>desktop</li>
</ol>
```

List에 관련된 <ul>과 <ol> 태그를 배우는 시간이었다.

HTML 문법에 맞게 올바른 태그만 입력해도 브라우저가 알아서 순서가 있는, 혹은 없는 리스트를 작성해준다.

Prettier는 VSC의 확장자 프로그램으로, HTML 파일을 작성할 때 자주 태그 때문에 오류가 생기는데, Prettier가 이를 인식하고 적절한 format으로 변경해준다. 이를 사용하려면 아래와 같이 설정해준다.

1. 확장 프로그램에서 Prettier 설치
2. Settings > Editor: Format On Save 체크
3. Ctrl+Shift+P > Format Document with… > Configure Default Formatter… > Prettier 설정

## #2.4 Tag Attributes

```HTML
<a href="http://google.com" target="_blank">Go to google</a>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYscfUBUbqwGd_DHVhG-ZjCOD7MUpxp4uhNe7toUg4ug&s"/>
```

HTML의 태그는 각각 attribute를 갖는다. 대표적인 예로 <a>와 <img> 태그가 있다.

모든 태그에 사용 가능한 attribute도 있으며, 각 태그마다 정해진 attribute도 있다.

Attribute 사용 시 띄어쓰기에 유의해야 한다.
