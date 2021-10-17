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

# 타이머

바닐라 자바스크립트로 타이머 만들기


## 요구사항

### 필수

- 세 개의 `input`에 `시간` `분` `초`를 입력
- 입력할 수 있는 시간에 제한 없음
- 타이머를 시작하면 입력받은 값에서 1초씩 줄어듦
- `index` 에는 `hh:mm:ss` 의 형식으로 표시
- 남은 시간을 시각적으로 표시 (예: 원형, 막대 차트 등)
- 필수로 구현할 버튼 총 4개: `시작` `일시 정지` `재시작` `리셋`


### 선택

- 자주 쓰는 시간 프리셋을 제공 (예: 3분, 5분, 10분, 30분, 60분 등)
- 입력할 수 있는 최대 시간을 `23:59:59`로 제한
- 두 자릿수를 입력하면 자동으로 다음 `input`으로 focus
- 구현한 버튼에 키보드 이벤트 추가 (예: 스페이스키: start ↔ pause)
- 브라우저 제목에 남은 시간 표시
- To do list를 추가하고 아이템별로 타이머 설정
- `localStorage`를 사용해서 타이머의 내용이 새로고침해도 유지됨


## 배운 점

- `Date.now` 내장객체를 활용해 타이머 만들기
- `setInterval` 함수로 타이머를 시작하고 `clearInterval` 로 중지하기
- `nextElementSibling` 을 이용해 `e.target`의 다음 요소로 focus를 이동하기
- 버튼에 `keyup` `keydown` 이벤트를 추가해 키보드로 조작하기


## 저장소
- [@dopamingo](https://github.com/dopamingo): [dopamingo/js-calculator](https://github.com/dopamingo/js-timer/)
- [@hhkim0729](https://github.com/hhkim0729): [hhkim0729/vanilla-timer](https://github.com/hhkim0729/vanilla-timer)
- [@MichelleJin12](https://github.com/MichelleJin12)
- [@S0YKIM](https://github.com/S0YKIM)
- [@srngch](https://github.com/srngch): [srngch/vanilla-js-timer](https://github.com/srngch/vanilla-js-timer)


## 배포 페이지
- [@dopamingo](https://github.com/dopamingo): [🔗링크](https://dopamingo.github.io/js-timer/)
- [@hhkim0729](https://github.com/hhkim0729): [🔗링크](https://hhkim0729.github.io/vanilla-timer/)
- [@srngch](https://github.com/srngch): [🔗링크](https://srngch.github.io/vanilla-js-timer/)
