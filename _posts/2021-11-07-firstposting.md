---
layout: single
title:  "The first post of notion!"
---


# Chap2_3

project Calculator

UIStackView

열 또는 행에 View 들의 묶음을 배치할 수 있는 간소화된 인터페이스

동적인 UI

관리하기 편함

오토레이 레이아웃을 쉽게 설정가능

Vertical Stack View

Horizontal Stack View

*Vertical Stack View == 간단하게 말해서 수직적 관계 subView끼리 상하 위치,수직한 위치

*Horizontal Stack View == 수평적 관계 subView끼리 좌우 위치,수평한 위치

![스크린샷 2021-11-04 오전 1.12.24.png](/assets/1.12.24.png)

![horizontal](/assets/1.12.05.png)

horizontal

# UIStackView Distribution

![Fill
( 우선순위 낮은것부터 변화시킴)](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.28.04.png)

Fill
( 우선순위 낮은것부터 변화시킴)

![Fill Proportionally
(subView가 가지고있는 크기에 비례해)](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.29.40.png)

Fill Proportionally
(subView가 가지고있는 크기에 비례해)

![Equal Centering  
스택 내에서 서브뷰들의 간격 일정하게](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.27.09.png)

Equal Centering  
스택 내에서 서브뷰들의 간격 일정하게

![Fill Equally
(고르게 스택뷰 내를 채움 )](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.29.01.png)

Fill Equally
(고르게 스택뷰 내를 채움 )

![Equal Sapcing 
서브뷰 사이 공간 일정하게](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.29.47.png)

Equal Sapcing 
서브뷰 사이 공간 일정하게

---

# UIStackView Alignment

—> StackView & subView들을 어떻게 정렬할 것인지,,, 배열?!?의 느낌!    

![Fill
채움~](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.58.55.png)

Fill
채움~

![Top
위로 정렬](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.59.10.png)

Top
위로 정렬

![
Center 
중앙에 정렬](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.59.22.png)

Center 
중앙에 정렬

![Bottom](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.59.46.png)

Bottom

![Leading
왼쪽 정렬](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.59.01.png)

Leading
왼쪽 정렬

![First Baseline
Horizontal 에서만 사용가능 
서브 베이스라인에 맞춰서~](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.59.17.png)

First Baseline
Horizontal 에서만 사용가능 
서브 베이스라인에 맞춰서~

![Tailing
왼쪽 (꼬리) 에 맞춘다](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.59.29.png)

Tailing
왼쪽 (꼬리) 에 맞춘다

![Last Baseline
Horizontal 스텍뷰에만 적용가능](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_5.59.52.png)

Last Baseline
Horizontal 스텍뷰에만 적용가능

---

UIStackView Spacing

 Stack View 안에 들어가는 뷰들의 간격을 조성하는 속성

![스크린샷 2021-11-03 오후 6.09.54.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-03_%EC%98%A4%ED%9B%84_6.09.54.png)

Spacing 은 view들의 간격을 조절한다!

  

autoLayout error

오토레이아웃을 사용하여

![이런 UI 를 만들기위해](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-04_%EC%98%A4%EC%A0%84_12.54.25.png)

이런 UI 를 만들기위해

![여기에서 첫번째 버튼을 두번째줄 세번째 열에 tailing을 걸면](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-04_%EC%98%A4%EC%A0%84_12.55.19.png)

여기에서 첫번째 버튼을 두번째줄 세번째 열에 tailing을 걸면

![이렇게 되버린다.](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-04_%EC%98%A4%EC%A0%84_12.55.49.png)

이렇게 되버린다.

해결하기위해..

![Horizontal 을 EqualSpacing에서 Equal Centering으로 변경했더니 이렇게 변함](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-04_%EC%98%A4%EC%A0%84_12.58.31.png)

Horizontal 을 EqualSpacing에서 Equal Centering으로 변경했더니 이렇게 변함

해결방법은 많다.

위에서 어떠한 길이도 제약조건을 주지않았다.

그 말은 간단히 말해 찌그러지기전 모두 비율로만 오토 레이아웃을 설정 하였고,

그 외의 지정하지 않았기 때문에 오류가 난것으로 확인된다.

ㄴ

ㄴ

![스크린샷 2021-11-06 오전 2.03.25.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.03.25.png)

먼저 나의 방법은 맨위칸의 Distribution을 Equal Sapcing으로 설정해 주었다

이렇게 해도 맨아래쪽에서

![스크린샷 2021-11-06 오전 2.05.05.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.05.05.png)

이렇게 에러가난다

내가해결한 방법을 

맨아래의 horizontal stack view의 Distribution을 

Fill spacing 에서 Fill로 바꾸어 주었다

![스크린샷 2021-11-06 오전 2.07.13.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.07.13.png)

UI의 모서리를 라운드로 만들기위해

코코아터치 파일 생성후

![스크린샷 2021-11-06 오전 2.16.30.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.16.30.png)

여기서 코드 작성 후

![스크린샷 2021-11-06 오전 2.20.19.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.20.19.png)

identity inspector에서 class를 방금 만들어준 RoundButton으로  바꿀수 있는데

![스크린샷 2021-11-06 오전 2.21.46.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.21.46.png)

이렇게 맨위에 Round Button의 속성 인스펙터가 생성된것을 알 수 있다.

빌딩하는데 시간이 조금 걸리고 바로 확인할 수있다

![스크린샷 2021-11-06 오전 2.22.43.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.22.43.png)

![스크린샷 2021-11-06 오전 2.23.00.png](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.23.00.png)

![찌그러져 나오긴하는데.. 원인을 나중에 찾아보자구](Chap2_3%206349fb943959411a8a82f94ee035eb75/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2021-11-06_%EC%98%A4%EC%A0%84_2.44.03.png)

찌그러져 나오긴하는데.. 원인을 나중에 찾아보자구

@IBDesignable을 사용하면 매번 빌드 과정을 거치기 때문에 오류나버벅일 수 있다.
