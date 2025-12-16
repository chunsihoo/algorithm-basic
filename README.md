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
