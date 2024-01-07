---
title: "바닐라 JS로 크롬 앱 만들기 1-2강"
excerpt: "크롬 앱 챌린지 사전학습"

categories:
  - Study_chrome
tags:
  - [Study, TIL, JavaScript]

toc: true
toc_sticky: true

date: 2024-01-06
last_modified_at: 2024-01-07
---

# #1. Introduction

### #1.0 Welcome

프로그래밍 경험이 없더라도 할 수 있다!

당신의 환상적인 커리어를 만들어 줄 언어, JavaScript. 렛츠 두디스

### #1.1 What Are We Building

모멘텀을 클론해서 만들어볼 것이다.

현재 시각, 현재 위치, 랜덤 사진, 랜덤 명언, Todo Memo 등의 기능이 들어간다.

누군가는 Vanilla JS를 굳이 배울 필요 없다고 할 순 있겠지만

나는 불편함을 해소하며 발전해나가는 개발자의 사고방식을 좋아하기에.. 답습해보기로 한다.

### #1.4-1.5 Why JS

1. JS는 전세계 모든 사용자가 사용하는 인기 폭발 언어이다.(브라우저에 기본 내장)
2. 그러다보니 3D 웹사이트, 백엔드, 머신러닝 등 다 지원하는 언어이다.
3. JS는 프론트엔드의 유일한 프로그래밍 언어이다.

언어 하나로 이 모든 걸 해결할 수 있다니 놀랍지 않은가✨

# #2. Welcome to JavaScript

### #2.0 Your First JS Project

<script src="https://gist.github.com/Seori15/d5f020b70a2a31c13905c12fe44cb78e.js"></script>

JavaScript문은 브라우저에서 직접 읽어 작동하지 않는다.

CSS와 마찬가지로 HTML 문서에 script 태그를 이용해 링크를 걸어주어 작동한다.

하지만 head 끝에 작성했던 CSS의 style과는 다르게 body 끝에 주로 작성한다.

### #2.1-2.3 Basic Data Types, Variables

JavaScript는 기본적으로 integer/float/string 타입을 알아서 구분한다.

JavaScript로 변수를 선언할 때는 값이 변하지 않는 상수 const와 변할 수 있는 let을 사용한다.

파이썬을 먼저 배운 내 입장으로는 const와 let을 구분하는 이유를 이해할 수 없었지만 변수 선언부에서 제작자의 의도를 파악하도록 도와준다고 한다.

var는 더 이상 사용하지 않는다.

### #2.4 Booleans

여타 언어들과 마찬가지로 각각 true, false를 의미하는 Boolean 타입이 있다.

그리고 값이 없는 경우는 null, 값을 지정해주지 않아 없는 경우는 undefined가 된다.

### #2.5 Arrays

<script src="https://gist.github.com/Seori15/5fe417e7ab2cd22869f21c1965d42e70.js"></script>

JavaScript에서 데이터를 나열(array)하는 방법은 간단하다.

array의 제목을 선언하고, [] 안에 데이터를 나열한다. 이 때 여러 타입이 공존할 수 있다.

### #2.6 Objects

<script src="https://gist.github.com/Seori15/18a94dabf60ed1b6db097cb099c65cd7.js"></script>

설명이 필요하지 않은 데이터는 array로 충분하지만,

게임 캐릭터의 스탯창과 같은 정보는 설명이 필요하다. 이럴 때 object를 활용한다.

object는 {}를 사용하여 작성한다.

### #2.7-2.8 Functions

<script src="https://gist.github.com/Seori15/b2e3b623f85609865cd7a0954a1b29f1.js"></script>

function은 변수를 받을 ()부분과 기능을 작성할 {}부분으로 구성된다.

object 안에 선언할 때는 문법이 살짝 달라지는 점에 유의하자.

### #2.11 Returns

<script src="https://gist.github.com/Seori15/bc2479da8fabc7f24f689be4adf1af79.js"></script>

console.log는 데이터의 중간 흐름을 이해하는 데 도움이 되지만, 직접적으로 데이터에는 관여하지 않는다. 예를 들면 우리는 계산기를 만들어서 a+b의 값을 얻어낼 수 있지만, a+b의 값을 활용하려면 console.log로는 부족하다. 함수로 작동한 데이터의 값을 활용하고자 할 때, return이 필요하다.

### #2.13-2.15 Conditionals(조건문)

<script src="https://gist.github.com/Seori15/23701c9e398b085741ab14930cd9dcfe.js"></script>
