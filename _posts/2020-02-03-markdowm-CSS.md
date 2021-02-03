---
layout: post
title: "CSS 에서 다른 태그/앨리먼트에 CSS 적용하기"
date: 2021-02-03 11:05:24
author: devluvpillow
categories: CSS
---

# CSS 에서 다른 태그/앨리먼트에 CSS 적용하기

---

<br>
  
가끔 A 태그에 hover시 다른 엘리먼트에 CSS 효과를 적용하고 싶을 때가 있다
`^`, `>`, `~`, `=` 를 통하여 구현 할 수 있다
  
<br>
<br>
  
##### B 엘리먼트가 A 엘리먼트 바로 안에 들어올 때

<code>
 A > B 
#A:hover > #B { background-color: yellow; }
</code>
  
<br>
  
##### B 엘리먼트가 A 엘리먼트 영역 밖에 있을 때
<code>
A + B 
#A:hover + #B { background-color: yellow; }
</code>
  
<br>
  
##### B 엘리먼트가 A 엘리먼트 영역 안의 어딘가에 있을 때

<code>
A  B  ( A태그와 B태그 사이에 빈칸 )
#A:hover #B { background-color: yellow; }
</code>
     
<br>
  
##### B 엘리먼트가 A 엘리먼트 의 자손일 때
<code>
A ~ B
#A:hover ~ #B { background-color: yellow; }
<code>
  
  
<br>

---

<br>
  
CSS는 잘 먹었지만 결과물은 처참했다   <br>
내가 이런걸 만들 줄이야.. ^^ <br>
다른 방법을 시도해보도록 한다 <br>
  
<br>

![망했다](https://hyeonii.github.io/assets/posting-img/f.gif) {: width="100"}

<br>
  
---
  
[참고 사이트](https://stackoverflow.com/questions/4502633how-to-affect-other-elements-when-one-element-is-hovered)
