---
layout: post
title: example1 part2.조회수 보기
image: 
  path: /assets/img/blog/steve-harvey.jpg
description: >
 조회수 보이기

sitemap: false
categories:
  -example1
---
# part2.조회수 보기

* toc
{:toc .large-only} 


👀3.10 조회수 보이기


깃허브 블로그의 단점은 아래와 같이 다른 블로그에서는 볼 수 있는 방문자수 또는 조회수를 보이기이다.
이런 조회수 보이기는 자신의 블로그가 얼마나 인기가 있고 영향력이 있는지 뽐내기에 아주 좋은
도구일것이다. 깃허브 블로그의 경우 Jekyll이나 Hugo와 같은 정적 사이트 생성기로 제작되었기
때문에 블로그 방문자와의 상호작용을 기록할 수 없다.
이는 자체적인 백엔드가 없기 때문인데. 그렇다보니 서드파티 서비스를 이용하여 이를 대체하고
는 한다. 대표적으로 댓글기능의 경우는 보통 Disqus나 utterances를 이용해서 구현한다.
방문 기록 분석은 구글 애널리틱스를 이용하면 된다.
하지만 내 글의 조회수를 보여주고 싶다면 어떻게 해야할까?
구글 애널리틱스 하나면 누가, 어디에서, 언제 어떤 검색어로 내 블로그에 방문했는지 모두 알 수있다.

<div class="main_center">
    <div><img src= "/assets/img/blog/example1/14.JPG" style="width: 700px; height: 500px; auto;"></div>
</div>


하지만 이는 블로그 주인 자신만 볼 수 있다는 문제가 있다.
내 게시글을 사람들이 이만큼 봤다는 것을 보여주고 싶고 내 블로그가 얼마나 인기 있는지 보여
주고 싶다면 어떻게 해야 할까?
성취감을 느낄 수 있고 자랑할 수 있으며 신뢰감을 주려는 목적으로 글의 조회수를 보여주고 싶
다면 어떻게 해야 할까?


Hits로 그 목적을 달성해보자.


👀3.10.1 Hits


Hits는 본래 깃헙 레파지토리 방문자 수를 세기 위해 만들어졌다.


🔍 https://hits.seeyoufarm.com/


위 링크에 들어가서 아래와 같이 커스텀해준다.


<div class="main_center">
    <div><img src= "/assets/img/blog/example1/10.JPG" style="width: 700px; height: 500px; auto;"></div>
</div>
그리고 아래로 조금만 내리면 아래와 같은 화면을 볼 수 있다.
<div class="main_center">
    <div><img src= "/assets/img/blog/example1/11.JPG" style="width: 700px; height: 500px; auto;"></div>
</div>
이중 HTML LINK를 복사한다.
각 게시물에 Hits를 보여주는 것도 좋지만 그전에 먼저 전체적인 내 페이지 조회수를 알고 싶다.
그래서 페이지에서 무조건 한번은 불러오는 사이드바에 Hits를 달아본다.
<div class="main_center">
    <div><img src= "/assets/img/blog/example1/12.JPG" style="width: 700px; height: 500px; auto;"></div>
</div>


👀구글 애널리틱스로 조회수보기


Hints의 문제는 어찌보면 새로고침의 개수이지 조회수라고 하기 그렇다.
새로고침만하면 숫자가 증가한다. 따라서 구글 애널리틱스를 통해 실질적인 조회수 조회와 각종
통계 지표를 제공받아본다.
아래 주소로 이동


🔍 https://analytics.google.com/