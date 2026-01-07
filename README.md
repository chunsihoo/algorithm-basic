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


