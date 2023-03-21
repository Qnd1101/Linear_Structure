# 선형 구조

### 1. 연결 리스트(Linked List)

* ## 연결 리스트(Linked List)
  * ### 동적 메모리에 할당된 링크에 의해 연결된 유한 개수의 데이터 원소들
* ## 특징
  * ### 링크 값을 변화 시키는 것 만으로 노드의 삽입 삭제가 용이하다.
  * ### 기억공간이 연속적으로 놓여 있지 않아도 저장이 가능하다.
  * ### 연결을 위한 링크(포인터) 부분이 필요하기 떄문에 순차 리스트에 비해 기억공간 효율이 좋지 않다.
  * ### 연결을 할 때 포인터를 찾는 시간이 필요하여 접근하는 속도가 느리다.
  * ### 트리를 표현할 때 가장 적합한 자료이다.
  
* ## 노드(node)
### 자료와 포인터를 갖고 있는 것을 노드(node)라고 한다.
![image](https://user-images.githubusercontent.com/107795830/226497844-0d4ecdf7-bb33-409f-a05b-e6668acabad8.png)
![image](https://user-images.githubusercontent.com/107795830/226497920-c94e40ae-183e-4452-b02f-74435258d212.png)

* ## 회소 행렬
### 회소 행렬이란 요소 중에 0으로 저장 되어 있는 형태로 기억 장소를 절약하기 위해 Linked List를 이용하여 저장한다.