- 모던자바스크립트 튜토리얼
- MDN
- VS Code

폴더 경로에  한글 x, 띄어쓰기 x

자바스크립트는 node나 브라우저가 있어야 실행할 수 있음

오타 주의

잘못된 순서도, 로직 주의

괄호, 대소문자, 따옴표

오타 찾아가면서 에러를 고치면서 실력이 는다.

```jsx
console.log('Hello World');
```

영어 공부 - 토익 → 시간 아끼고 실력 상승

( ) parentheses

{ } braces

[ ] brackets

**REPL Read-Eval-print Loop**

프로그래밍 사고력

→ 순서도 그려서 실력 기르기

코딩테스트

→ 효율적인 순서도 그리는 방법

## 기본 문법 배우기

- 명령이 끝나면 세미콜론으로 구분
- Unexpected identifier : 뭘 넣어야 되는데 안 넣었을 때 나는 에러
- // : 주석
- /*     */   : 주석
- 코드 사이도 가능
- 긴가민가할때, 쓰이지 않는 코드도 주석처리
- 들여쓰기

## 자료형

값 value :  프로그램이 조작할 수 있는 데이터

자료형 : data type : 값의 종류

string : 문자열 | 따옴표나 벡틱으로 감싸줘야된다.

- 벡틱은 줄바꿈 가능

boolean

typeof '문자열'

→ string

typeof `문자열`

→ string

typeof ""

→ string

'' == '     '

→ false

따옴표를 문자열 안에 넣고 싶을때

벡틱이나 큰따옴표로 감싸줌

\'

역슬래시를 문자열안에 넣고싶을때 \\

문자열에선 문자열 연산이 된다.

띄어쓰기도 문자열 안에 넣어주기

5e4 = 50000

5e-4 = 0.0005

0b111 = 7

0111 = 73

0x1a1 = 417

typeof 0x1a1 = number

typeof NaN = "number"

typeof '124' = string

'124' + 5 = "1245"

숫자로 형변환

perseInt('124')

Number('124')+5 → 129

'3.14' → 문자열

parseInt('3.14') = 3

parseFloat('3.14') = 3.14

parseInt('3월') = 3

Number('3월') = NaN

'1231231'.substr(0,2) = "A"

'1231231'.substring(0,2) = "12"

prompt() : 문자열 입력받음

ParsInt(111,2)

** 제곱

typeof - Infinity

"number"

Infinity - Infinity

NaN

문자열 - 숫자열

Nan

: 문자열이 숫자열로 바뀐다.
