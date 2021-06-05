
## :memo: Table of Contents

- [What is this?](#what-is-this)
- [면접에서 받았던 질문들](#면접에서-받았던-질문들)
- [Part 1. CS](#part-1-전산-기초)
  - [개발상식](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Development_common_sense)
  - [자료구조](https://github.com/JaeYeopHan/for_beginner/tree/master/DataStructure)
  - [네트워크](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Network)
  - [운영체제](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/OS)
  - [데이터베이스](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Database)
  - [디자인패턴](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/DesignPattern)
  - [알고리즘](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Algorithm)
- [Part 2. Language](#part-2-language)
  - [Java](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Java)
  - [JavaScript](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/JavaScript)
  - [Python](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Python)
- [Part 3. 분야별 정리](#part-3-분야별)
  - [FrontEnd](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/FrontEnd)
  - [iOS](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/iOS)
  - [Machine Learning](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/MachineLearning)
- [그 외 좋은 자료 추천](#그-외-좋은-자료)

</br>

</br>

# What is this?

예비 개발자들 또는 개발자들의 기술 면접 준비를 위한 자료를 정리해놓은 저장소입니다. 

### [면접에서 받았던 질문들](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/issues/59)

해당 Issue 에서 실제로 받았던 면접 질문들을 공유할 수 있습니다.

---


### [회사에 궁금한 점이 있으신가요?](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Reverse_Interview)

인터뷰를 마치고 한번씩은 반드시 들어봤을 질문입니다. 이 때 어떠한 질문을 하면 좋을까요? 적절한 질문들을 정리해둔 Reverse Interview 목록입니다.

---

# Part 1. 전산 기초

## :bulb: 개발상식 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Development_common_sense)

- 좋은 코드란 무엇인가?
- 객체 지향 프로그래밍이란 무엇인가?
- RESTFul API 란?
- TDD 란 무엇이며 어떠한 장점이 있는가?
- 함수형 프로그래밍이란?
- MVC 패턴이란 무엇인가?
- Git 과 GitHub 에 대해서

</br>

## :bulb: 자료구조 [Link](https://github.com/JaeYeopHan/for_beginner/tree/master/DataStructure)

- Array vs Linked List
- Stack and Queue
- Tree
  - Binary Tree
  - Full Binary Tree
  - Complete Binary Tree
  - BST (Binary Search Tree)
- Binary Heap
- Red-Black Tree
  - 정의
  - 특징
  - 삽입
  - 삭제
- Hash Table
  - Hash Function
  - Resolve Collision
    - Open Addressing
    - Separate Chaining
  - Resize
- Graph
  - Graph 용어 정리
  - Graph 구현
  - Graph 탐색
  - Minimum Spanning Tree
    - Kruskal algorithm
    - Prim algorithm

</br>

## :bulb: 네트워크 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Network)

- GET, POST 방식의 차이점
- TCP 3-way-handshake
- TCP 와 UDP 의 차이점
- HTTP 와 HTTPS 의 차이점
  - HTTP 의 문제점들
- DNS round robin 방식
- 웹 통신의 큰 흐름

</br>

## :bulb: 운영체제 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/OS)

- 프로세스와 스레드의 차이
- 스케줄러의 종류
  - 장기 스케줄러
  - 단기 스케줄러
  - 중기 스케줄러
- CPU 스케줄러
  - FCFS
  - SJF
  - SRT
  - Priority scheduling
  - RR
- 동기와 비동기의 차이
- 멀티스레드
  - 장점과 단점
- 프로세스 동기화
  - Critical Section
  - 해결책
- 메모리 관리 전략
  - 메모리 관리 배경
  - Paging
  - Segmentation
- 가상 메모리
  - 배경
  - 가상 메모리가 하는 일
  - Demand Paging (요구 페이징)
  - 페이지 교체 알고리즘
- 캐시의 지역성
  - Locality
  - Caching line

</br>

## :bulb: 데이터베이스 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Database)

- 데이터베이스
  - 데이터베이스를 사용하는 이유
  - 데이터베이스 성능
- Index
  - Index 란 무엇인가
  - Index 의 자료구조
  - Primary index vs Secondary index
  - Composite index
  - Index 의 성능과 고려해야할 사항
- 정규화에 대해서
  - 정규화 탄생 배경
  - 정규화란 무엇인가
  - 정규화의 종류
  - 정규화의 장단점
- Transaction
  - 트랜잭션(Transaction)이란 무엇인가?
  - 트랜잭션과 Lock
  - 트랜잭션의 특성
  - 트랜잭션의 상태
  - 트랜잭션을 사용할 때 주의할 점
- Statement vs PreparedStatement
- NoSQL
  - 정의
  - CAP 이론
    - 일관성
    - 가용성
    - 네트워크 분할 허용성
  - 저장방식에 따른 분류
    - Key-Value Model
    - Document Model
    - Column Model

#### 추가자료

- [DBMS 는 어떻게 트랜잭션을 관리할까?](https://d2.naver.com/helloworld/407507)

</br>

## :bulb: Design Pattern [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/DesignPattern)

- Singleton

</br>

## :bulb: Algorithm (알고리즘) [Link](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Algorithm)

- 손코딩 및 코딩 테스트 대비
  => 대부분의 내용이 코드이기 때문에 별도의 [Java Algorithm Training Repository](https://github.com/JaeYeopHan/algorithm_basic_java)에 저장합니다.
- 코딩 테스트를 위한 Tip
- 문제 해결을 위한 전략적 접근
- Sorting Algorithm
- Prime Number Algorithm

</br>

<sup>[(목차로 돌아가기)](#technical-interview-guidelines-for-beginners)</sup>

</br>

---

</br>

# Part 2. Language

## :gem: Java [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Java)

- JVM 에 대해서 / GC 의 원리
- Collection
- Annotation
- Generic
- final
- Overriding vs Overloading
- Access Modifier
- Wrapper class
- Multi-Thread 환경에서의 개발

#### 추가 자료

- [Java 기본서 비교](http://asfirstalways.tistory.com/146)

</br>

## :gem: JavaScript [Link](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/JavaScript)

- JavaScript Event Loop
- Hoisting
- Closure
- this 에 대해서
- Promise

#### 추가 자료

- [JavaScript 기본서 비교](http://asfirstalways.tistory.com/246)
- [ECMAScript6 정리](https://jaeyeophan.github.io/categories/ECMAScript6)
- [Interview Algorithm Questions in JavaScript (영어)](https://github.com/kennymkchan/interview-questions-in-javascript)
  - JavaScript 와 관련된 인터뷰 관련 내용들을 정리해놓은 자료입니다.
    </br>

