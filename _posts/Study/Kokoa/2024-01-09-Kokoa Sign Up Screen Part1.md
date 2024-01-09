---
title: "코코아톡 챌린지 6강 Sign Up Screen Part1"
excerpt: "코코아 챌린지 6강"

categories:
  - Study_kokoa
tags:
  - [Study, TIL, HTML, CSS]

toc: true
toc_sticky: true

date: 2024-01-09
last_modified_at: 2024-01-10
---

# #6 Clonning Time

우리가 구현할 화면은 총 8개다.

로딩 화면, 로그인 화면, 친구 목록, 채팅 목록, 검색 화면, 더보기 화면, 설정 화면, 채팅 화면

JavaScript는 들어있지 않기 때문에 CSS를 연습할 용도로 껍데기만 만들 것이다.

## #6.1 Sign Up Screen TIL

<img src="https://drive.google.com/uc?id=1onxOqWQlTL9YI3izwbXZBVtBfYCKyNQm">

[Sign Up Screen Part1 on Github](https://github.com/Seori15/2024_Kokoa_Clone/commit/95b396cfdd8d25bdfbd3242c1bfc0dbfb654269b)

오늘은 Sign Up 화면을 클론하면서, 기본적으로 화면의 HTML 파일이 어떻게 구성되는지 파악할 수 있었다.

어디부터 어떻게 작성해야 할지 막막했는데 status-bar, header, input 부분으로 먼저 크게 나누고, 각 구역에 해당하는 블록을 파악하는 순서대로 금방 이해하며 진행할 수 있었다.

진행하면서 submit 타입의 input 태그는 button과 똑같이 보인다는 것을 알 수 있었다. CSS를 적용할 때의 통일성을 위하여 input으로 작성하였다.

\*BEM CSS

Block, Element, Modifier의 준말.

CSS의 클래스 명을 지을 때 BEM 방식으로 지어서 가독성을 높이는 방법이다. 하이픈(—)과 밑줄(**)로 BEM을 구분하여 작명한다. ex).block**element—modifier

본 강의에서는 BEM의 장/단점을 체감하기 위해서 BEM 방식과 일반 방식을 혼용하며 진행한다.

\*Font Awesome

수많은 무료/유료 아이콘을 사용하게 해주는 사이트이다. 회원가입 하면서 개개인의 Kit를 받게 되면 HTML에 script로 삽입하면서 아이콘을 사용할 수 있게 된다.

\*Google Fonts

구글 폰트에서 맘에 드는 글씨체를 찾아 import 혹은 link하여 사용이 가능하다.
