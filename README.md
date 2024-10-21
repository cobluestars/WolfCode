# 🐺WolfCode Language Specification🐺

## 1. Introduction:
   - WolfCode is a playful, wolf-themed programming language designed to teach basic programming concepts. It uses wolf pack terminology to represent various programming constructs.

## 2. Data Types:
   - Bone: Represents integer values
     Example: Howl my_bone as Bone
   - Meat: Represents floating-point values
     Example: Howl my_meat as Meat
   - Biscuit: Represents boolean values (crunchy = true, soft = false)
     Example: Howl my_biscuit as Biscuit

## 3. Variables and Assignment:
   - Declaration: "Howl [name] as [type]"
     Example: Howl age as Bone
   - Assignment: "Mark [name] with [value]"
     Example: Mark age with 5

## 4. Basic Operators:
   - Addition: "Fetch [bone1] and [bone2]"
     Example: Fetch age and 3
   - Subtraction: "Chase [bone1] from [bone2]"
     Example: Chase 2 from age
   - Multiplication: "Bury [bone1] [bone2] times"
     Example: Bury age 2 times
   - Division: "Share [bone1] among [bone2] pack members"
     Example: Share age among 2 pack members
   - Comparison: "Sniff [bone1] and [bone2]" (returns Biscuit)
     Example: Sniff age and 10

## 5. Control Structures:
   - If statement:
   ```WolfCode
     "If [condition] then
        [action]
     else
        [other action]
     Pack decides"
  ```
   - While loop:
  ```WolfCode
     "While [condition] do
        [actions]
     Pack rests"
   - For loop:
     "For each [item] in [collection] do
        [actions]
     Pack moves on"
  ```

## 6. Input/Output:
   - Input: "Listen for [variable]"
     Example: Listen for age
   - Output: "Howl [message]"
     Example: Howl "Your age is: " age

## 7. Memory Model:
   - The den is represented as an infinite series of caves
   - Each cave stores one data item (Bone, Meat, or Biscuit)
   - Navigate using: "Dig [direction] to [cave_name]"
     Example: Dig north to age_cave

## 8. Jump Commands:
   - Unconditional jump: "Run to [label]"
     Example: Run to start_loop
   - Conditional jump: "If [condition] then run to [label]"
     Example: If Sniff age and 18 then run to adult_section

## 9. Function Definition:
   - Define function:
     "Teach pack [function_name]
        [function body]
     Pack learned [function_name]"
   - Call function: "Do [function_name]"

## 10. Comments:
    - Single line: "// [comment]"
    - Multi-line: "/* [comment] */"

## 11. Program Structure:
    - Start: "Pack gathering"
    - End: "Pack dispersing"


## Example Programs:

### 1. Basic Arithmetic:

```WolfCode
Pack gathering

Howl "Let's do some wolf math!"

Howl num1 as Bone
Howl num2 as Bone

Listen for num1
Listen for num2

Howl sum as Bone
Mark sum with Fetch num1 and num2
Howl "Sum: " sum

Howl diff as Bone
Mark diff with Chase num2 from num1
Howl "Difference: " diff

Howl product as Bone
Mark product with Bury num1 num2 times
Howl "Product: " product

Howl quotient as Meat
Mark quotient with Share num1 among num2 pack members
Howl "Quotient: " quotient

Pack dispersing
```

### 2. Control Structures:

```WolfCode
Pack gathering

Howl "Counting bones!"

Howl count as Bone
Mark count with 1

While Sniff count and 11 do
    Howl "Bone count: " count
    Mark count with Fetch count and 1
Pack rests

Howl "Even or Odd?"

For each num in count do
    If Share num among 2 pack members then
        Howl num " is even"
    else
        Howl num " is odd"
    Pack decides
Pack moves on

Pack dispersing
```

### 3. Function Example:

```WolfCode
Pack gathering

Teach pack calculate_dog_years
    Listen for human_years
    Howl dog_years as Bone
    Mark dog_years with Bury human_years 7 times
    Howl "In dog years, that's: " dog_years
Pack learned calculate_dog_years

Howl "Enter your age in human years:"
Do calculate_dog_years

Pack dispersing
```

### 4. Hello World Example:

```WolfCode
Pack gathering

// Declare variables for each character
Howl h as Bone
Howl e as Bone
Howl l as Bone
Howl o as Bone
Howl space as Bone
Howl w as Bone
Howl r as Bone
Howl d as Bone
Howl exclamation as Bone

// Assign ASCII values
Mark h with 72  // ASCII for 'H'
Mark e with 101 // ASCII for 'e'
Mark l with 108 // ASCII for 'l'
Mark o with 111 // ASCII for 'o'
Mark space with 32 // ASCII for space
Mark w with 87  // ASCII for 'W'
Mark r with 114 // ASCII for 'r'
Mark d with 100 // ASCII for 'd'
Mark exclamation with 33 // ASCII for '!'

// Combine characters to form the message
Howl message as Bone
Mark message with Fetch h and e
Mark message with Fetch message and l
Mark message with Fetch message and l
Mark message with Fetch message and o
Mark message with Fetch message and space
Mark message with Fetch message and w
Mark message with Fetch message and o
Mark message with Fetch message and r
Mark message with Fetch message and l
Mark message with Fetch message and d
Mark message with Fetch message and exclamation

// Output the message
Howl message

Pack dispersing
```

# WolfCode 언어 설명

## 1. 소개

- WolfCode는 늑대 무리의 용어를 사용하여 프로그래밍 구조를 나타내며, 기본적인 프로그래밍 개념을 가르치는 재미있는 언어입니다.
- 만든 이: cobaltbluestars(Renard), Raika the Wolfdog

## 2. 데이터 타입

- Bone: 정수형 값
예: Howl my_bone as Bone

- Meat: 부동 소수점 값
예: Howl my_meat as Meat

- Biscuit: 불리언 값 (crunchy = 참, soft = 거짓)
예: Howl my_biscuit as Biscuit

## 3. 변수 선언 및 할당

- 변수 선언: Howl [이름] as [타입]
예: Howl age as Bone

- 값 할당: Mark [이름] with [값]
예: Mark age with 5

## 4. 기본 연산자

- 덧셈: Fetch [bone1] and [bone2]
예: Fetch age and 3

- 뺄셈: Chase [bone1] from [bone2]
예: Chase 2 from age

- 곱셈: Bury [bone1] [bone2] times
예: Bury age 2 times

- 나눗셈: Share [bone1] among [bone2] pack members
예: Share age among 2 pack members

- 비교: Sniff [bone1] and [bone2] (Biscuit을 반환)
예: Sniff age and 10

## 5. 제어 구조

- If 조건문:

```WolfCode
If [조건] then
  [행동]

else
  [다른 행동]

Pack decides
```

-While 반복문:

```WolfCode
While [조건] do
  [행동]

Pack rests
```

- For 반복문:

```WolfCode
For each [항목] in [컬렉션] do
  [행동]

Pack moves on
```

## 6. 입출력:

- 입력 받기: Listen for [변수]
예: Listen for age

- 출력하기: Howl [메시지]
예: Howl "Your age is: " age

## 7. 메모리 모델

- Den은 무한한 "caves"로 표현됨
각 cave는 하나의 데이터 항목(Bone, Meat, 또는 Biscuit)을 저장

- 탐색: Dig [방향] to [cave_name]
예: Dig north to age_cave

## 8. 점프 명령어

- 무조건 점프: Run to [label]
예: Run to start_loop

- 조건부 점프: If [조건] then run to [label]
예: If Sniff age and 18 then run to adult_section

## 9. 함수 정의

- 함수 정의:

```WolfCode
Teach pack [함수명]
  [함수 내용]
Pack learned [함수명]
```

- 함수 호출: Do [함수명]

## 10. 주석

- 단일 줄 주석: // [주석 내용]
- 여러 줄 주석: /* [주석 내용] */

## 11. 프로그램 구조

시작: Pack gathering
끝: Pack dispersing


## WolfCode Quick Sort

```WolfCode

Pack gathering

// 늑대 무리 선언
Howl wolf_pack as Den
Mark wolf_pack with [{"name": "leo", "age": 5}, {"name": "jax", "age": 3}, {"name": "matt", "age": 2}, {"name": "renard", "age": 1}]

// 퀵 정렬 함수 정의
Teach pack quick_sort
    Listen for wolves

    // 리스트가 1 이하인 경우 그대로 반환
    If Sniff length of wolves and 1 then
        Howl sorted_wolves as Den
        Mark sorted_wolves with wolves
        Pack learned quick_sort
    Pack decides

    // 피벗 선택: 첫 번째 늑대를 피벗으로 사용
    Howl pivot as Den
    Mark pivot with wolves[0]

    // 피벗을 기준으로 나누기
    Howl less as Den
    Howl greater as Den
    For each wolf in wolves do
        If Sniff wolf.age and pivot.age then
            Howl "나이 적음: " wolf.name
            Mark less with Fetch less and wolf
        else
            Howl "나이 많음 또는 같음: " wolf.name
            Mark greater with Fetch greater and wolf
        Pack decides
    Pack moves on

    // 재귀적으로 정렬 및 합치기
    Howl sorted_less as Den
    Howl sorted_greater as Den
    Mark sorted_less with Do quick_sort(less)
    Mark sorted_greater with Do quick_sort(greater)

    Howl sorted_wolves as Den
    Mark sorted_wolves with Fetch sorted_less and [pivot] and sorted_greater

    Howl "정렬된 늑대 무리: " sorted_wolves
Pack learned quick_sort

// 정렬 실행
Howl sorted_pack as Den
Mark sorted_pack with Do quick_sort(wolf_pack)
Howl "최종 정렬 결과: " sorted_pack

Pack dispersing

```
