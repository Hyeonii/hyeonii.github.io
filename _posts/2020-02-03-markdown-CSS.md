---
layout: post
title: "Reset CSS와 Normalize CSS의 차이 "
date: 2021-02-01 15:14:24
author: devluvpillow
categories: CSS
---

<br>

# reset css와 normalize css의 차이

### reset CSS

---

##### reset CSS를 사용하는 이유

브라우저 마다 기본적으로 설정된 css 관련 기본 값들이 존재하기 때문에  
내가 짠 레이아웃이 각 브라우저 마다 다른 모습으로 출력 될 수 있다

그래서 크로스 브라우징에서는 css reset을 이용하여 브라우저의 기본값을 초기화 시킨다  
브라우저에서 기본적으로 적용하는 태그의 간격이나 색상 등을 없애주는 작업이다  
<br>

Eric Meyer의 yahoo, 다음, 네이버 등에서 배포한 reset css도 있가
대중적으로 많이 사용하는 reset css 코드이며 Eric Meyer 라는 분이 만들었다

[Eric Meyer’s “Reset CSS” 2.0](https://meyerweb.com/eric/tools/css/reset/)  
<br>

### normalize css

---

reset CSS에 대해 찾아보다 알게 되었다  
css Normalize의 코드가 브라우저 마다 가지고 있는 기본 설정 차이를 동일하게 만들어준다  
<br>

##### reset CSS와의 차이점

기본값을 아예 제거해버리는 reset CSS 와는 달리 사용하기 좋은 기본값들은 유지한다
reset.cs의 범위를 벗어난 몇 가지 일반적인 버그도 수정해준다고 한다

[Necolas's "Normalize CSS"](https://github.com/necolas/normalize.css)

<br>
  
### 결론
---
  
사람마다 취향이 다르고 문제에 대한 해결 방법이 다르니   
둘 다 실험해보고 어떤 것을 선호하는지 알아보는게 가장 좋다  
  
css Normalize의 설명 중 코드를 효율적으로 작성하는데에 좋다는 말이 있어 더욱 궁금해졌다    
직접 사용해보고 비교해봐야겠다
