markdown 강의
========
markdown language study

**************

# Inline Code

# (Python에서 `random` 패키지에서 `randint` 함수를 사용하세요.)

<!--
[//]: # "인라인 코드를 작성하려면 틱을 이용하세요"
[]: # 'Python에서 `random` 패키지에서 `randint` 함수를 사용하세요.'
-->

# 코드
    def sum(a,b):
        return a + b

# Python Code
```python
name = 'World'
print(name)
```

```java
int a = 1;
float b = 2;
double c = 3;
```
-----------------------

## 차례
1. [강조](#Emphasis)
2. [리스트](#Lists)
   1. [숫자 없는 리스트]()

## Emphasis Is Here

이것은 한 *문장*입니다.  
이것은 다음 문장입니다.

이것은 다음 **문단**입니다.  
이것은 다음 문장입니다.

이것은 또다른 ***문단***입니다.
이 내용을 ~~취소~~해요.

## Lists
### 헤더

- 첫번째 아이템
  - 서브 아이템
    - 서서브 아이템
  - 서브 아이템2
- 두번째 아이템
- 세번째 아이템
+ 네번째 아이템
* 다섯번째 아이템

1. 첫번째 아이템
   1. 서브 아이템
3. 두번째 아이템
   - 서브 아이템
5. 세번째 아이템

## 테이블

|첫번째 열|두번째 열|세번째 열|네번째 열|
|----------|:----------|:--------:|-----:| 
|기본| 왼쪽정렬|아무거나|아무거나|
|아무거나|아무거나|아무거나|아무거나|

|제목|내용|설명|
|------|---|---|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|

## 링크
구글로 가고 싶으면 [이것]을(https://www.google.com/webhp?hl=ko&sa=X&ved=0ahUKEwjAp5iB8_zvAhV8w4sBHcccDn0QPAgI)을 클릭하세요.
구글로 가고 싶으면 [이것]을(https://www.google.com/webhp?hl=ko&sa=X&ved=0ahUKEwjAp5iB8_zvAhV8w4sBHcccDn0QPAgI"구글 홈페이지")을 클릭하세요.
라이선스를 보고 싶으면 [이것]을(./LICENSE)을 클릭하세요.  
구글로 가고 싶으면 [이것]을[구글]을 클릭하세요.  
구글로 가고 싶으면 [이것]을[네이버]을 클릭하세요.  

구글 홈페이지 = https://www.google.com/webhp?hl=ko&sa=X&ved=0ahUKEwjAp5iB8_zvAhV8w4sBHcccDn0QPAgI 입니다.  
구글 홈페이지 = <https://www.google.com/webhp?hl=ko&sa=X&ved=0ahUKEwjAp5iB8_zvAhV8w4sBHcccDn0QPAgI> 입니다.  

[]: https://www.google.com/webhp?hl=ko&sa=X&ved=0ahUKEwjAp5iB8_zvAhV8w4sBHcccDn0QPAgI
[]: https://www.naver.com/

강조를 사용하려면 [Emphasis 섹션](#Emphasis-Is-Here)을 참고해주세요


![로고]
(https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "구글 로고")

> 너 자실을 알라.  
> 나도 모른다.
>  - 소크라테스

![이미지가 없을때 나오는 텍스트]
(https://www.google.co.kr/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "마우스를 위에 가져다 놓았을때 나오는 설명")

<img
src = "https://www.google.co.kr/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" width=100>
</img>

