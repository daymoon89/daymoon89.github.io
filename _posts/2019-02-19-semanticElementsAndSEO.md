---
layout: post
title: "시멘틱 요소와 SEO(Semantic Elements & SEO)"
description: "Semantic Elements와 SEO, 그리고 그 둘의 연관성에 관한 글"
thumb_image: "documentation/sample-image.jpg"
tags: [article, web, blog]
---

    개인적으로 공부한 내용을 토대로 작성한 글입니다.  
    다소 부정확한 내용이 있을 수 있습니다. 따끔한 일침 감사히 받겠습니다.

    Semantic Elements와 SEO의 연관성에 관한 글이며 SEO의 상세한 내용은 다루지 않습니다.

HTML은 웹을 배울 때 대부분 가장 처음 배우는 언어이며, 굉장히 쉬운 마크업 언어입니다.

이런 HTML은 대충 쓰면 되지 따로 공부해야 하나 싶기도 합니다.

사실 이런 내용을 따로 공부하지 않아도 페이지가 작동하는 데 HTML 때문에 문제가 생길 일은 거의 없으니까요.

그러나 컴퓨터와 사람이 이해하기 쉬운 문서를 작성하고, 검색엔진에 자신의 페이지가 상위에 위치하기를 원하는 분들이라면 한 번쯤은 이 쉽고 기초적인 HTML에 대한 내용도 자세히 살펴볼 필요가 있습니다.

믿기 힘드시겠지만 HTML을 배우는 것보다 쉽습니다.

이제 Semantic Elements이 무엇이며 SEO와 어떠한 관련이 있는지 알아보겠습니다.

## Semantic Elements란?

'의미론적인 요소들'

 Semantic Elements의 한국어 번역입니다. 번역을 보니 의미가 명확해지는 것 같습니다.

 HTML에서 의미론적인 요소란, 명확한 의미를 가진 태그를 말합니다.

먼저 의미론적이지 않은, 일반적인 태그(혹은 요소_Element)를 살펴보겠습니다.

대표적으로 ```<div>, <span>```이 있습니다.

```<div>```는 단순하게 구역을 나누는 용도이며 태그만으로는 무엇을 의미하는 지 알 수 없습니다.

 그렇다면 의미론적인 요소에는 무엇이 있을까요?

 바로, ```<h1>, <table>``` 같은 태그입니다. 태그만 보고 명확한 의미를 파악할 수 있죠.  
 HTML5에는 다음과 같은 의미론적인 요소들이 추가되었습니다. 
 대표적으로 ```<main>, <article>, <aside>, <figure>, <figurecaption>, <header>, <footer>, <nav>, <section>```등이 있습니다.

    <!-- 의미론적이지 않은 태그 -->
    <div id=header>
    	<h1>난 무의미해</h1>
    	<p>나도</p>
    </div>
    
    
    <!-- 의미론적 태그 -->
    <header>
        <h1>난 의미있어</h1>
        <p>나도</p>
    </header>

## SEO(Search Engine Optimization)

 이번에는 SEO를 간단하게 살펴보겠습니다.

 보통 검색 엔진을 이용하는 입장에서 검색 엔진 최적화라는 말은 해석을 어떻게 해야할 지 난감합니다.

 그러나 개발하는 입장으로 받아들인다면 대충 감은 잡을 수 있습니다.

 

 내가 만든 페이지를 구글과 같은 곳의 검색결과 상단에 위치하게 하려면 어떻게 해야할까요?

 저 물음의 답하는 작업들을 SEO(Search Engine Optimization_검색엔진최적화)라고 합니다.

 기본적인 작업은 검색어를 페이지에 적절하게 배치하고 다른 웹페이지에 링크가 연결, 인용되는 횟수를 늘려야합니다.

 (한국 포털사이트 같은 경우 기준이 다를 수 있으며, 구글과 같은 검색엔진과 지향하는 방향이 달라서가 아닐까 합니다) 

 

그렇다면 HTML의 의미론적인 태그와 SEO는 어떤 관계일까요?

## Semantic Elements와 SEO(Search Engine Optimization)

 위에서 SEO의 방법 중 기본적인 요소로 검색어를 페이지에 적절하게 배치하는 것을 말했습니다. 

 검색어를 적절하게 배치하는 것과 의미있게 태그를 작성하는 것이 무슨 상관일까요?

 검색엔진은 검색결과를 낼 때, HTML에 담긴 태그를 분석합니다.

 의미가 분명한 태그는 검색엔진의 입장에서 분명한 데이터인 셈이죠.

 예를 들어, ```<h1>```에 키워드를 넣는 것입니다.

  

물론 Semantic Elements는 SEO 요소에서 작은 부분입니다.

그러나 SEO는 작은 부분, 부분, 부분, 부분들이 모여야 큰 힘을 발휘할 수 있는만큼 의미있는
 태그를 작성하는 것을 소홀히 해서는 안됩니다.

읽어주셔서 감사합니다.

- 참고
    - [w3schools - HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
    - [Link-Assistant - HTML Tags for SEO: to use or not to use?](https://www.link-assistant.com/news/html-meta-tags-for-seo.html)
    - [The HTML5 Semantic Elements and what They Mean For SEO](https://www.inboundnow.com/html5-semantic-elements-mean-seo/)