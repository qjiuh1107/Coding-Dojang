# Coding-Dojang
## Unit 1-7
### 파이썬 기본 문법
[![Python](https://img.shields.io/badge/Python-Used-blue.svg)](https://shields.io/#/)

#### 문자열을 붙여서 사용할 때는 세미콜론을 이용하여 구분해준다.
```
print('Hello, world');print('Python Programming)
```
#### if 다음 줄은 항상 들여쓰기를 해야함; 들여쓰기를 하지 않으면 오류가 남./ 공백을 섞어써도 안됨.
```
if a== 10:
    print('10입니다')
```

### 숫자계산하기
#### 연산자:(덧셈-> +, 뺼셈 -> -, 곱셈 -> *, 나눗셈 -> /, 거듭제곱 -> **, 나머지 버리기(몫 구하기) -> //, 나머지 구하기 -> %)
#### 계산 결과를 정수, 실수로 만들고 싶을 때 

```
int(5 / 2)
float(1 + 2)
```

### 변수와 입력 사용하기
#### 산술 연산 후 할당 연산자 사용
```
a = 10
a += 20
a
30
```
#### 객체의 자료형 알아내기
#### -> 객체(변수)가 어떤 자료형인지 알고 싶을 땐 type함수를 사용한다.
```
type(3.3)
<class'flaot'>
x=10
type(x)
<class'int'>
```
#### 입력 값을 변수에 저장하기
```
s = input()           # 입력값을 문자열로 저장
a = int(input())      # 입력값을 정수로 저장
b = float(input())
```
#### 변수를 한 번에 여러개 입력받기
```
a, b = input().split() 
a, b = map(int, input().split())
a, b = map(float, input().split())

