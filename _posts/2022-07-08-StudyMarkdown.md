---
title: "마크다운(Markdown) 공부하기 1"
last_modified_at: 2022-07-08
categories:
  - Blog
tags:
  - standard
  - markdown
  - study
---

이 공부는 블로그 : [TheoryDB 블로그](https://theorydb.github.io) 님 블로그 내용을 참고하여 진행했습니다.

# 1. 마크다운(Markdown)이란?
마크다운은 일반 텍스트 문서의 양식을 편집하는 문법이다. README 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로 문서 양식을 편집할 때 쓰인다. 
배우기가 직관적이며 여러 툴을 통해 HTML 등 다른 문서 형태로 변환도 용이하다.

# 마크다운 문법 
## 1. 제목 쓰기
1단계 ~ 6단계까지 '#'의 갯수를 늘려가며 강조를 다르게 할 수 있다.
# 1단계
## 2단계
### 3단계 등!

## 2. 수평선: 내용을 명시적으로 구분하고 싶을 때
---

## 3. 엔터키: 라인을 바꾸고 싶을 때
가나다라  
마바사
문장 끝에 스페이스바 2번  
혹은 줄바꾼 첫머리에 # 추가

## 4. 목록(list): 요소를 나열할 때
1. 첫 번째
2. 두 번째
3. 세 번째
+ 순서없음
- 홍길동
* 중대장

## 5. 강조: 문장 내 강조하고 싶은 단어를 눈에 띄게
__볼드(진하게)__
_이탤릭체(기울여서)_
~~취소선~~
<u>밑줄</u>
__볼드로 진하게 만들다가*이탤릭으로 기울이고*다시 볼드로__(중복 활용도 가능하다.)

## 6. 인용구: 인용할 경우 또는 분위기 전환시에도 사용(중복 형태 가능)
> 안녕하세요
> > 제 블로그에 와주셔서
> > > 감사합니다!

## 7. 링크(Link): 클릭하면 다른 페이지, 다른 부분으로 이동 가능
유형1('설명어'를 클릭하면 URL로 이동) : [eoeon github.io] (https://seoyeonchoi.github.io/ "어서오세요!!")
유형2(URL 보여주고 자동연결) : <https://seoyeonchoi.github.io/>
유형3 문단 내 다른 부분 연결인데 아직 조금 어려움

## 8. 이미지(image): 보여주기
유형1('이미지' 삽입) :
![이미지](https://raw.githubusercontent.com/seoyeonchoi/mypage/main/%EA%B3%A0%EC%8B%AC.png "고심하이")  
#유형2('사이즈를 조절'하고 싶은 경우 HTML 태그로 처리) :
<img src = "https://raw.githubusercontent.com/seoyeonchoi/mypage/main/%EA%B3%A0%EC%8B%AC.png" width="300" height="300">  
#유형3(이미지 삽입 후, '링크 걸기') :
[![이미지](https://raw.githubusercontent.com/seoyeonchoi/mypage/main/%EA%B3%A0%EC%8B%AC.png)](https://seoyeonchoi.github.io/)  

