# _WS_DataStructure_
_WS_DataStructure_ Read me!!
 - 자료구조와 알고리즘 
 - 슬랙 초대 요청 :: 
 - 재추진..
# 0.시작하기 전
 ## 로드맵
 ```
 1. 열혈 자료구조 (윤성우 님 저서)
 2. 뇌를 자극하는 알고리즘 (박상현 님 저서)

3. 알고리즘 인생을 계산하다
4. c9R
 ```
 ## 개발환경 셋팅 
 ### Cross-flatform 자료구조
 - OS에 영향을 받지않기 위해서 : GCC(컴파일러) + VSCode(Editor) + Cmake(유틸리티)
 - Editor : VS Code
 - Compiler : C언어 컴파일러  
 - 지원 OS : Linux Ubuntu 18/Windows10/Mac mojave or else 사용가능
 
 
 * note : 알고리즘 교재의 경우 "C로 구현한 알고리즘 - Kyle Loudon 저 / 허욱 역" 교재 또한 고려중임 (단종됨)

# 1.Schedule (열혈 자료구조)


  ```
    2018-12-28	챕터 1
    2019-01-04	챕터 2
    2019-01-11	챕터 3
    2019-01-18	챕터 4
    2019-01-25	해외출장
    2019-02-01	설날 휴무
    2019-02-08	챕터 5
    2019-02-15	챕터 6
    2019-02-22	챕터 7
    2019-03-01	챕터 8
    2019-03-08	복습/예비
    2019-03-15	챕터 9
    2019-03-22	챕터 10
    2019-03-29	챕터 11
    2019-04-05	챕터 12
    2019-04-12	챕터 13
    2019-04-19	챕터 14
    2019-04-26	플젝:은행관리
    ->> 어 이상하다? 분명이 끝나있어야 하는데..??
  ```
 * 열심히 해보시죵 : )
===============================================
## 2019-06-02 진행
   1. Bitree(333p, 문제8-2풀어오기 enk:다시짜오기, dhkim:고민&문제해결)
   2. Stack 계산기 진행 완료(~250p)
   3. 두문제 풀어오기
       * (https://leetcode.com/problems/validate-stack-sequences/)
       * (https://leetcode.com/problems/n-ary-tree-preorder-traversal/)
   * 일정: 6/5 (수) 22



할일 정리 (To Do list)
[공지사항]
  -스터디 학습법 변경 : 학습시간에 코드 생각해보고 짜기, 각자 학습 구역에 대해 기본개념만, 핵심 소스코드는 학습시간에 고민 및 해결
  -담당 구역은 스터디 이전에 개념만 정리해서 가져와 설명하기
  - 개발환경은 GCC컴파일러 + Makefile프로젝트
  - OS는 리눅스를 추천하나 맥, 윈도우 모두 가능
  - 추천 에디터는 VScode, VIM

[민준님]
  - Chp10(정렬) - 개념정리 및 예제소스 작성 및 소개

[봉준님]
  - chp11(탐색1) - 개념정리 및 예제소스 작성 및 소개

[동훈]
  - chp12(탐색2) - 개념정리 및 예제소스 작성 및 소개
  - chp9 (우선순위큐와 힙) 개념정리
  - 모든 프로젝트 Makefile화 -> 3_seminar 폴더 참고

[향후 일정]
  - 8/06 : chp9 우선순위 큐 힙
  - 8/13 : chp10~12
  - 8/20 : chp13
  - 9/03 : chp14 - 1회
  - 9/10 : chp14 - 2회

[3차시 ]
  - 목표 : 10월 30일까지 끝내기 1회독!!!


 * ===========================================================================================
 - 참고 : https://www.edwith.org/cs50 - 하바드 컴교양강좌
 - 참고 : http://panthema.net/2013/sound-of-sorting/ - 정렬알고리즘 시청각화
  - 다음 공부 : 
    - https://slack-redir.net/link?url=http%3A%2F%2Fwww.yes24.com%2F24%2FUsedShop%2FGoods%2F3524901
    - https://www.aladin.co.kr/shop/UsedShop/wuseditemall.aspx?ItemId=4563781&start=pnoranbook&partnerPop=noranbook
  - 개발환경
    - http://www.mingw.org/
    - https://cmake.org/
    - http://solver.assistedcoding.eu/makefilegen - 메이크파일 만드는 사이트
    - 중요한건 : C:\MinGW\msys\1.0\bin 을 꼭 환경변수 추가하기 ( 메뉴얼 : https://blog.rovitek.com/35)
   
 * ========================================================================================
 * ========================================================================================
    할일 : "ALGraph.c" 파일 완성하기
    Question1. 코드완성 - GraphInit() 함수속 동적할당의 크기를 결정하기
    Question2. 코드완성 - GraphDestroy() 함수 구현하기
    Question3. 코드완성 - GraphDestroy() 함수 속 free 함수 완성하기
    Question4. 주석달기 - 2Line에 걸처 LInsert() 함수가 호출되는 의미를 그래프 자료구조와 연결시켜 설명하기
    Question5. 주석달기 - ShowGraphEdgeInfo() 함수 완성하기

    ==============================================================
    정답시 출력 
    A between connected Vertex: B D E
    B between connected Vertex: A C
    C between connected Vertex: B D
    D between connected Vertex: A C E
    E between connected Vertex: A D

    * a.exe 참고


    ==============================================================
    참고 - 터미널 명령어 
    빌드 : $make all
    정리 : $make clean
    실행 : a.exe (a.exe파일 실행)


  

 * ========================================================================================
 * ========================================================================================
  * 과제 2
    할일 : "DFShowGraphVertex(ALGraph * pg, int startV)" 함수 완성하기
    Question1. 참거짓판단(TRUE or FALSE) - LFirst(&(pg->adjList[visitV]), &nextV) 리턴값으로 알맞은 것은?
    Question2. 코드완성 
      - if(VisitVertex(pg, nextV) == /*/Q1 TRUE or FALSE/*/)//nextV의 방문에 성공한 경우
      - SPush(/*/Q2/*/); //visitV의 정보는 스텍에 PUSH 
    Question3. 코드완성 

    ==============================================================
    정답시 출력 

    C between connected Vertex: B D
    D between connected Vertex: A C E
    E between connected Vertex: D F G
    F between connected Vertex: E
    G between connected Vertex: E
    A B C D E F G
    C B A D E F G
    E D A B C F G
    G E D A B C F

    * a.exe 파일 실행


    ==============================================================
    참고 - 터미널 명령어 
    빌드 : $make all
    정리 : $make clean
    실행 : a.exe (a.exe파일 실행)

