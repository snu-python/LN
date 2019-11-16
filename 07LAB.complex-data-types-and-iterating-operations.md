실습 : 복합자료형과 순회형 연산
===

Lab: Complex Data Types and Iterating Operations

***

**박 진 수** 교수    
Intelligent Data Semantics Lab  
Seoul National University

***

다음 표는 성적 데이터를 이름순으로 정렬해서 보여주고 있다.

|이름|점수|
|-|-|
|네오|97|
|라이언|80|
|무지|60|
|어피치|95|
|제이지|45| 
|콘|88|
|튜브|75|
|프로도|56|

앞의 표에 나타난 성적 점수를 이름순으로 리스트로 만들어 *scores* 변수에 할당한 후, *scores*를 출력한다.


```python
# Your code here
scores = __TODO__
print(scores)
```

순회형 **연산자**를 사용해서 성적 점수 리스트 *scores* 중 0점 처리된 점수가 있는지 확인한다.


```python
# Your code here
__TODO__
```

최댓값을 찾아주는 함수를 사용해서 성적 점수 리스트 *scores* 중 가장 높은 점수를 변수*best_score*에 할당한 후, *best_score*를 출력한다.


```python
# Your code here
best_score = __TODO__  # 가장 큰 값을 가진 객체를 반환한다.
print(best_score)
```

최솟값을 찾아주는 함수를 사용해서 성적 점수 리스트 *scores* 중 가장 낮은 점수를 변수 *bottom_score*에 할당한 후, *bottom_score*를 출력한다.


```python
# Your code here
bottom_score = __TODO__ . # 가장 작은 값을 가진 객체를 반환한다.
print(bottom_score)
```

*best_score*와  *bottom_score*를 사용해서 두 점수의 차이를 변수 *difference*에 할당한 후, *difference*를 출력한다.


```python
# Your code here
difference = __TODO__  # 가장 높은 점수와 낮은 점수의 차이를 구한다.
print(difference)
```

성적 점수 리스트 *scores*의 평균 점수를 구해서 변수 *average*에 할당한 후, *average*를 출력한다.


```python
# Your code here
average = __TODO__  # 성적 점수 리스트의 평균을 구한다.
print(average)
```

성적 점수 리스트 *scores*의 점수를 <u>내림차순</u>으로 정렬해서 변수 *sorted_scores*에 할당한 후, *sorted_scores*를 출력한다.


```python
# Your code here
sorted_scores = __TODO__  # 성적 점수 리스트를 내림차순으로 정렬한다.
print(sorted_scores)
```

*sorted_scores*에 있는 점수를 역순으로 바꾼 후 튜플형으로 변수 *reversed_scores*에 할당한 후, *reversed_scores*를 출력한다.


```python
# Your code here
reversed_scores = __TODO__  # 성적 점수를 역순으로 뒤집어 튜플로 만든다.
print(reversed_scores)
```

상위 5개의 점수를 변수 *top5*에 할당한 후, *top5*를 출력한다.


```python
# Your code here
top5 = __TODO__
print(top5)
```

맨 앞에서 만든 성적 점수 리스트 *scores*에 있는 점수 중 60점 이상인 점수만 **if** 조건문을 사용해서 리스트 형식으로 출력한다.


```python
# Your code here
L = []  
for i in scores:  
    if __TODO__:  
        __TODO__
print(L)  
```

성적 데이터 표를 참고하여 각 학생의 이름을 키로, 각 점수를 매핑값으로 가지는 딕셔너리를 만들어 변수 *dict_scores*에 할당한 후, *dict_scores*를 출력한다.


|이름|점수|
|-|-|
|네오|97|
|라이언|80|
|무지|60|
|어피치|95|
|제이지|45| 
|콘|88|
|튜브|75|
|프로도|56|


```python
# Your code here
dict_scores = __TODO__
```

*dict_scores*에서 '라이언'의 점수를 출력한다.


```python
# Your code here
print(__TODO__)  
```

*dict_scores*에서 '제이지'의 점수를 71로 수정한 후 '제이지'의 점수를 출력한다.


```python
# Your code here
__TODO__
print(__TODO__)
```

성적 점수 딕셔너리 *dict_scores*에서 모든 학생 점수의 평균을 구해서 변수 *dict_average*에 할당한 후, *dict_average*를 출력한다.


```python
# Your code here
dict_average = __TODO__
print(dict_average)
```
---
**THE END**