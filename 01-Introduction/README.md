[Eng | 영어](#01-introduction-what-is-javascript)
/
[Kor | 한국어](#01-소개-자바스크립트는-무엇인가)

# 01-Introduction: What is JavaScript?

## 1.1 Summary

JavaScript is a **dynamic, weakly typed** programming language which is **compiled at runtime.**
It can be executed as part of a webpage in a browser or directly on any machine("host environment").

JavaScript was created **to make webpages more dynamic.**
(e.g. change content on a page directly from inside the browser)
Originally, it was called LiveScript but due to the popularity of java, it was renamed to JavaScript.

JavaScript is totally independent from Java and has **nothing in common with Java!**

## 1.2 How Is JavaScript Executed?

Let's say you write your Javascript code and you want it to have some effect on the web page.
if we talk about the browser as the environment where we run our script.
Then you have one important thing built into any environment where you want to run Javascript code and
that's a **Javascript engine.**

It's built into the browser as I said,
there in Chrome for example, in the Chrome browser, it's v8, that's the name of the engine, in Firefox the name would be spider monkey.

Now the job of the engine is to parse code, so parse, read and understand your Javascript code,
then on the fly compile it to machine code because machine code executes faster,
so it reads your code but it does not necessarily execute it like that but instead,
it now takes that code and compiles it to code which is faster to execute by the machine
and then it executes that machine code.

This all happens in the browser with the help of the Javascript engine

## 1.3 Dynamic? Weakly Typed?

## 1.4 JavaScript Runs On A Host Environment

## 1.5 JavaScript and Java

<br>

# 01-소개: 자바스크립트는 무엇인가?

## 1.1 요약

JavaScript는 **런타임시 컴파일되는 동적, 약형 프로그래밍 언어이다**
브라우저에서 웹페이지의 일부로 실행되거나, 호스트 환경이라 불리는 모든 장치에서 직접 실행될 수 있다.

JavaScript는 **웹페이지를 보다 동적으로 만들기 위해** 만들어졌다.
(예를들면, 브라우저 내에서 페이지의 내용을 직접 변경하는 일)
최초에는 LiveScript 라는 이름으로 불렸지만, 당시 Java의 인기로 인해 JavaScript로 이름이 변경되었다.

하지만 JavaScript와 Java는 완전하게 별개로, 둘 사이에는 공통점이 전혀 없다.

## 1.2 자바스크립트는 어떻게 실행되는가?

스크립트 실행환경이 브라우저인 경우를 가정하여
JavaScript 코드를 작성하여 웹페이지의 효과를 주고 싶을때
코드를 실행하는 환경에 내장된 중요한 것이 있는데,
그게 바로 **JavaScript 엔진**이다.

크롬의 경우 V8, 파이어폭스의 경우 SpiderMonkey 같은 것들이 있다.

이러한 엔진의 역할은 코드를 분석해 읽고 이해하여,
컴퓨터가 실행할 수 있도록 기계어 코드로 변환하는 역할을 한다.
즉, 코드를 읽고 바로 실행하는 것이 아니라
코드를 읽은 후 컴파일을 통해 기계어 코드로 변환하여
컴퓨터가 이를 실행할 수 있도록 만든 후에 실행을 하는 것이다.

## 1.3 동적, 약형 언어?