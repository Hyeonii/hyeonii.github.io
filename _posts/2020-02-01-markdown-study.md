---
layout: post
title: "테스트 포스팅입니다"
date: 2021-01-31 15:14:24
author: devluvpillow
categories: Study
---

# 마크다운 문법 탐구

### 글씨체

일반 글씨체
_이탤릭 글씨체_ _이탤릭 글씨체_ 별표 한 개와 언더바 두 가지
**두꺼운 글씨체** 별표 두개
**_두꺼운 이탤릭체_**
<u>밑줄 치기</u>
~~취소합니다 신기방기~~

### 리스트

1.  1. 목록 1
    2. 목록 2
       - 순서 없는 목록
       - 순서 없는 목록

- 순서가 필요하지 않은 목록 ul
- 그냥 작대기 그어주면
- 된다

* 이건 별표
* 목록

- 더하기 목록은
- 어떻게 생겼을까?

### 링크

[내 깃허브 페이지](https://hyeonii.github.io/)
나의 인스타그램: <https://www.instagram.com/devluvpillow/>

### 이미지

앞에 !느낌표를 붙여준다

![로고 이미지](https://hyeonii.github.io/assets/logo.png "logo image")
[![이미지 링크](https://hyeonii.github.io/assets/logo.png)](https://www.instagram.com/devluvpillow/)

### 코드 강조

---

1. 코드 강조

<pre> 
    pre로 넣은 코드 
    <body>
        <div></div>
    </body>
</pre>

<code> 
    code 로 넣은 코드
    <body>
        <div></div>
    </body>
</code>

2. 인라인 코드 강조

` 바틱 기호` 안에 쓴 코드은 `inline code`가 된다

3. 블록코드 강조

```html
<a href="https://www.hyeonii/github.io" target="_blank">내 홈페이지</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

### 표

`<table>` 태그로 변환 가능하다

<table>
    | 값 | 의미 | 기본값 |
    |---|:---:|---:|
    | `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
    | `relative` | 요소 자신을 기준으로 배치 |  |
    | `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
    | `fixed` | 브라우저 창을 기준으로 배치 |  |
</table>

```markdown
| 값         |                  의미                  |   기본값 |
| ---------- | :------------------------------------: | -------: |
| `static`   |     유형(기준) 없음 / 배치 불가능      | `static` |
| `relative` |       요소 자신을 기준으로 배치        |          |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |          |
| `fixed`    |      브라우저 창을 기준으로 배치       |          |
```

### 인용문

<blockQuote>

> 나는 아직 배고프다
> _(진짜 배고픈 사람이 한 말)_

BREAK!

> 나는 아직 배고프다
>
> > 중첩도 가능
> >
> > > 중중첩도 가능
> > > _(진짜 배고픈 사람이 한 말)_

</blockQuote>

> blockQute 밖에서 인용을 하면?
> _(???)_

### 수평선

## `_` `*` `-` 중 하나를 3개 이상 입력

---

---

### 줄바꿈

`<br>` 이나 `띄어쓰기 두 번` 사용

我的小時候 吵鬧人性的時候  
wǒ de xiǎo shíhòu chǎonào rénxìng de shíhòu  
어린시절, 시끄럽고 제 멋대로 였을 때  
我的外婆 總會唱歌哄我 <br>
wǒ de wàipó zǒnghuì chànggē hōng wǒ <br>
외할머니는 언제나 노래를 하면서 나를 달래주셨어 <br>
한자도 잘 나오네요!
