---
layout: default
title: Calculator
permalink: /project/calculator/
excerpt: "개인 프로젝트 Calculator"
parent: Projects
nav_order: 3

categorites:
  - Project
tags:
  - JavaScript
  - VanillaJS
---

## CALCULATOR

A calculator app mimicked iphone's calculator in Vanilla Javascript

</br>

## REQUIREMENTS

- [x] 사칙연산: `+ - * /`
- [x] 부호 토글: `+/-`
- [x] 계산기를 클래스로 구현
- [x] AC 기능: 0 으로 초기화
- [x] 연산자를 클릭할 때마다 결과 업데이트
- [x] C(CE) 기능: 마지막 연산의 숫자를 지우기 (`3+1` → `3+`)

</br>

## BONUS

- [x] 퍼센트: `%`
- [x] 반복 계산: `=` 를 연속으로 누르면 이전 연산 반복
- [x] 버튼 클릭 시 색이 변하는 기능

</br>

## LESSON LEARNED

- [x] `Number`와 `String` 함수로 숫자와 문자열 변환하기
- [x] 이벤트 객체를 매개변수로 받아서 `target`속성 활용하기
- [x] `includes` 메서드로 문자열 안에 해당 문자가 있는지 확인하기
- [x] `active`로 버튼 클릭 시에 색이 변하도록 하는 `CSS` 기능
- [x] 지나친 `if`문 사용을 자제하고 인덴트를 줄이는 방향으로 리팩토링
- [x] `FLEX`뿐만 아니라 `GRID`를 활용하여 간격 맞추기
