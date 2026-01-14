# algorithm-basic
목적

생각하는 힘 + 문제 해결력 증명
간단한 알고리즘 문제를 통해  
문제를 분석하고 해결하는 사고 과정을 연습하고 있습니다.

각 문제는 풀이 과정을 주석으로 설명하는 방식으로 작성했습니다.
# 문제: 두 개의 정수를 입력받아 더 큰 수를 출력하시오.
# 풀이 과정:
# 1. 두 수를 입력받는다.
# 2. if 문을 사용하여 두 수를 비교한다.
# 3. 더 큰 값을 출력한다.

a, b = map(int, input().split())

if a > b:
    print(a)
else:
    print(b)
# 문제: 1부터 n까지의 수 중 짝수의 합을 구하시오.
# 풀이 과정:
# 1. 반복문으로 1부터 n까지 확인
# 2. 짝수일 경우에만 누적 합

n = int(input())
total = 0

for i in range(1, n + 1):
    if i % 2 == 0:
        total += i

print(total)
mini-projects
 └─ robot-action-decider
     ├─ action_decider.py
     └─ README.md
# 로봇 행동 결정 프로그램
# 거리와 배터리 상태를 입력받아
# 로봇의 행동을 판단한다

distance = int(input("장애물과의 거리(cm): "))
battery = int(input("배터리 잔량(%): "))

if distance < 20:
    print("정지")
elif battery < 30:
    print("충전 필요")
else:
    print("전진")
# 로봇 행동 결정 프로그램

## 프로젝트 개요
로봇이 주변 상황에 따라  
적절한 행동을 결정하도록 만드는 간단한 제어 프로그램입니다.

## 사용 기술
- Python

## 구현 기능
- 거리 값 입력
- 배터리 상태 확인
- 조건에 따른 행동 판단

## 배운 점
조건문을 활용해 여러 상황을 고려하는 로직을 구성할 수 있었습니다.

## 향후 개선
실제 센서 입력과 연동해 보고 싶습니다.

---

## Algorithm Basic

### 목적

**생각하는 힘과 문제 해결 능력을 기르기 위해** 간단한 알고리즘 문제를 풀이하며,
문제를 분석하고 해결하는 사고 과정을 연습하고 있습니다.

각 문제는 **풀이 과정을 주석으로 설명하는 방식**으로 작성했습니다.

---

### 문제 1 : 두 개의 정수를 입력받아 더 큰 수를 출력하시오

#### 풀이 과정

1. 두 개의 정수를 입력받는다.
2. `if` 문을 사용하여 두 수를 비교한다.
3. 더 큰 값을 출력한다.

```python
a, b = map(int, input().split())

if a > b:
    print(a)
else:
    print(b)
```

#### 학습 내용

* 다중 입력 처리 (`map`, `split`)
* 조건문을 이용한 값 비교

---

### 문제 2 : 1부터 n까지의 수 중 짝수의 합을 구하시오

#### 풀이 과정

1. 반복문으로 1부터 n까지의 수를 확인한다.
2. 짝수일 경우에만 누적 합을 계산한다.

```python
n = int(input())
total = 0

for i in range(1, n + 1):
    if i % 2 == 0:
        total += i

print(total)
```

#### 학습 내용

* 반복문과 조건문의 결합 사용
* 누적 합 알고리즘 이해

---

##  Mini Project

### 📁 robot-action-decider

```
mini-projects
└─ robot-action-decider
   ├─ action_decider.py
   └─ README.md
```

---

##  로봇 행동 결정 프로그램

### 프로젝트 개요

로봇이 **거리와 배터리 상태**를 입력받아
주변 상황에 따라 적절한 행동을 결정하도록 만든 간단한 제어 프로그램입니다.

---

### 구현 코드

```python
distance = int(input("장애물과의 거리(cm): "))
battery = int(input("배터리 잔량(%): "))

if distance < 20:
    print("정지")
elif battery < 30:
    print("충전 필요")
else:
    print("전진")
```

---

### 사용 기술

* Python

---

### 구현 기능

* 거리 값 입력
* 배터리 상태 확인
* 조건에 따른 로봇 행동 판단

---

### 배운 점

* 여러 조건을 고려하는 조건문 로직을 구성할 수 있게 됨
* 로봇 제어에 필요한 기본적인 판단 구조를 이해함

---

### 향후 개선 방향

* 실제 센서 입력과 연동
* Arduino 기반 로봇 제어 프로그램으로 확장

---

## 마무리

이 포트폴리오는 **알고리즘 사고력과 로봇 제어 기초 역량**을 함께 쌓아가는 과정을 정리한 자료입니다.
앞으로 더 복잡한 알고리즘 문제와 실제 하드웨어 제어 프로젝트로 확장해 나갈 계획입니다.

# 📘 Python Algorithm & Mini Projects Portfolio

고등학교 입학 전, 파이썬 기초 문법과 알고리즘 사고력을 기르기 위해 학습한 내용을 정리한 포트폴리오입니다.
기본 문법 이해부터 간단한 로봇 제어 로직까지 단계적으로 연습했습니다.

---

## 🧠 Algorithm Basic

### 📌 목적

간단한 알고리즘 문제 풀이를 통해 **문제를 분석하고 해결하는 사고력**을 기르는 것을 목표로 합니다.
각 문제는 풀이 과정을 단계적으로 정리하고, 코드에는 주석을 통해 사고 과정을 설명했습니다.

---

### 문제 1. 두 개의 정수를 입력받아 더 큰 수를 출력하시오

#### 풀이 과정

1. 두 개의 정수를 입력받는다.
2. `if` 문을 사용하여 두 수를 비교한다.
3. 더 큰 값을 출력한다.

```python
a, b = map(int, input().split())

if a > b:
    print(a)
else:
    print(b)
```

#### 학습 포인트

* 다중 입력 처리 (`map`, `split`)
* 조건문을 활용한 값 비교

---

### 문제 2. 1부터 n까지의 수 중 짝수의 합을 구하시오

#### 풀이 과정

1. 반복문으로 1부터 n까지의 수를 확인한다.
2. 짝수일 경우에만 누적 합을 계산한다.

```python
n = int(input())
total = 0

for i in range(1, n + 1):
    if i % 2 == 0:
        total += i

print(total)
```

#### 학습 포인트

* 반복문과 조건문의 결합
* 누적 합 알고리즘 이해

---

## 🤖 Mini Projects

### 📁 robot-action-decider

```
mini-projects
└─ robot-action-decider
   ├─ action_decider.py
   └─ README.md
```

---

### 로봇 행동 결정 프로그램

#### 프로젝트 개요

로봇이 **장애물과의 거리**와 **배터리 잔량**을 입력받아,
현재 상황에 따라 적절한 행동을 결정하도록 만든 간단한 제어 프로그램입니다.

---

#### 구현 코드

```python
distance = int(input("장애물과의 거리(cm): "))
battery = int(input("배터리 잔량(%): "))

if distance < 20:
    print("정지")
elif battery < 30:
    print("충전 필요")
else:
    print("전진")
```

---

#### 사용 기술

* Python

---

#### 구현 기능

* 거리 값 입력
* 배터리 상태 확인
* 조건에 따른 로봇 행동 판단

---

#### 배운 점

* 여러 조건을 고려하는 조건문 로직을 설계할 수 있게 됨
* 로봇 제어의 기본적인 판단 구조를 이해함

---

#### 향후 개선

* 실제 거리 센서와 배터리 센서 입력과 연동
* Arduino 기반 로봇 제어 프로그램으로 확장

---

## ✨ 마무리

이 저장소는 **파이썬 기초 문법, 알고리즘 사고력, 로봇 제어 논리**를 함께 성장시킨 학습 기록입니다.
앞으로 더 복잡한 알고리즘 문제와 실제 하드웨어 제어 프로젝트로 확장할 계획입니다.

# 📘 Python Basic Grammar & Algorithm Portfolio

고등학교 입학 전, 파이썬의 **기초 문법과 알고리즘 사고력**을 기르기 위해 학습한 내용을 정리한 포트폴리오입니다.
조건문, 반복문, 팩토리얼, 문자열 포맷 등 프로그래밍의 핵심 개념을 예제 중심으로 학습했습니다.

---

## 1️⃣ 조건식 (Condition)

조건식이란 **True 또는 False로 판단할 수 있는 식**을 의미합니다.

```python
a = 10
b = 20

print(a > b)   # False
print(a == b)  # False
print(a < b)   # True
```

✔ 결과가 `True / False`로 나오면 모두 조건식입니다.

---

## 2️⃣ 선택문 (if Statement)

### 2.1 단일 선택문

```python
age = 15

if age >= 14:
    print("중학생 이상입니다.")
```

---

### 2.2 다중 선택문 (if - elif - else)

여러 조건 중 **하나만 실행**됩니다.

```python
score = 85

if score >= 90:
    print("A")
elif score >= 80:
    print("B")
elif score >= 70:
    print("C")
else:
    print("F")
```

---

### 2.3 양자 택일 선택문 (if - else)

두 가지 경우 중 하나를 선택합니다.

```python
num = 10

if num % 2 == 0:
    print("짝수")
else:
    print("홀수")
```

---

### 2.4 조건 표현식 (삼항 연산자)

```python
num = 10
result = "짝수" if num % 2 == 0 else "홀수"
print(result)
```

---

## 3️⃣ 반복문 (Loop)

### 반복문의 종류

* `for` 문
* `while` 문

---

## 4️⃣ for 반복문

시퀀스(iterable)의 요소를 하나씩 꺼내 반복합니다.

```python
for 변수 in 시퀀스:
    실행할 문장
```

### 예제 1 : 리스트 반복

```python
for animal in ["dog", "cat", "mouse"]:
    print(f"{animal} is a mammal.")
```

출력 결과

```
dog is a mammal.
cat is a mammal.
mouse is a mammal.
```

---

### 예제 2 : range 사용

```python
for i in range(4):
    print(i, end=" ")
```

출력 결과

```
0 1 2 3
```

---

## 5️⃣ 들여쓰기 (Indentation)

✔ 파이썬에서 들여쓰기는 **문법의 일부**입니다.

* 코드 블록을 구분하는 역할
* 보통 공백 4칸 사용
* 들여쓰기가 다르면 오류 발생

```python
if True:
    print("정상")
  print("에러")  # ❌ Indentation Error
```

---

## 6️⃣ 반복문 실습 예제

### 6.1 구구단 출력

```python
n = int(input())

for i in range(1, 10):
    print(f"{n} * {i} = {n * i}")
```

---

### 6.2 삼각형 출력

```python
n = int(input())

for i in range(1, n + 1):
    print("*" * i)
```

---

### 6.3 피보나치 수열 (앞의 20개)

```python
a, b = 0, 1

for _ in range(20):
    print(a, end=" ")
    a, b = b, a + b
```

---

### 6.4 숫자 맞추기 게임

```python
import random

secret = random.randint(1, 100)
count = 0

while True:
    guess = int(input("숫자 입력: "))
    count += 1

    if guess > secret:
        print("더 작은 수입니다!")
    elif guess < secret:
        print("더 큰 수입니다!")
    else:
        print(f"{count}번 만에 맞추셨습니다!")
        break
```

---

## 7️⃣ 팩토리얼 (Factorial)

### 정의

```
n! = n × (n-1) × (n-2) × ... × 1
```

### 반복문으로 구현

```python
n = int(input())
result = 1

for i in range(1, n + 1):
    result *= i

print(result)
```

---

## 8️⃣ f-string (문자열 포맷)

```python
name = "Python"
age = 10

print(f"{name} is {age} years old.")
```

---

### 📌 f-string 포맷 지정자 요약표

| 포맷        | 의미      | 예시           | 결과        |
| --------- | ------- | ------------ | --------- |
| `{x}`     | 기본 출력   | `f"{x}"`     | 10        |
| `{x:d}`   | 정수      | `f"{x:d}"`   | 10        |
| `{x:f}`   | 실수      | `f"{x:f}"`   | 10.000000 |
| `{x:.2f}` | 소수 2자리  | `f"{x:.2f}"` | 10.00     |
| `{x:,}`   | 천 단위 구분 | `f"{x:,}"`   | 1,000     |
| `{x:05d}` | 0 채우기   | `f"{x:05d}"` | 00010     |
| `{x:<5}`  | 왼쪽 정렬   | `f"{x:<5}"`  | 10        |
| `{x:^5}`  | 가운데 정렬  | `f"{x:^5}"`  | 10        |

---

## ✨ 마무리

이 저장소는 **파이썬 기초 문법, 반복문·조건문 활용, 알고리즘 사고력**을 체계적으로 정리한 학습 기록입니다.
향후 로봇 제어 및 실제 센서 연동 프로젝트로 확장할 계획입니다.

# python-basic

## 목적

생각하는 힘과 문제 해결력을 기르기 위해 Python 기본 문법을 정리하고,
각 개념을 예제와 함께 정리한 학습 기록입니다.

튜플(tuple)과 사전(dictionary)을 중심으로,
자료구조의 특징과 활용 방법을 이해하는 것을 목표로 했습니다.

---

## 튜플 (Tuple)

### 개념

* 여러 값을 하나로 묶어 저장하는 자료형
* **순서가 있으며 (ordered)**
* **한 번 생성되면 값 변경 불가 (immutable)**

### 특징

* 입력한 순서 유지
* 중복 허용
* 인덱싱 / 슬라이싱 가능
* 값 변경 불가로 안전함

### 튜플 생성 예시

```python
# 기본 튜플
t1 = (1, 2, 3)

# 괄호 없이도 가능
t2 = 4, 5, 6

# 요소가 하나일 때는 콤마 필수
t3 = (7,)   # 튜플
t4 = (7)    # 정수
```

### 튜플 사용 예시 1

```python
# 인덱싱
print(t1[0])      # 1

# 슬라이싱
print(t1[1:])     # (2, 3)

# 튜플은 불변
# t1[0] = 10  → 오류 발생
```

### 튜플 사용 예시 2

```python
tup = (1, 2, 3)
print(tup[0])     # 1

# tup[0] = 3  → TypeError 발생
```

### 튜플 사용 예시 3

```python
print(type((1)))    # int
print(type((1,)))   # tuple
print(type(()))     # tuple
```

### 튜플 사용 예시 4

```python
len(tup)            # 3
tup + (4, 5, 6)     # (1, 2, 3, 4, 5, 6)
tup[:2]             # (1, 2)
2 in tup             # True
```

---

## 튜플 언패킹 (Unpacking)

```python
x, y, z = (12.3, 28.3, 9.87)
```

### 확장 언패킹

```python
a, *b, c = (1, 2, 3, 4)
# a = 1, b = [2, 3], c = 4
```

### 변수 값 교환

```python
a, b = 10, 20
a, b = b, a
print(a, b)   # 20 10
```

---

## 두 점 사이의 거리 계산 (문제 2.2.9)

```python
import math

p1 = (x1, y1)
p2 = (x2, y2)

d = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)
```

---

## 사전 (Dictionary)

### 개념

* 데이터를 **키(key) : 값(value)** 형태로 저장
* 키를 이용해 빠르게 값에 접근 가능

```python
student = {
    "name": "John Doe",
    "age": 21,
    "cell": "010-2222-3333"
}
```

### 기본 특징

* 키는 중복 불가
* 키는 변경 불가능한 자료형만 가능
* 값은 어떤 자료형이든 가능
* Python 3.7+부터 입력 순서 유지

### 사전 접근

```python
print(student["age"])   # 21
```

---

## 해시 (Hash)

* 데이터를 고정된 길이의 값으로 변환하는 과정
* 사전은 해시 기반으로 빠른 탐색 가능

```python
invalid_dict = {[1, 2, 3]: "123"}  # 오류
valid_dict = {(1, 2, 3): "ok"}
```

---

## 사전 키 확인

```python
filled_dict = {"one": 1, "two": 2, "three": 3}
list(filled_dict.keys())
```

---

## Iterable

* 반복 가능한 객체
* for문에서 사용 가능

### 대표 예시

* 문자열: "hello"
* 리스트: [1, 2, 3]
* 튜플: (1, 2, 3)

---

## ✨ 마무리

이번 정리를 통해 Python의 기본 자료구조인 튜플과 사전을 이해하고,
불변성과 해시 구조의 개념을 익힐 수 있었습니다.

앞으로는 실제 문제 풀이와 프로젝트에 적극 활용할 예정입니다.



## 🧠 Algorithm Basic

### 📌 목적

간단한 알고리즘 문제 풀이를 통해 **문제를 분석하고 해결하는 사고력**을 기르는 것을 목표로 합니다.
특히 이 문서에서는 **연산자(산술 연산문)** 를 중심으로 문제를 구성하여,
파이썬 기본 문법이 실제 계산 로직에 어떻게 사용되는지를 이해하는 데 중점을 둡니다.

각 문제는 풀이 과정을 단계적으로 정리하고,
코드에는 주석을 통해 사고 과정을 설명했습니다.

---

### 문제 1. 두 개의 정수를 입력받아 사칙연산 결과를 출력하시오

#### 풀이 과정

1. 두 개의 정수를 입력받는다.
2. 덧셈, 뺄셈, 곱셈, 나눗셈을 각각 계산한다.
3. 계산 결과를 순서대로 출력한다.

```python
a, b = map(int, input().split())

print(a + b)   # 덧셈
print(a - b)   # 뺄셈
print(a * b)   # 곱셈
print(a // b)  # 나눗셈(몫)
```

#### 학습 포인트

* 산술 연산자 (`+`, `-`, `*`, `//`) 이해
* 다중 입력 처리 (`map`, `split`)
* 연산 결과 출력 흐름 파악

---

### 문제 2. 세 개의 정수의 평균을 구하시오

#### 풀이 과정

1. 세 개의 정수를 입력받는다.
2. 세 수의 합을 계산한다.
3. 합을 3으로 나누어 평균을 구한다.

```python
a, b, c = map(int, input().split())

average = (a + b + c) / 3
print(average)
```

#### 학습 포인트

* 덧셈과 나눗셈 연산 결합
* 실수 결과 처리
* 계산식 변수 저장

---

### 문제 3. 정수 하나를 입력받아 제곱 값을 출력하시오

#### 풀이 과정

1. 정수를 하나 입력받는다.
2. 자기 자신과 곱하여 제곱 값을 계산한다.
3. 결과를 출력한다.

```python
n = int(input())

print(n * n)
```

#### 학습 포인트

* 곱셈 연산 활용
* 간단한 수학 연산의 알고리즘화

---

## 🤖 Mini Projects

### 📁 robot-action-decider

```
mini-projects
└─ robot-action-decider
   ├─ action_decider.py
   └─ README.md
```

---

### 로봇 행동 결정 프로그램

#### 프로젝트 개요

로봇이 **장애물과의 거리**와 **배터리 잔량**을 입력받아,
현재 상황에 따라 적절한 행동을 결정하도록 만든 간단한 제어 프로그램입니다.

---

#### 구현 코드

```python
distance = int(input("장애물과의 거리(cm): "))
battery = int(input("배터리 잔량(%): "))

if distance < 20:
    print("정지")
elif battery < 30:
    print("충전 필요")
else:
    print("전진")
```

---

#### 사용 기술

* Python

---

#### 구현 기능

* 거리 값 입력
* 배터리 상태 확인
* 조건에 따른 로봇 행동 판단

---

#### 배운 점

* 연산 결과를 조건 판단에 활용하는 방법을 이해함
* 여러 조건을 고려한 로직 설계 경험
* 로봇 제어의 기본적인 판단 구조 습득

---

#### 향후 개선

* 실제 거리 센서 및 배터리 센서 값과 연동
* Arduino 기반 로봇 제어 프로그램으로 확장

---

## ✨ 마무리

이 저장소는 **연산문 중심의 파이썬 기초 문법**,
**알고리즘 사고력**, **로봇 제어 논리**를 함께 성장시킨 학습 기록입니다.

앞으로 조건문·반복문과 결합된 더 복잡한 계산 문제와
실제 하드웨어 제어 프로젝트로 확장할 계획입니다.

# ✅ Chapter 3. 기본 문법

## 3. 제어 흐름 (Control Flow and Iterables)

# 🧠 3.7. 예외(Exception) 처리

프로그램을 개발하다 보면 문법적으로는 완벽하지만,
실행 중 **예상치 못한 상황**(잘못된 입력, 네트워크 오류, 파일 부재 등)으로 인해
프로그램이 중단되는 경우가 발생합니다.

이러한 상황을 **예외(Exception)** 라고 하며,
이를 안전하게 처리하는 작업을 **예외 처리(Exception Handling)** 라고 합니다.

---

## ✅ 1/7 예외 처리 기본 개념

예를 들어 로그인 과정에서 서버 응답이 없다면 다음과 같은 고민이 필요합니다.

* 얼마나 기다려야 하는가?
* 사용자에게 무엇을 안내해야 하는가?
* 프로그램을 종료할 것인가, 다시 시도할 것인가?

이처럼 **비정상 상황에 대비하는 로직**이 바로 예외 처리입니다.

---

## 3.7.1 예외(Exception)란?

예외란 프로그램 실행 중 정상적인 흐름을 방해하는 사건입니다.

* 예외 처리를 하지 않으면 → 프로그램 즉시 종료 (Crash)
* 예외 처리를 하면 → 오류를 우아하게 처리하거나 복구 가능

---

## 3.7.2 Python 예외 처리 기본 문법

```python
try:
    # 실행하고 싶은 코드 (에러 가능 구간)
except 예외종류:
    # 예외 발생 시 실행 코드
else:
    # 예외가 발생하지 않았을 때 실행 (선택)
finally:
    # 예외 발생 여부와 관계없이 항상 실행 (선택)
```

---

## ✅ 2/7 예외 처리 예제 + raise

```python
try:
    raise IndexError("this is an index error")
except IndexError as e:
    pass
except (TypeError, NameError):
    pass
else:
    print("All good!")
finally:
    print("We can clean up resources here")
```

### 🔹 raise

* 의도적으로 예외를 발생시킬 때 사용

### 🔹 as e 의미

* 발생한 예외 객체를 변수(e)에 저장
* e 대신 err, error 등 다른 이름 사용 가능

---

## ✅ 3/7 IndexError 예시 + 예외 카테고리

```python
lockers = ["노트북", "책", "우산"]

try:
    item = lockers[5]
except IndexError as e:
    print("⚠️ 문제가 발생했습니다!")
    print(f"에러 메시지 내용: {e}")
```

출력 결과:

```
⚠️ 문제가 발생했습니다!
에러 메시지 내용: list index out of range
```

> `as e`를 사용하지 않으면 상세 에러 메시지를 확인할 수 없음

---

### 📌 주요 예외 카테고리

| 카테고리 | 예외 이름             | 발생 상황          |
| ---- | ----------------- | -------------- |
| 값/타입 | TypeError         | 잘못된 타입 연산      |
| 값/타입 | ValueError        | 타입은 맞으나 값이 부적절 |
| 참조   | NameError         | 변수 이름 없음       |
| 참조   | AttributeError    | 객체에 없는 속성 호출   |
| 인덱스  | IndexError        | 범위 초과 접근       |
| 인덱스  | KeyError          | 딕셔너리 키 없음      |
| 입출력  | FileNotFoundError | 파일 없음          |
| 입출력  | PermissionError   | 파일 권한 없음       |

---

## ✅ 4/7 파일 처리 기본 방식 vs with

### 일반적인 파일 처리 방식

```python
f = open("data.txt")
try:
    content = f.read()
finally:
    f.close()
```

⚠️ close()를 깜빡하기 쉬움

---

### with 사용 (권장)

```python
with open("myfile.txt") as f:
    for line in f:
        print(line)
```

#### 특징

* 블록 종료 시 자동 close()
* 오류 발생해도 안전하게 종료

---

## ✅ 5/7 추가 예외 + 0으로 나누기

### 주요 예외 추가

| 카테고리 | 예외 이름               | 발생 상황     |
| ---- | ------------------- | --------- |
| 수학   | ZeroDivisionError   | 0으로 나누기   |
| 수학   | OverflowError       | 너무 큰 수    |
| 모듈   | ImportError         | import 실패 |
| 모듈   | ModuleNotFoundError | 모듈 없음     |

### Practice: 0으로 나누기 처리

```python
try:
    m, n = map(int, input().split())
    print(f"{m} / {n} = {m / n}")
except ZeroDivisionError:
    print("0으로 나눌 수 없습니다.")
```

---

## 3.7.3 with 문장과 자원 관리

자원(Resource)이란 운영체제가 관리하는 데이터입니다.

* 파일
* 데이터베이스
* 네트워크

`with` 문은 자원을 **자동으로 정리(cleanup)** 해줍니다.

---

## ✅ 6/7 JSON 타입과 파일 읽기

### JSON ↔ Python 타입

| JSON         | Python       |
| ------------ | ------------ |
| string       | str          |
| number       | int / float  |
| true / false | True / False |
| null         | None         |

```python
with open("myfile2.txt", "r") as file:
    contents = json.load(file)
    print(contents)
```

---

## ✅ 7/7 with로 파일 쓰기 + JSON

```python
contents = {"aa": 12, "bb": 21}

with open("myfile1.txt", "w") as file:
    file.write(str(contents))

import json
with open("myfile2.txt", "w") as file:
    file.write(json.dumps(contents))
```

### 💡 JSON이란?

JSON(JavaScript Object Notation)은
사람과 컴퓨터 모두 읽기 쉬운 데이터 표현 형식입니다.

```json
{
  "name": "Sungyong",
  "age": 15,
  "likes": ["game", "coding"]
}
```

### JSON → Python 변환 규칙

| JSON      | Python |
| --------- | ------ |
| object {} | dict   |
| array []  | list   |

---

## ✨ 마무리

이 문서는 **파이썬 예외 처리의 핵심 개념부터 파일·JSON 처리까지**를 정리한 학습 기록입니다.

안정적인 프로그램을 만들기 위한 기반 문법으로,
향후 로봇 제어, 서버 통신, 데이터 처리 프로젝트로 확장할 수 있습니다.

