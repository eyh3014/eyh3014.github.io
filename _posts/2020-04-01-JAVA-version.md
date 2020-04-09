---
layout: single
title:  "JAVA version"
date:   2020-04-01 10:29:00 +0900
categories: jekyll update
---

# Java

<img src="https://dbscthumb-phinf.pstatic.net/4874_000_1/20170502190804493_5QKHFU8SI.jpg/ka39_117_i1.jpg?type=m4500_4500_fst&amp;wm=N" alt="alt text" style="zoom:50%;" />

* ### java 란

썬 마이크로시스템즈에서 1995년에 개발한 객체 지향 프로그래밍 언어이고 창시자는 [제임스고슬링](https://ko.wikipedia.org/wiki/제임스_고슬링)이다. 2010년에 오라클이 썬 마이크로 시스템즈를 인수하면서 Java의 저작권을 소유하여 개발, 관리, 배포를 주관하고 있다.

* ### java의 특징

덩치가 작고, 보안에 민감하며, 여러 운영체제에 이식성이 뛰어나다는 데에 있다. 이후 자바 기술은 융통성과 효율성, 플랫폼 이식성 및 보안을 통해 네트워크 컴퓨팅 기술로 자리매김하였으며, 대부분의 주요 산업 분야에서 사용되어 여러 종류의 장치와 컴퓨터 및 네트워크에서 찾아볼 수 있게 되었다.

* ### java의 버전별 역사

  1. ##### 초기자바 ~ JDK 1.0

     * 1991년, OAK 발표: GE사의 요청으로, 썬마이크로 시스템즈에서 C++의 단점을 극복하고자 만든 언어.  메모리 할당/해제의 어려움과 다중상속으로 인한 실수유발을 극복하려고 했다.
     * 1996년, JDK 1.0발표 :  언어 이름을 자바라 바꾸고, Java Virtual Machine 1.0을 발표했다. Java Applet도 이때 처음 도입.

  2. ##### JDK1.1

     * 1997년 : RMI, JDBC, reflection, JIT,Inner Class 개념이 포함되었다.

  3. ##### JDK1.2

     * 1998년 Java SE 1.2, ME 1.2, EE 1.2 발표 
     * 자바를 세가지 버전으로 나눴다. Swing이 SE에 포함, Corba IDL(이종기기간 함수호출 스펙), Collection Framework 포함

  4. ##### JDK1.3

     * 2000년도 출시
     * HotSpot(Sun에서 만든 JIT구현), JNDI(디렉토리랑 이름으로 원하는 서비스찾는것) 포함

  5. ##### JDK1.4

     * 2002년도 출시
     * JCP(Java Community Process)에 의해서 오픈소스 정책으로 자바가 관리되기 시작한 버전.
     * Java 2 Security 모델의 확립(Sandbox)
     * Java Web Start포함 (Java Applet이 브라우저에서 돌아가는 것과 다르게, 외부 sandbox에서 동작)
     * Language: assert 도입
     * API : Regular Expression, Assert keyword, Security 2 version(현재 security model), Non Blocking IO(NIO)

  6. ##### JDK1.5

     * 2004년도 출시
     * 기능적으로 가장 많은 변화가 생긴버전 (Generics가 가장 대표적)
     * LanguageI: Generics , annotation, auto boxing, enum,vararg ,foreach, static imports 도입
     *  API : java.util.concurrent API, scanner class

  7. ##### JDK1.6

     * 2006년도 출시
     * 기능에 별 차이 없슴 - 보안, 성능강화 주력. 
     *  JVM/Swing에 있어 많은 Performance 향상(synchronization, compiler, GC,start-up time)
     *  G1(Garbage First) GC도입.

  8. ##### JDK1.7

     * 2011년도 출시
     * JVM : Dynamic Language support (invokedynamic - new byte operation)
     * Language : Switch에서 String, try-resource, generics에서 타입추론, 숫자에서 underscore사용
     * API:Concurrency 강화, NIO 강화, sort강화, crypto강화, GPU강화
     * JavaFX가 기본으로 포함
     * 안정적인 ARM지원

  9. ##### JDK1.8

     * 2014
     * 오라클로 인수된 후 첫번째 버전
     * JDK 1.5이후 가장 큰 언어적 변화(Lambda및 함수형프로그래밍,default method)이며 러닝커브가 크다.
     *  JEP에 의해서 새로운 기능들이 발의되기 시작.
     * Language : Lambda expression, Default Method Interface, functional programming for MapReduce style 지원, default method이용한 다중상속지원,메소드 참조
     * API : Nashorn (JS엔진), new Date and Time API, stream api,Collection에 대한 함수형화 (Interface에 default가 생김으로서 가능)
     * 병철처리에 접합한 구조로 진화

  10. ##### JDK1.9

      * 2017
      * 자바 플랫폼 모듈 시스템

