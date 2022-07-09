---
title: "마크다운(Markdown) 공부하기 2"
last_modified_at: 2022-07-09
categories:
  - Blog
tags:
  - standard
  - markdown
  - study
---

이 공부는 블로그 : [TheoryDB 블로그](https://theorydb.github.io) 님 블로그 내용을 참고하여 진행했습니다.  
지난 시간에 8번 이미지 삽입까지 공부했는고, 이번엔 이후 내용을 다룰 예정

# 마크다운 문법2 (유용한 부가기능)
+ 표그리기
|                  | 수학                        | 평가              |  
|:--- | ---: | :---: |  
| 철수             | 90            | 참잘했어요. |  
| 영희           | 50            | 분발하세요. |

1. 라인 단위로 구분자 | 사용
2. 헤더(머리글)을 분리하고 싶은 경우 --- 사용
3. 정렬이 필요한 경우 : 기호를 --- 구분선 왼쪽(좌측정렬), 오른쪽(우측정렬), 양쪽(양쪽 배치)에 사용 가능

+ 수식: 논문 분석 등 활용 가능
수식은 $$으로 둘러쌓여야 하고 (),{}으로 감싸면 우선순위를 고려한 동일 단위로 인식한다.
$$f(x)= if x < x_{min} : (x/x_{min})^a$$  
$$otherwise : 0$$  
$$P(w)=U(x/2)(7/5)/Z$$  
$$p_{\theta}(x) = \int p_{\theta}(2z)p_{\theta}(y\mid k)dz$$  
$$x = argmax_k((x_t-x_u+x_v)^T*x_m)/(||x_b-x_k+x_l||)$$

수식 어렵네^^ 대충 복붙하고 넘김

+ 코드 블록(Code Block): 소스코드, 외부 인용자료 블록처리 등에 사용
```python
py_vector = one_hot_encoding("파이",word2index)
py_vector.dot(torch_vector)
>>> 0.0
``` 
```C++
class Hello{
private:
  string name;
  int age;
public:
  void setName(string name){
  this->name = name;}
  void setAge(int age){
  this->age = age;}
  string getName(){retrun name;}
  int getAge(){return age;}
 };
 
```
그냥 복습 겸 c++ 써봄

신기한 내용이 많구만
공부 끝
