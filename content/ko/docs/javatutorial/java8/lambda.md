---
title: "Lambda expression"
date: 2021-08-14T15:38:25+09:00
description: 람다 표현식
draft: true
weight: 1
enableToc: true
tocLevels: ["h2", "h3", "h4"]
---

# 람다 표현식

{{< boxmd >}}
Scala와 같은 다른 프로그래밍 언어를 아시는 분이라면 `람다 표현식(Lambda expressions)`에 대해서 알고 계실겁니다.
람다 표현식은 Java 8에서 추가된 매우 흥미로운 기능입니다.
{{< /boxmd >}}

- 자바 프로그래밍 언어에서 람다 표현식(혹은 함수)은 `익명 함수(anonymouse function)`를 말합니다.
    - __익명 함수__ : 이름이 없는 함수, 식별자가 없다
- 특히 함수의 파라미터에 자주 사용됩니다.


## 1. 람다 표현식이란?

## 2. 문법

```java
(parameters) -> expression

(parameters) -> { statements; }

() -> expression
```


### 2.2. 람다 표현식을 작성하는 규칙

1. 람다 식은 0 또는 하나 이상의 모수를 가질 수 있습니다.
2. 매개 변수의 유형은 명시적으로 선언하거나 컨텍스트에서 추론할 수 있습니다.
3. 여러 매개변수는 필수 괄호로 묶고 쉼표로 구분됩니다. 빈 괄호는 빈 매개변수 집합을 나타내는 데 사용됩니다.
4. 매개 변수가 하나 있을 때 매개 변수 유형이 유추된 경우 괄호를 사용할 필요가 없습니다.
5. 람다 식 본문은 0, 1개 이상의 문을 포함할 수 있습니다.
6. 람다 표현식의 본문에 하나의 문이 있는 경우 대괄호는 필수 항목이 아니며 익명 함수의 반환 유형은 본문 표현식과 동일합니다. 본문에 두 개 이상의 문장이 있는 경우 이러한 문구는 곱슬 괄호로 묶어야 합니다.


## 3. Java 8 람다 표현식의 특징들


[Functional Interface](/ko/docs/javatutorial/java8/functional/)

## 4. Java 8 Functional Interface


## 5. 예제들 
