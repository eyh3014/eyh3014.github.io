---
layout: single
title:  "Strassen Algorithm"
date:   2020-04-09 06:23:00 +0900
categories: jekyll update
---

# Strassen Algorithm

-------

### Volker Strassen

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Strassen_Knuth_Prize_lecture.jpg/640px-Strassen_Knuth_Prize_lecture.jpg" width="50%" height="50%">

폴커 슈트라센 은 1936년 4월29일생의 독일 수학자로, 콘스탄츠 대학교의 수학 및 통계학과 명예교수이다.

알고리즘 분석에 중요한 공헌을 한 그는 칸토르 메달, 패리스 카넬라키스 상을 수상했다. 특히 카누스 상은 *"효율적인 알고리즘의 설계 및 분석에 대한 영향력있는 기여"* 라고 덧붙였다.

슈트라센은 확률론적 연구로 그의 연구를 시작했다. 그의 1964년 논문 "반복 로그의 법칙에 대한 불변성 원리" 는 반복 로그의 법칙의 기능적 형태를 정의하여 무작위 행보에서 규모 불변량의 형태를 보여 주었다. 슈트라센의 "불변의 원리" 또는 "반복 로그의 슈트라센의 법칙" 으로 알려진 이 결과는 매우 자주 인용되어 1966년 세계 수학자 대회 에서 발표 되었다.



### Strassen Algorithm 이란?

* 슈트라센이 1969년에 만든 행렬 곱셈 알고리즘으로 기존 무식한 방식에 비해 시간복잡도가 더 낮은 O(n^2.81)을 보여준다.
* 행렬 C는 행렬 A와 B의 연산으로 이루어지며 행렬 A와 B는 2n * 2n 의 크기를 지닌 다. (n은 임의의 정수이다.) 만약 2n * 2n이 아닐 경우 빈 자리를 0으로 채워 2n * 2n 꼴로 만들고 쉬트라센 행렬 곱을 진행한다.
* 따라서 행렬 A, B, C는 서로 크기가 같은 4개의 부분 행렬로 분할이 가능하다.

![alt image](http://yimoyimo.tk/images/strassen2.png)





* A, B 행렬을 각가 4개씩 총 8개의 부분행렬로 분할한 후 쉬트라센 알고리즘 연산을 수행한다. 기존에 행렬곱은 단순히 8번의 곱셈과 4번의 덧셈이 필요했지만, 쉬트라센의 방법은 7번의 곱셈과 18번의 덧셈/뺄셈을 필요로 한다. 컴퓨터의 입장에서는 곱셈 연산이 덧셈 뺄셈 연산보다 부담이 크므로 쉬트라센 알고리즘이 훨씬 좋은 알고리즘이다.
* 슈트라센 알고리즘에 따라 다음 7개의 수식으로 곱 C를 표현할 수 있다.

![alt image](http://yimoyimo.tk/images/strassen3.png)

