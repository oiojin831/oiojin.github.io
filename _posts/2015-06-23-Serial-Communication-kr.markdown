---
layout: post
title: "Serial Communication kr"
categories: translate embedded sparkfun
---

[원본](https://learn.sparkfun.com/tutorials/serial-communication)
Sparkfun의 튜토리얼 글을 일고 간략하게 정리 및 의역한 글입니다.

# Serial Communication

## Introduction
Embedded electronics는 결국은 회로들의 연결이다. 각각의 회로들이 정보를 교환하기 위해서는 일반적인 통신 프로토콜(communication protocol)을 공유해야한다. 이러한 데이터 교환을 위한 통신 프로토콜이 많이 정의 되었지만 일반적으로 두가지 종류로 분류할수있다. 병렬 또는 직렬이 있다.(parallel, serial)

### Parallel vs. Serial
Parallel interfaces는 동시에 여러개의 bits를 전달한다. 
![paralleVserial](https://cdn.sparkfun.com/assets/c/a/c/3/a/50e1cca6ce395fbc27000000.png)
[직렬통신](http://mintnlatte.tistory.com/197)

* circuits
* protocol
* buses
