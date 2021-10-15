---
layout: default
title: Timer
excerpt: "개인 프로젝트 Timer"
permalink: /project/timer/
parent: Projects
nav_order: 1

categorites:
  - Project
tags:
  - JavaScript
  - VanillaJS
---

# Timer

바닐라 자바스크립트로 아이폰 계산기 클론 코딩하기 


## 요구사항

### 필수

- 세 개의 `input`에 `시간` `분` `초` 를 입력할 수 있다.
- 최대 입력 시간에 제한은 없다.
- 타이머를 시작하면 입력받은 값에서 1초식 줄어든다.
- `index` 에는 `hh:mm:ss` 의 형식으로 표시한다.
- 남은 시간을 시각적으로 표시한다. (예: 원형, 막대 차트 등)
- 필수로 구현할 버튼은 총 4개이다. `시작` `일시정지` `재시작` `리셋`


### 선택

- 자주 쓰는 시간 프리셋을 제공한다. (예: 3분, 5분, 10분, 30분, 60분 등)
- 입력할 수 있는 최대 시간을 `23:59:59`로 제한한다.
- 두 자리 수를 입력하면 자동으로 다음 `input`으로 focus가 간다.
- 구현한 버튼에 키보드 이벤트를 추가한다. (예: 스페이스키: start ↔ pause)
- 브라우저 제목에 남은 시간을 표시한다.
- To do list 를 추가하고 아이템별로 타이머를 설정한다.
- `localStorage`를 사용해서 타이머의 내용이 새로고침해도 유지된다.


## 배운 점

- `Date.now` 내장객체를 활용해 타이머를 만들 수 있다.
- `setInterval` 함수로 타이머를 시작하고 `clearInterval` 로 중지할 수 있다.
- `nextElementSibling` 을 이용해 `e.target`의 다음 요소로 focus를 이동할 수 있다.
- 버튼에 `keyup` `keydown` 이벤트를 추가해 키보드로 조작할 수 있다.




## 저장소
- [@hhkim0729](https://github.com/hhkim0729): [hhkim0729/vanilla-timer](https://github.com/hhkim0729/vanilla-timer)
- [@srngch](https://github.com/srngch): [srngch/vanilla-js-timer](https://github.com/srngch/vanilla-js-timer)
- [@dopamingo](https://github.com/dopamingo): [dopamingo/js-calculator](https://github.com/dopamingo/js-timer/)


## 배포 페이지
- [@hhkim0729](https://github.com/hhkim0729): [🔗링크](https://hhkim0729.github.io/vanilla-timer/)
- [@srngch](https://github.com/srngch): [🔗링크](https://srngch.github.io/vanilla-js-timer/)
- [@dopamingo](https://github.com/dopamingo): [🔗링크](https://dopamingo.github.io/js-timer/)
