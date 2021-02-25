# 월드리더 스터디 1회(2021.02.12)

## 1회차 목표

- Learning & Sharing
  - 팀명 - 
  - 학습목표
    -  공모전 참여
    -  공동 목표 : 다뤄보지 않았던 분야인 통계와 파이썬을 공부함으로써 결과적으로는 국토도시 데이터 분석과제 등과 같이 통계와 파이썬을 이용하는 공모전에서 수상하는 쾌거를 이루고 싶다.
    -  김홍순 : 새로운 분야에 대한 도전
    -  석현수 : AI 공부
    -  오혜리 : 통계공부
    -  최예훈 : 저는 원래 약간 취미로 파이썬기초만 공부중이었는데 제가 또 산업공학과 복수전공을 하고 있어서 통계 공부도 하다보니까? 두개 연관 지어서 웹 크롤링이나 통계 조사를 할 수 있다고 들어서
  - 활동일정
    - 매주 활동내용 : 5회분 중 1회분씩 맡아서 개념 강의(1명) & 각 교재들보면 연습문제가 있는데, 이거 각각 공부해서 풀어와서 비교, 이해 안됐던 부분 토론
    - 통계에 대해서 기초를 쌓고 파이썬 이용해서 빅데이터를 활용하여 실생활에 적용해보기.
    - 2/15~3/21 (5주)
      - 파이썬 기본기 교재 (점프 투 파이썬) & 기초통계학 교재 공부(https://www.youtube.com/watch?v=saCv9cBvT7U&t=264s) (제대로 배우는 기초통계학) (8주)
    - [3/22일 위인전 Learning & Sharing 일정 시작]
      3/22~4/11 (3주)
      - 초보자를 위한 파이썬 200제(http://www.yes24.com/Product/Goods/36836557)
    - 4/12~5/2 (3주)
      - 파이썬으로 배우는 통계학 교과서 (http://www.yes24.com/Product/Goods/83532333)
    - SQL(2주)
    - 공모전 준비(3주)
  - 팀원 정보 및 지원 동기
    - 개별로 간단한 소개 및 지원 동기를 작성
  - 모임 소개
    - 모임 구성 계기 및 모임에 대한 소개 작성
  - 세부활동내용 및 전략
    - 활동기간 : 3.22(월)~6.4(금), 11주(중간고사 기간이 있어 1주 추가)
    - 활동을 통해 달성하고자 하는 최종 목표를 세분화한 후 각각의 회차에 따른 활동목표, 활동내용 작성
    - 합계시간이 30시간 이상 되지 않으면 제출 불가
    - (2장-민호/3,4장/5장/6장/7장)(1,2,3,4장-민호/5,6,7장/8,9장/10장/11장)
  - 예산
  - 모임규칙
    - 금요일 오후1시~4시/5시
    - 팀 구성원과 충분히 합의하여 정하기 
    - 모임에 나오지 않거나, 성실하게 활동하지 않을 경우 자체적으로 어떻게 관리할 것인지 패널티 등을 구체적으로 작성
  - 첨부파일 
    - 참여할 공모전(https://www.linkareer.com/activity/55935)/대회 포스터, 별도의 계획서, 활동하고자 하는 내용이 담긴 자료 첨부 가능
- mark down 문법 익히기
  - https://www.youtube.com/watch?v=kMEb_BzyUqk
- githurb 사용법 익히기
  - https://www.youtube.com/watch?v=tC8Xj_Bf8Fw


# 스터디 2회차

## 파이썬

### 파이썬 기본 문법

#### 자료형

숫자형(정수, 실수, 8진수, 16진수)

+ 정수형 
  + 양의 정수, 음의정수, 0
+ 실수형
  + -1.2, 5.7
+ 8진법 16진법
  + 문자 활용





#### 연산자

+ 사칙연산 +,-,*,/
+ x의 y제곱을 나타내는 **
+ 나눗셈 후 
  + 나머지 반환 %
  + 몫을 반환 //



#### 문자열 자료형

문자열이란 문자, 단어로 구성된 문자들의 집합

3가지 방법이 있다

1. 큰따옴표(" ")

2. 작은따옴표('')

3. 큰따옴표 3개 연속해서 둘러싸기

   문자열에 큰따옴표를 넣고 싶을때

4. 작은따옴표 3개 연속해서 둘러싸기

   문자열에 작은따옴표를 넣고 싶을때



백슬래시를 이용하여 작은따옴표와 큰따옴표 문자열 포함 가능



#### 이스케이프 코드

+ 줄을 바꿀 때 방법

  1. \n 사용

  2. 작은따옴표 3개 또는 큰따옴표 3개 사용

     multiline="""

     Life is too short

     youu need python

     """

     print(multiline)

     Life is too short 

     you need python



| 코드 | 설명                                              |
| ---- | ------------------------------------------------- |
| \t   | 문자열 사이에 줄 간격                             |
| \\\  | 문자열 사이에\를 그대로 표현할때                  |
| \\'  | 작은 따옴표 그대로 표현                           |
| \\"" | 큰따옴표 그대로 표현                              |
| \\r  | 캐리지 리턴(줄바꿈 문자, 커서를 가장 앞으로 이동) |
| \\f  | 폼 피드(줄바꿈 문자 커서를 다음줄로 이동)         |
| \\a  | 벨 소리(출력할때 삐 소리)                         |
| \\b  | 백스페이스                                        |
| \000 | 널 문자                                           |

#### 문자열 연산하기

문자열 더해서 연결

```
head = "Python"
tail = "is fun!"
head + tail
-> 'Python is fun!'
```

문자열 곱하기

```
a = "python"
a * 2
-> "Pythonpyhon"
```

```
# multistring.py

print{"="*50)
print("My Program")
print("=" * 50)
```

```
a = "Life is too short"
len(a)
-> 17
```

#### 문자열 인덱싱과 슬라이싱

인덱싱(Indexing) : '가리킨다' / 슬라이싱(Slicing) : '잘라낸다'

문자열 인덱싱

```
a= "Life is too short, You need Python"
a[3]
-> 'e'
```

활용

a[0] = L, a[12] = s, a[-1] = n, a[-0] = L

-1부터는 뒤에서부터 읽는 용도로 사용됨.

문자열 슬라이싱

```
a = "Life is too short, You need Python"
b = a[0] + a[1] + a[2] + a[3]
b
-> 'Life'

a[0:4]
-> 'Life'

a[0:3]
-> 'Lif'
```

슬라이싱은 다음과 같이 a[시작번호 : 끝번호]를 지정하는 방법으로 문자를 원하는 만큼 잘라낸다.

```
a = "Life is too short, You need Python"

a[0:5] # a[0:4]와 유사한 모양을 가지지만 공백 문자 역시 L,i,f,e 같은 문자와 동일하게 취급 되므로 a[0:4]와 a[0:5]는 완전히 다른 문자열이다.
-> 'Life '

a[0:2]
-> 'Li'

# 슬라이싱할 때 항상 시작 번호가 0일 필요는 없다.
a[5:7]
-> 'is'

a[12:17]
-> 'short'

# a[:] 내부에 숫자를 입력하지 않거나 음수 값을 넣었을 때도 작동을 하며, 어떤 식으로 나타나는지 위의 결과를 보고 확인할 수 있다.
a[19:] 
-> 'You need Python'

a[:17]
-> 'Life is too short'

a[:]
-> 'Life is too short, You need Python'

# 슬라이싱에서도 인덱싱과 마찬가지로 마이너스(-) 기호를 사용할 수 있다.
a[19:-7]
-> 'You need'
```

- 슬라이싱으로 문자열 나누기

  ```
  a = "20010331Rainy"
  date = a[:8]
  weather = a[8:]
  date
  '20010331'
  weather
  'Rainy'
  ```

  이는 자주 사용되는 슬라이싱 기법 중 하나이다.

  a[:8]은 a[8]이 포함되지 않고 a[:8]은 a[8]이 포함되기 떄문에 다음과 같은 방법으로 날짜와 날씨를 나눠서 표현할 수 있다.

  - 추가 문자열 수정

    ```
    a = "pithon"
    # 아래와 같이 행할 경우 오류가 발생한다. 문자열의 요솟값은 바꿀 수 없는 값이기 때문이다.
    a[1]
    -> 'i'
    a[1] = 'y'
    
    # 따라서 아래와 같은 방법을 사용한다.
    a[:1]
    -> 'P'
    a[2:]
    ->'thon'
    b = a[:1]+'y'+a[2:]
    -> 'Python'
    ```

#### 문자열 포매팅

문자열 안의 특정한 값만 바꿔야 할 경우가 있을 때 사용.

- 문자열 포매팅 예제

  1. 숫자 바로 대입

     ```
     # 숫자를 넣고 싶은 자리에 %d를 넣어주고 삽입할 숫자 3은 가장 뒤에 적용. 여기서 %d는 포맷코드라고 불린다.
     "I eat %d apples" %3
     -> 'I eat 3 apples'
     ```

  2. 문자열 바로 대입

     ```
     # 문자열을 넣고 싶은 자리에 %s를 넣어준다. (숫자형 포맷코드 = %d, 문자형 포맷코드 = %s)
     "I eat %s apples" %"five"
     -> 'I eat five apples'
     ```

  3. 숫자 값을 나타내는 변수로 대입

     ```
     number = 3
     "I eat %d apples" % number
     -> 'I eat 3 apples'
     ```

  4. 2개 이상의 값 넣기

     ```
     # 2개 이상의 값을 넣을땐 마지막 % 다음 괄호 안에 콤마로 구분하여 각각의 값을 넣는다.
     number = 10
     day = "three"
     "I ate %d apples. so I was sick for %s days." % (number, day)
     -> 'I ate 10 apples. so I was sick for three days'
     ```

- 문자열 포맷 코드

  | 코드 | 설명                     |
  | ---- | ------------------------ |
  | %s   | 문자열 (string)          |
  | %c   | 문자 1개 (Character)     |
  | %d   | 정수 (Integer)           |
  | %f   | 부동소수(Floating-point) |
  | %o   | 8진수                    |
  | %x   | 16진수                   |
  | %%   | Literal%(문자'%' 자체)   |

  ```
  # %d 대신 %s를 사용해도 가능하다.
  "I have %s apples" % 3
  -> 'I have 3 apples'
  # %f 대신 %s를 사용해도 가능하다.
  "rate is %s" % 3.234
  -> 'rate is 3.234'
  # %s는 % 뒤에 있는 값을 자동으로 문자열로 바꾸기 때문.
  ```

  ```
  # %%활용 예시
  
  "Error is %d%." % 98
  # 위와 같이 코드를 작성할 경우 "Error is 98%"가 나타나지 않고 오류 메세지가 뜨게 된다.
  # %d와 %가 같은 문자열 안에 존재하는 경우 %를 나타내려면 %%로 써야한다.
  
  "Error is %d%%." % 98
  -> 'Error is 98%'
  
  # "Error is %s." % 98% 와 같이 작성을 해도 오류가 뜨는 것을 확인하였다. 문자열로 바뀌는 포맷코드인 %s 마저도 %와는 같이 쓸 수 없다.
  ```

- 포맷코드와 숫자 함께 사용하기.

  1. 정렬과 공백

  ```
  # 오른쪽 정렬
  "%10s" # 전체 길이가 10개인 문자열 공간에서 대입되는 값을 오른쪽 정렬, 그 앞의 나머지는 공백으로 만드는 코드
  -> '        hi' # 공백 8개가 앞서 들어가고 hi가 작성된다.
  
  # 왼쪽 정렬
  "%-10sjane" % "hi"
  -> 'hi        jane'
  ```

  1. 소수점 표현하기

  ```
  "%0.4f" %3.42134234
  -> '3.4213'
  # 소수점 네번째 자리까지만 나타내고 싶은 경우에는 위와 같이 사용.
  
  
  "%10.4f" %3.42134234
  -> '    3.4213'
  #전체 길이 10개의 문자열 공간에서 오른쪽 정렬. #공백은 앞쪽에 4개 들어간다.
  ```

- format 함수를 사용한 포매팅

  문자열 포매팅 예제 활용

  ```
  # 숫자 바로 대입하기
  # format 함수 사용전. format 코드 사용.
  "I eat %d apples" %3
  -> 'I eat 3 apples'
  
  # format 함수 사용.
  "I eat {0} apples".format(3)
  -> 'I eat 3 apples'
  
  
  # 문자열 바로 대입하기
  # format 함수 사용전. format 코드 사용.
  "I eat %s apples" %"five"
  -> 'I eat five apples'
  
  # format 함수 사용.
  "I eat {0} apples ".format ("five")
  -> 'I eat five apples'
  
  
  #숫자 값을 가진 변수로 대입하기
  # format 함수 사용전. format 코드 사용.
  number = 3
  "I eat %d apples" % number
  -> 'I eat 3 apples'
  
  # format 함수 사용.
  number = 3
  "I eat {0} apples ".format (number)
  -> 'I eat 3 apples'
  
  
  #2개 이상의 값 넣기
  # format 함수 사용전. format 코드 사용.
  number = 10
  day = "three"
  "I ate %d apples. so I was sick for %s days." % (number, day)
  -> 'I ate 10 apples. so I was sick for three days'
  
  # format 함수 사용.
  number = 10
  day = "three"
  "I ate {0} apples, so I was sick for {1} days.".format(number, day)
  -> 'I ate 10 apples, so I was sick for three days.'
  
  # format 함수 사용. 변수 이름 넣기
  "I ate {number} apples, so I was sick for {day} days.".format(number=10, day=3)
  'I ate 10 apples, so I was sick for 3 days-'
  # 이 경우 format 함수에는 반드시 name = Value 형태의 입력값이 있어야한다.
  
  #인덱스와 이름 혼용해서 넣기
  "I ate {0} apples, so I was sick for {day} days.".format(10, day=3)
  'I ate 10 apples- so I was sick for 3 days.'
  ```

  포맷 함수에서의 정렬

  ```
  #왼쪽 정렬 
  "{0:<10}".format("hi") #{0:<10}에서 ':<10'이 %10s에서 '10'의 역할을 한다.
  -> 'hi        '
  
  
  #오른쪽 정렬
  "{0:>10}".format("hi")
  -> '        hi'
  
  
  #가운데 정렬
  "{0:^10}".format("hi")
  -> '    hi    '
  
  
  #공백 채우기 및 정렬 응용
  "{0:=^10}".format("hi")
  -> '====hi===='
  
  "{0:!<10}".format("hi")
  -> 'hi!!!!!!!!'
  ```

  소수점 표현하기

  ```
  # format 함수 사용전. format 코드 사용.
  "%0.4f" %3.42134234
  -> '3.4213'
  
  # format 함수 사용.
  y = 3.42134234
  "{0:0.4f}".format(y)
  -> '3.4213'
  
  
  # format 함수 사용전. format 코드 사용.
  "%10.4f" %3.42134234
  -> '    3.4213'
  
  # format 함수 사용.
  y = 3.42134234
  "{0:10.4f}".format(y)
  '    3.4213'
  ```

  format 함수를 사용하는 중 { }와 같은 중괄호(brace) 문자를 포매팅 문자가 아닌 문자 그대로 사용하고 싶은 경우에는 아래와 같이 사용한다.

  ```
  "{{ and }}".format()
  -> '{ and }'
  
  "{{cho minho}}".format()
  ->'{cho minho}'
  ```

  f문자열 포매팅

  문자열 앞에 f 접두사를 붙이면 f 문자열 포매팅 기능 사용가능.

  ```
  name = '홍길동'
  age = 30
  f'나의 이름은 {name}입니다. 나이는 {age}입니다.' #f후에 띄어쓰기를 하지 않아야한다!
  -> '나의 이름은 홍길동입니다. 나이는 30입니다.' 
  
  age = 30
  f'나는 내년이면 {age+1}살이 된다.'
  '나는 내년이면 31살이 된다.'
  
  
  #딕셔너리 활용(in f 문자열 포매팅)
  d = {'name':'홍길동', 'age': 30}
  f'나의 이름은 {d["name"]}입니다. 나이는 {d["age"]}입니다'
  ->'나의 이름은 홍길동입니다. 나이는 30입니다'
  
  
  #정렬 방법(in f 문자열 포매팅)
  f'{"hi":<10}' #왼쪽정렬
  -> 'hi        '
  
  f'{"hi":>10}' #오른쪽 정렬
  -> '        hi'
  
  f'{"hi":^10}' #가운데 정렬
  -> '    hi    '
  
  f'{"hi":=^10}'#가운데 정렬하고 =문자로 공백 채우기
  -> '====hi===='
  
  f'{"hi":!<10}' #왼쪽 정렬하고 !문자로 공백 채우기
  -> 'hi!!!!!!!!'
  
  
  #소수점 표현
  y=3.42134234
  f'{y:0.4f}' #소수점 4자리까지만 표현
  -> '3.4213'
  
  f'{y:10.4f}' #소수점 4자리까지 표현하고 총 자릿수를 10으로 맞춤
  -> '    3.4213'
  
  
  #{}문자 표시
  f'{{ and }}'
  -> '{ and }'
  ```

  f문자열 포매팅은 포멧함수에서 .format() 대신 f를 앞에쓰고 .format()의 괄호 안에 들어가는 내용을 {0}자리에 적어주면된다.

Q. format 함수 또는 f 문자열 포매팅을 사용해 ‘!!!python!!!’ 문자열을 출력해 보자.

```
# format함수 활용
'{0:!^12}'.format("python")

# f 문자열 포매팅
f'{"python":!^12}'
```

#### 문자열 관련 함수

- 문자열 자료형이 자체적으로 가지고 있는 함수. 문자열 내장함수라고한다.

```
#문자 개수 세는 함수(count)
a = "hobby"
a.count('b')
-> 2

#위치 알려주기1(find)
a = "Python is the best choice"
a.find('b')
-> 14 # 문자열에서 b가 처음 나온 위치
a.find('k')
-> -1 #찾는 문자나 문자열이 존재하지 않으면 -1을 반환한다.

#위치 알려주기2(index)
a = "Life is too short"
a.index('t')
-> 8
a.index('k') #이 경우 k가 없기 때문에 오류가 발생한다. 이것이 find와의 차이다.
-> 오류발생


#문자열 삽입(join)
",".join('abcd')
-> 'a,b,c,d'
",".join(['a', 'b', 'c', 'd']) #이와 같이 리스트를 사용할 수도 있다.
-> 'a,b,c,d'


#소문자->대문자(upper)
a = 'hi'
a.upper()

#대문자->소문자(lower)
a = 'HI'
a.lower()


#왼쪽 공백 지우기(lstrip)
a = " hi "
a.lstrip()
-> 'hi '

#오른쪽 공백 지우기(rstrip)
a = " hi "
a.rstrip()
-> ' hi'

#양쪽 공백 지우기(strip)
a = " hi "
a.strip()
-> 'hi'

#문자열 바꾸기(replace)
a = "Life is too short"
a.replace("Life", "Your leg")
-> 'Your leg is too short'

#문자열 나누기(split)
a = "Life is too short"
a.split() #공백을 기준으로 문자열 나눔
-> ['Life', 'is', 'too', 'short']
b = "a:b:c:d"
b.split(':') #:기호를 기준으로 문자열 나눔
-> ['a', 'b', 'c', 'd']
```

## 리스트 자료형

#### 리스트는 어떻게 만들고 사용할까?

- 구조

  리스트명 = [요소1, 요소2, 요소3, ...]

  ex) odd = [1, 3, 5, 7, 9]

  ```
  a = [] #비어있는 리스트
  
  b = [1, 2, 3] #숫자 리스트
  
  c = ['Life', 'is', 'too', 'short'] #문자 리스트
  
  d = [1, 2, 'Life', 'is'] #숫자 & 문자 리스트
  
  e = [1, 2, ['Life', 'is']] #리스트 안의 리스트
  ```

#### 리스트의 인덱싱과 슬라이싱

- 리스트의 인덱싱

```
a = [1,2,3]
a[0]
-> 1
a[0] + a[2] # 1 + 3, 이와 같이 리스트의 요소값들을 빼내어 숫자열로써 계산이 가능하다.
-> 4
a[-1] #-1은 문자열과 마찬가지로 리스트의 마지막 요소값을 불러온다.
-> 3


#리스트 안의 리스트
a = [1, 2, 3, ['a', 'b', 'c']]
a[3]
->['a', 'b', 'c']
a[-1]
->['a', 'b', 'c']
a[-1][0] #리스트 안의 리스트에 포함된 요소를 이용하는 방법.
-> 'a'
# 삼중 리스트의 인덱싱 방법도 위와 같다.
```

- 리스트의 슬라이싱

```
a = [1, 2, 3, 4, 5]
a[0:2]
-> [1, 2]

a[:2]
-> [1, 2]

a[2:]
-> [3, 4, 5]

# 리스트 안의 리스트
a = [1, 2, 3, [ 'a', 'b', 'c'], 4, 5]
a[2:5] #a[2]부터 a[4]까지
-> [3, ['a', 'b', 'c'], 4]
»> a[3][:2]
['a', 'b']
```

#### 리스트 연산하기

- 리스트 역시 + 기호와 * 기호를 사용할 수 있는 숫자열이 아닌 문자열 처럼 사용된다.

  ```
  #리스트 더하기(+)
  a = [1, 2, 3]
  b = [4, 5, 6]
  a + b
  -> [1, 2, 3, 4, 5, 6]
  
  #리스트 반복하기(*)
  a = [1, 2, 3]
  a*3
  -> [1, 2, 3, 1, 2, 3, 1, 2, 3]
  
  #리스트 길이 구하기
  a = [1, 2, 3]
  len(a)
  -> 3
  
  #개인적으로 궁금해서 시도해본 문자열 관련함수. index와 count만 리스트에서 적용되었다.
  a.count(1)
  -> 1
  a.count(2)
  -> 1
  a.index(2)
  -> 1
  a.index(3)
  -> 2
  ```

#### 리스트의 수정과 삭제

- 리스트에서 값 수정하기

  ```
  a = [1, 2, 3]
  a[2] = 4
  a
  -> [1， 2, 4]
  
  # 문자열의 요소값은 바꿀수 없기때문에 replace라는 함수를 사용하지만 리스트의 경우 이와 같은 방법으로 수정이 가능하다.
  ```

- 리스트 요소 삭제하기(del함수)

  ```
  a = [1, 2, 3]
  del a[1]
  a
  -> [1, 3]
  
  #슬라이싱 기법으로 한번에 여러개를 삭제하는 것도 가능하다.
  a = [1, 2, 3, 4, 5]
  del a[2:]
  a
  -> [1, 2]
  ```

#### 리스트 관련 함수

- 문자열과 마찬가지로 변수 뒤에 '.'을 붙여서 관련함수 사용 가능

  ```
  #리스트에 요소 추가(append)
  a = [1, 2, 3]
  a.append(4)
  a
  -> [1, 2, 3, 4] #뒤쪽에 추가됨.
  a.append([5, 6,])
  a
  -> [1, 2, 3, 4, [5, 6]]
  
  
  #리스트 정렬(sort)
  a = [1, 4, 3, 2]
  a.sort()
  a
  -> [1, 2, 3, 4]
  
  b = ['a', 'c', 'b']
  b.sort
  b
  ->['a', 'b', 'c']
  
  
  #리스트 뒤집기(reverse)
  a = ['a', 'c', 'b']
  a.reverse()
  a
  ['b', 'c', 'a'] #다음과 같이 reverse 함수는 sort와 다르게 정렬한 다음 거꾸로 뒤집는 것이 아닌 현재의 리스트 그대로 거꾸로 뒤집는다. 역순으로 정렬하기 위해선 sort 함수를 취해준 후 reverse 함수를 취해야한다.
  
  
  # 위치 추출(index). 책에는 반환이라 되어있으나 추출이 더 맞는듯 하여 추출로 사용
  a = [1,2,3]
  a.index(3) #3은 리스트 a의 세 번째(a[2]) 요소 
  -> 2
  a.index(1) #1은 리스트 a의 첫 번째(a[0]) 요소
  -> 0
  a.index(0) #리스트에 없는 요소값을 넣으면 에러가 뜬다.
  -> 에러
  
  
  #리스트에 요소 삽입(insert)
  a = [1, 2, 3]
  a.insert(0, 4) #a[0] 위치에 4 삽입 
  a
  -> [4, 1, 2, 3] #append가 리스트의 가장 뒷부분에만 삽입을 하는 함수라면 insert는 지정해준 자리에 삽입이 가능하다.
  a.insert(3, 5)
  a
  -> [4, 1, 2, 5, 3]
  
  
  #리스트 요소 제거(remove)
  a = [1, 2, 3, 1, 2, 3]
  a.remove(3) #remeve(x)는 리스트에서 첫번째로 나오는 x를 삭제한다.
  ->[1, 2, 1, 2, 3]
  
  
  #리스트 요소 끄집어내기(pop)
  a = [1, 2, 3]
  a.pop()
  ->3
  a
  ->[1,2] #index와 비슷하게 맨 마지막 자리의 요소를 추출해내지만 index와 다르게 그 요소를 삭제한다.
  
  a = [1, 2, 3]
  a.pop(1)
  -> 2
  a
  -> [1, 3] #pop(x)는 리스트의 x번째 요소를 돌려주고 그 요소는 삭제한다.
  
  
  #리스트에 포함된 요소x의 개수 세기(count)
  a = [1, 2, 3, 1]
  a.count(1)
  ->2
  
  
  #리스트 확장
  a = [1, 2, 3]
  a.extend([4, 5])
  a
  -> [1， 2, 3, 4, 5]
  b = [6, 7]
  a.extend(b)
  a
  -> [1, 2, 3, 4, 5, 6, 7]
  ```

## 튜플 자료형

- 리스트와 매우 유사하다.

  |        | 튜플                                                         | 리스트                                                       |
  | ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 차이점 | - ()로 둘러싼다. - 요소 값의 변화 불가능 - 단 1개의 요소일 때 반드시 콤마(,)가 필요하다. ex) t1 = (1, ) - 괄호를 생략해도 된다. ex) t4 = 1, 2, 3 | - []로 둘러싼다. - 요소 값의 변화가 가능 - 단 1개의 요소일 때 콤마(,)가 필요하지 않다. ex) L1 = [1] - 괄호를 생략하면 안된다. ex) L4 = [1, 2, 3] |
  | 용도   | 프로그램이 실행되는 동안 그 값이 항상 변하지 않기를 바랄 때 사용 | 수시로 값을 변화시켜야할 때 사용 리스트가 더 자주 사용된다.  |

#### 튜플 다루기

- 인덱싱, 슬라이싱, 더하기, 반복하기(곱하기), 길이구하기는 리스트 함수와 완전히 동일하게 사용된다.
- 다만 요소값을 삭제하는 del함수나 변경하는 방법은 리스트와 다르게 불가능하다.

## 딕셔너리 자료형

#### 딕셔너리란?

- 딕셔너리 : 대응 관계를 나타내는 자료형
- 리스트나 튜플과는 다르게 순차적으로 해당 요소값을 구하지 않고 Key를 통해 Value를 얻는것이 특징.

#### 딕셔너리는 어떻게 만들까?

- 기본 구조

  {Key1:Value1, Key2:Value2, Key3:Value3, ...}

  ex1) dic = {'name' :'pey', ’phone':’011999332', 'birth': '1118'}

   이 경우 Key는 각각 'name', 'phone', 'birth', 해당하는 Value는 'pey', ’011999332', '1118'이 된다.

  ex2) a= {1: 'hi'}

   Key는 1, Value로는 'hi'가 쓰인 상황이다.

  ex3) a= {'a' : [1, 2, 3]}

   Value에 리스트를 넣는 것도 가능하다.

#### 딕셔너리 쌍 추가, 삭제하기

- 딕셔너리 쌍 추가하기

  ```
  a = {1: 'a'}
  a[2] = 'b' # {2:‘b’} 쌍 추가
  a
  -> {1: 'a', 2: 'b'}
  
  a['name'] = 'pey' #{’name’:'pey’} 쌍 추가
  a
  -> {1： ’a’, 2: 'b', 'name': 'pey'}
  
  a[3] = [1,2,3] #{3:[1, 2, 3]}쌍추가
  a
  -> {1: 'a', 2: 'b', 'name': 'pey', 3: [1, 2, 3]}
  ```

- 딕셔너리 요소 삭제하기

  ```
  a = {1: 'a', 2: 'b', 'name': 'pey', 3: [1, 2, 3]}
  del a[1] #Key가 1인 Key:Value 쌍 삭제
  a
  -> {2: 'b', 'name': 'pey', 3: [1, 2, 3]}
  ```

#### 딕셔너리를 사용하는 방법

- 관련 있는 요소를 엮을때 유용함

  ex) {"김연아":”피겨스케이팅", "류현진":"야구", "박지성’':"축구", "귀도": ”파이썬"}

- 딕셔너리에서 Key 사용해 Value 얻기

  ```
  grade = {'pey': 10, ' julliet': 99}
  grade[’pey’] #Key가 'pey’인 딕셔너리의 Value를 반환
  -> 10
  grade['julliet'] #Key가 ’julliet’인 딕셔너리의 Value를 반환
  -> 99
  
  a = {1:'a', 2:'b'}
  a[1] #Key가 1 인 요소의 Value를 반환
  -> 'a'
  a[2] #Key가 2인 요소의 Value를 반환 
  -> 'b'
  a['a']
  -> 1
  a['b']
  -> 2
  ```

  리스트의 경우 처럼 순서에 대한 값이 아닌 key에 해당하는 value값이 print 되는 것을 볼 수 있다.

  또한 반대 케이스인 value의 값을 통해 key를 도출해 내는 것도 가능하다.

  - a[*Key*] = Value
  - a[*Value*] = Key

- 딕셔너리 작성시 주의 사항

  Key는 고유한 값이므로 중복되면 안된다.

  ```
  a = {1:'a', 1:'b'} #1이라는 Key 값이 중복으로 사용
  a
  -> {1： 'b'} #1:'a'쌍이 무시됨, 동일한 Key를 가질 경우 가장 뒤의 Key:Value쌍만 유지
  ```

  Key 값으로 리스트를 쓰는것 역시 안된다. 딕셔너리 역시 사용이 불가능하다. 단, Value에는 어떤 값이든 사용 가능하다.

#### 딕셔너리 관련 함수

- Key 리스트 만들기

  ```
  #Key 리스트 만들기(keys)
  a = {'name': 'pey', 'phone': '0119993323', 'birth': '1118'}
  a.keys()
  -> dict_keys(['name', 'phone', 'birth']) #dict_keys 객체는 리스트와 유사하나 append, pop, remove, sort 함수는 수행할 수 없다.
  
  #dict_keys 객체 반복문 활용(리스트와 유사한 활용)
  for k in a.keys()：
  	print(k)  
      
  -> name
  phone
  birth
  
  #dict_keys 객체 리스트 변환
  list(a.keys())
  -> ['name', 'phone', 'birth']
  ```

- Value 리스트 만들기

  ```
  a = {'name': 'pey', 'phone': '0119993323', 'birth': '1118'}
  a.values()
  -> dict_values(['pey', '0119993323', '1118'])
  
  
  
  for  k in a.values():
  	print(k)
  
  -> pey
  0119993323
  1118
  
  
  list(a.values())
  -> ['pey', '0119993323', '1118']
  ```

- Key:Value 쌍 얻기 & 지우기

  ```
  #Key:Value 쌍 얻기
  a = {'name': 'pey', 'phone': '0119993323', 'birth': '1118'}
  a.items()
  -> dict_items([('name', 'pey'), ('phone', '0119993323'), ('birth', '1118')])
  
  
  #Key:Value 쌍 지우기
  a = {'name': 'pey', 'phone': '0119993323', 'birth': '1118'}
  a.clear()
  a
  -> {}
  ```

- 해당 Key가 딕셔너리 안에 있는지 조사하기(in)

  ```
  a = {'name': 'pey', 'phone': '0119993323', 'birth': '1118'}
  'name' in a
  -> True
  'email' in a
  -> False
  ```

Q. 다음 표를 딕셔너리로 만드시오.

| 항목  | 값     |
| ----- | ------ |
| name  | 홍길동 |
| birth | 1128   |
| age   | 30     |

A. dic = {'name':'홍길동', 'birth':'1128', 'age', '30'}

## 집합 자료형

#### 집합 자료형은 어떻게 만들까?

- set()의 괄호 안에 리스트를 입력하거나 문자열을 입력하여 만든다.

  ```
  s1 = set([1, 2, 3])
  s1
  -> {1, 2, 3}
  
  s2 = set("Hello")
  s2
  {'e', 'H', 'l', 'o'}
  ```

  개인적인 생각으로는 딕셔너리와 같이 {}를 사용하기 때문에 혼동을 주지 않기 위해서 set이라는 함수를 필수적으로 사용해야하는것이 아닐까 라고 생각한다.

#### 집합 자료형의 특징

1. 중복을 허용하지 않는다.

2. 순서가 없다.

   - 따라서 set 자료형으로 저장된 값을 인덱싱으로 접근하려면 리스트나 튜플로 변환한 후 해야한다.

     ```
     s1 = set([1,2,3])
     l1 = list(s1) #리스트로 변환
     l1 
     -> [1, 2, 3]
     l1[0]
     -> 1
     
     t1 = tuple(s1) #튜플로 변환 
     t1
     -> (1, 2, 3)
     t1[0]
     -> 1
     ```

#### 교집합, 합집합, 차집합 구하기

- set 자료형은 교집합, 합집합, 차집합을 구할 때 유용하게 사용

  ```
  s1 = set([1, 2, 3, 4, 5, 6]) #{1, 2, 3, 4, 5, 6} 집합
  s2 = set([4, 5, 6, 7, 8, 9]) #{4, 5, 6, 7, 8, 9} 집합
  
  #교집합(&)
  s1 & s2
  -> {4, 5, 6}
  s1.intersection(s2)
  -> {4, 5, 6}
  
  #합집합(|)
  s1 | s2
  -> {1, 2, 3, 4, 5, 6, 7, 8, 9}
  s1.union(s2)
  -> {1, 2, 3, 4, 5, 6, 7, 8, 9}
  
  # 차집합
  s1 - s2
  -> {1, 2, 3}
  s2 - s1
  -> {8, 9, 7}
  s1.difference(s2)
  -> {1, 2, 3}
  s2.differnece(s1)
  -> {8, 9, 7}
  ```

#### 집합 자료형 관련 함수

```
#값 1개 추가하기(add)
s1 = set([1, 2, 3])
s1.add(4)
s1
-> {1, 2, 3, 4}


#값 여러개 추가하기(update)
s1 = set([1, 2, 3])
s1.update([4,5,6])
s1
-> {1, 2, 3, 4, 5, 6}


#특정 값 제거하기(remove)
s1 = set([1, 2, 3])
s1.remove(2)
s1
-> {1,3}
```

## 불 자료형

#### 불 자료형이란?

- 참(True)과 거짓(False)을 나타내는 자료형

  ```
  a = True
  b = False
  
  type(a)
  -> <class 'bool'>
  type(b)
  -> <class 'bool'>
  ```

  위와 같이 True와 False는 따옴표로 감싸지 않고 True와 False 그 자체로 쓰이는 자료형이다.

  - 활용 예시

    ```
    1==1
    -> True
    
    2 > 1
    -> True
    
    2 < 1
    -> False
    ```

#### 자료형의 참과 거짓

| 자료형   | 값            | 참 or 거짓 |
| -------- | ------------- | ---------- |
| 문자열   | "Python"      | 참         |
|          | ""            | 거짓       |
| 리스트   | [1, 2, 3]     | 참         |
|          | []            | 거짓       |
| 튜플     | ()            | 거짓       |
| 딕셔너리 | {}            | 거짓       |
| 숫자형   | 0이 아닌 숫자 | 참         |
|          | 0             | 거짓       |
|          | None          | 거짓       |

- 참과 거짓이 자료형에서 어떻게 쓰이는지는 예시를 통해서 알 수 있다.

  ```
  a = [1, 2, 3, 4]
  while a: #a가 참인동안
      a.pop() #a의 마지막 요소들을 하나씩 꺼낸다.
      
      
  -> 4
  3
  2
  1    
  
  
  # if문 활용
  if [1, 2, 3]: #[1,2,3]이 True면
  	print("참") #"참"을 print하고
  else: #False면
  	print(" 거짓") # 거짓을 print하라. 이 경우 [1, 2, 3]은 True에 해당하므로 "참"이 출력
      
  -> '참'
  ```

#### 불 연산

- bool 내장 함수 이용

  ```
  bool('python')
  -> True
  bool('')
  -> False
  
  bool([1,2,3])
  -> True
  bool([])
  -> False
  
  bool(0)
  -> False
  bool(3)
  -> True
  ```

## 자료형의 값을 저장하는 공간, 변수

#### 변수란?

- 구조

  변수 이름 = 변수에 저장할 값

  ex) a=1, b="python", c=[1,2,3]

- C나 JAVA의 경우 변수를 만들때 자료형을 직접 지정해야하지만 파이썬의 경우 스스로 판단하여 자료형을 지정

```
>>>a=[1,2,3]
>>>id(a)
4303029896 =>메모리에 저장된 주소
```

#### 리스트 복사법

- 리스트를 복사후 아무 리스트나 수정하여도 모든 리스트의 수정된 값이 적용된다.

1. [:]사용

   ```
   >>>a=[1,2,3]
   >>>b=a[:] => 리스트 a의 처음 요소부터 끝 요소까지 슬라이싱
   >>>a[1]=4 
   >>>a / b
   [1,4,3] / [1,4,3]
   ```

2. copy 모듈사용

   ```
   >>>from copy import copy
   >>>a=[1,2,3]
   >>>b=copy(a) => b는 동일한 값을 지니지만 a와 b는 서로다른 객체이다.
   ```

#### 변수를 만드는 여러 가지 방법

```
a,b=('python','life') = (a,b)='python','life' #튜플형
[a,b]=['python','life'] #리스트형
a=b='python' #변수에 같은 값을 대입


#두 변수의 값 바꾸기
a=3
b=5
a,b=b,a
a / b
-> 5 / 3
```

## 연습문제

#### Q1

```
국어 = 80
영어 = 75
수학 = 55

(국어 + 영어 + 수학) / 3
-> 70
```

#### Q2

```
a=13
if a%2:
    print("홀수")
else:
    print("짝수")
    
-> 홀수
```

#### Q3

```
pin = "881120-1068234"
yymmdd = pin[:6]
num = pin[7:]
print(yymmdd)
print(num)
```

#### Q4

```
pin = "881120-1068234"
print(pin[7])

if pin[7]=="1":
    print("남자")
else:
    print("여자")
```

#### Q5

```
a = "a:b:c:d"
b = a.replace(":", "#")
print(b)
```

#### Q6

```
a = [1, 3, 5, 4, 2]
a.sort()
a.reverse()
print(a)
```

#### Q7

```
a = ['Life', 'is', 'too', 'short']
result = " ".join(a)
print(result)
```

#### Q8

```
a = (1, 2, 3)
a = (1, 2, 3) + (4,)
print(a)
```



#### Q10

```
a = {'A':90, 'B':80, 'C':70}
result = a.pop('B')
print(a)
print(result)
```

#### Q11

```
a = [1, 1, 1, 2, 2, 3, 3, 3, 4, 4, 5]
aSet = set(a)
b = list(aSet)
print(b)
```

#### Q12

```
a = b = [1, 2, 3]
a[1] = 4
print(b)

id(a)
id(b)
```



## 통계

### 모집단과 표본

#### 모집단과 표본

- 모집단(population) : 통계분석 방법을 적용할 관심 대상의 전체 집합
- 표본(sample) : 모집단을 대표할 수 있는 일부를 추출해 조사를 실시 할 때 직접적인 조상이 된 모집단의 일부

#### 모수와 통계량

- 모수 : 모집단을 분석하여 얻는 결과 수치
  - 평균, 분산, 표준편차, 비율 등의 모집단 특성을 모평균, 모표준편차, 모비율로 나타낸다.
- 통계량 : 표본을 분석하여 얻는 결과 수치
  - 평균, 분산, 표준편차, 비율 등의 표본 특성



- 모평균과 표본평균에 해당하는 기호가 아닌 m으로 평균을 표현하기도 하는데 이 경우엔 모평균이나 표본평균을 구분하지 않고 표현하는 경우에 사용된다.

### 표본추출 방법

- 표본조사 결과는 모집단을 100% 표현해낼 수 없지만 자주 활용된다.
  - 시간 및 비용 대비 효과가 가장 크기 때문.
  - 경우에 따라서는 전체를 조사하는 것보다도 표본을 대상으로 주의 깊게 조사하는 편이 정확도가 높을 수도 있음
- 표본을 추출할 때 가장 중요한 것은 모집단에 대한 대표성이다.
  - '모집단에 대한 대표성' : 표본이 모집단을 대표하기에 양적, 질적으로 적합해야한다는 특성.
- 표본추출방법을 크게 2가지로 나눌 수 있다.
  - 확률적 표본추출 방법 : 동일한 확률 아래 표본을 추출
  - 비확률적 표본추출 방법 : 확률과 상관없이 조사자가 자신의 의지로 표본을 뽑거나 조사 대상이 자발적으로 표본이 됨.

#### 확률적 표본추출 방법

1. 단순 무작위 표본 추출
   - 표본추출 방법 중 가장 편한 방법
   - 모집단에서 일정한 규칙에 따라 표본을 기계적으로 추출
   - 장점 : 컴퓨터로 추출하거나 난수표 활용 가능
   - 단점 : 표본 크기가 작다면 표본의 특성이 왜곡
2. 체계적 표본추출
   - 모집단을 대상으로 각각에 대해 번호를 부여, 일정한 순서대로 n개의 간격을 정해 표본을 추출
   - 장점 : 표본을 선정하는 방법이 매우 쉽다.
   - 예시 : 선거 당일 출구 조사
3. 비례 층화 표본추출
   - 모집단을 여러개의 이질적 집단으로 구분한 후, 각 집단의 구성 개수에 비례하도록 추출
   - 예시 : 총원이 10,000명인 한 대학교의 1, 2, 3, 4학년의 비율이 4: 3: 2: 1이라면 1,000명을 추출할때 학년별로 각각 400, 300, 200, 100명씩 추출하여 표본을 구성해야한다.
4. 다단계 층화 표본추출
   - 비례 층화 표본 추출에서 상 하위 표본 단위를 미리 설정하고 그에 맞추어 다시 추출하는 방법이다.
   - 예시 : 총원 10,000명인 A 대학교에서 1,000명을 추출할 때, 먼저 단과대학 별로 구분 지은 후 다시 학과별 구성 숫자에 맞추어 추출
5. 군집 표본추출
   - 모집단 구성이 여러개의 군집으로 이루어진 경우 활용. 몇개의 군집을 표본으로 선택하여 조사.
   - 각 군집들 간의 특성을 볼 때 동질성이 보이고, 군집별 내부 특성을 보면 다양하여 서로 다른 구성으로 군집을 형성한다면 내부는 이질적이나 외부는 동질적이라 표현.
   - 예시 : 서울 시민을 대상으로 자전거 구매 의사를 조사할 때, 25개 구를 모두 조사하지 않고 표본으로 몇 개의 구를 선택하여 조사하는 방법

#### 비확률적 표본추출 방법

1. 편의 표본추출
   - 조사자의 편의에 따라 시간이나 장소에 구애받지 않고 임의로 표본을 추출
   - 장점 : 조사하기 쉬움. 비용이 적게듬.
   - 단점 : 모집단에 대한 대표성을 나타내기 힘듬. 실수나 오류가 가장 많이 발생.
2. 판단 표본추출
   - 조사자가 적합하다고 판단한 구성원들을 표본으로 선택.
   - 표본으로 선택할지 여부를 조사자가 판단한다는 점이 편의 표본추출과의 차이점
3. 할당 표본추출
   - 모집단의 속성을 대표할 만한 연령, 학력, 직업 등의 구분을 결정하고, 각각에 대한 표본의 개수를 미리 정한 후 조사자가 결정한 표본의 개수에 따라 임의로 표본을 추출
4. 자발적 표본추출
   - 조사자의 의지와는 별개로 응답자가 원하여 조사에 응하는 경우를 표본으로 선택
   - 단점 : 조사 주제에 대해 관심이 높은 사람들이 주로 조사에 응하여 결과가 왜곡될 가능성이 크다.

## 표본의 분포

### 정규분포와 표준화

#### 정규분포

- 가장 중요하면서도 일반적인 분포. 가우스분포(Gaussian distribution)로도 불림.
- 확률 분포를 알 수 없더라도 n을 독립적으로 반복하여 늘려간다면 정규분포에 근접한다는 중심 극한 정리에 근거.
- 도수분포곡선 : 각 계급의 빈도를 선으로 연결한 곡선
  - 정규분포의 도수분포곡선은 평균을 중심으로 좌우로 대칭인 종모양. 좌우로 갈수록 x축으로 수렴
- 어떤 경우라도 그래프의 중심이 되는 가장 높은 점(평균)과 꼬리의 각도(분산)만 다르며, 평균을 기준으로 좌우가 대칭.

#### 표준화

- 여러 특성에 대한 분석결과들을 서로 비교할 수 있게 만드는 과정.
- $$ 확률변수X, 정규분포 N(\mu,\sigma^2), Z= \frac{X-\mu}{\sigma} $$
  - 이렇게 만들어진 새로운 확률분포 Z는 표준정규분표 N(0,1)을 따른다.
  - 즉, 표준화 하면 다양한 정규분포의 기준점이 평균 = 0, 표준편차 =1로 동일하게 맞춰진다.

### 표본평균의 확률분포

#### z분포(표준정규분포)

- 표본 정규분포이다.
- 평균은 0, 표준편차는 1로 맞춘다.
- 주로 표본의 개수가 충분하거나 모분산(σ^2)을 알고 있는 경우에 사용한다.
- $$ Z=\frac{X-\mu}{\sigma}=\frac{X-\mu}{\sigma/\sqrt{n}} $$

#### t분포

- 표본이 충분하지 못한 경우에 사용(30개를 넘지 못하는 경우)
- 모집단은 정규분포를 이룬다는 가정이 필요. 그러므로 t분포도 '평균=0, 분산>1'인 정규분포를 따른다.
- 표준정규분포와는 다르게 모분산을 알지 못하는 경우에 사용.
- 모분산을 몰라도 n이 매우 크다면 z분포로 계산된 결과와 거의 차이가 없다.
- $$ t_{(n-1)} = \frac{X-\mu}{s}=\frac{X-\mu}{s/\sqrt{n}} $$

#### z분포와 t분포의 관계

- z 분포의 공식과 t분포의 공식은 n과 n-1을 제외하고는 식이 동일하다. 즉 n이 무한대로 커지면 두 분포는 동일한 분포가 된다.

### 표본분산의 확률분포

- x^2 분포(카이제곱 분포), F분포 : 분산의 추론과 관련된 분포.
- x^2 분포(카이제곱 분포) : 1개의 분산을 추론한 분포
- F분포 : 2개의 분산을 추론한 분포

#### x^2 분포(카이제곱 분포)

- 정규분포로부터 도출. z분포의 제곱에 대한 분포.
- 항상 0보다 큰 값을 가진다.
- $$ \chi^2분포=확률변수\sum_{i=1}^{n}{x_i}^2 $$
- 확률변수 x_1, x_2, x_3, x_4...x_n가 독립이고 표준정규분포라면 x_1^2, x_2^2, x_3^2, x_4^2...x_n^2가 새로운 확률변수를 구성하게 되고, 이 분포를 자유도가 n인 x^2분포라 하며 위와 같은 식으로 정의된다.
- ![image-20210218061950710](C:\Users\minho\OneDrive\바탕 화면\world Leader\chi-square graph)
- 카이제곱 분포는 위 그림과 같이 표본의 개수(자유도)에 따라 각기 다른 분포를 나타내는 것이 특징이다.

#### F분포

- $$ F_{(v_1,v_2)}=\frac{v_1}{v_2}, (v_1=\frac{s_1}{(n-1)},v_2=\frac{s_2}{(m-1)}) $$
- 위의 식으로 표현. 이때 v_1, v_2는 x^2에 대한 분산을 의미.
- 카이제곱 검정을 따르는 분포 2개는 F 분포를 따르게 된다.
- ![image-20210218062532261](C:\Users\minho\OneDrive\바탕 화면\world Leader\F graph)
- v_1과 v_2가 같다면 F분포는 1을 기준으로 값이 결정되며 같지 않다면 1과 멀어진다.
- 표본의 개수가 많아질 수록 1과 가까운 분포를 나타냄을 확인 가능

### 표본비율의 확률분포

표본비율 : 모비율을 추정하기 위해 표본으로 추정한 비율(proprotion)

#### \hat{p}(표본비율) 분포

- 모비율을 추정하기 위해 사용.
- 베르누이 시행의 이항분포를 활용
  - 베르누이 시행 : 어느 한 사건이 발생하는 경우
    - '남성과 여성', '성공과 실패', '구매와 비구매'

## 표본분포와 중심극한정리

### 표본분포

- 표본분포(sample distribution) : 표본에서 도출되는 통계량을 확인하는 확률분포
- 모수를 추정하기 위한 표본 통계량의 확률분포이므로 모수를 추정할 확률을 얻을 수 없어 여러번 측정해야함.

### 표본평균의 오차

- 아주 정교하게 표본을 설계해도 오차는 발생하므로 이를 최대한 줄여가는 것이 중요하다.

### 중심극한정리(CLT)

- 표본의 개수(*n*)가 충분하다면 모수를 모르는 상황에서도 표본 통계량으로 정규분포를 구성하여 모수를 추정할 수 있음.
- 모집단이 정규분포를 이루지 않아도 표본의 개수가 충분하다면 정규분포에 가까워진다.
- 일반적으로 크다의 기준은 30개 이상으로 잡는다.
- 중심극한 정리를 이용하면 각기 다른 모양의 분포를 비교할 수 있다.

## 연습문제



# Ch3. 데이터와 통계량

## 01 데이터의 수집

### 변수와 데이터

#### 변수(variable)

- 변수 : 어떠한 대응 관계로 변화하는 수 혹은 함수관계로 대응하며 주어진 범위 안에서 변화하는 수
- 조사 목적에 따른 대응 관계, 주어진 환경 등에 의해 변화하는 수.

#### 데이터(data)

- 조사 목적에 맞는 변수를 기반으로, 표본으로부터 수집한 자료
- 변수에 특성에 따라 단일자료 또는 다중 자료로 수집.
- 단일 자료는 비교적 간단한 변수에 사용, 다중 자료는 복잡하거나 정교하게 살펴야 그 의미를 알 수 있는 변수에 사용

### 척도

- 조사 대상이 지닌 특성을 데이터로 활용하기 위해 수치화하는 작업.

#### 범주형 척도(categorial scale)

- 데이터들을 구분지어 나눌 수 있는 척도
- 명목척도(nominal scale)
  - 수 또는 순서의 개념과 상관없이 이름만 붙여지는 척도.
  - 빈도분석과 기술통계분석에서 표본의 성격을 나타내는데 활용
  - ex) 성별, 지역, 학력, 종교
- 서열척도(ordinal scale)
  - 숫자 혹은 연산과는 관련이 없지만, 순서(서열)을 구분할 수 있다.
  - 주로 서열 상관분석에서 활용된다.
  - ex) 마라톤 경기 결과, 성적결과

#### 연속형 척도(continuous scale)

- 연결된 속성의 데이터를 조사 목적에 맞게 구분한 척도
- 등간척도(interval scale)
  - 측정된 자료들 간에 더하기, 빼기 가능/ 0값을 가지지 않기 때문에 곱하기, 나누기는 불가능.
  - 측정 대상에 순서가 있고, 그 간격을 척도로 사용한다.
  - 빈도분석, 기술통계분석, 피어슨 상관분석, 분산분석, 회귀분석 등에 활용
- 비율척도( ratio scale)
  - 0값도 가짐으로써 사칙연산이 모두 가능.
  - 거의 모든 통계분석에서 사용 가능

| 구분        | 척도     | 예시                              |
| ----------- | -------- | --------------------------------- |
| 범주형 척도 | 명목척도 | 남/여, 서울/대구/광주/부산        |
|             | 서열척도 | 1등/2등/3등, 금메달/은메달/동메달 |
| 연속형 척도 | 등간척도 | 온도                              |
|             | 비율척도 | 무게, 부피, 길이                  |

## 데이터의 표현 방법

### 도수분포표(frequency distribution table)

### 히스토그램

### 막대그래프

### 상자수염그림

- 2개 이상인 집단의 자료를 서로 비교하는 사용
- 그림 자체에서 최대값, 최소값, 평균, 중앙값 등 많은 정보를 보여줄 수 있음.

## 03 기초 통계량

#### 기초 통계량의 개념

- 통계량은 표본이 갖는 특성을 제시하여 이를 바탕으로 모수를 추정하더라도 문제가 없음을 설명하는 기초자료가 된다.

#### 기초 통계량의 구분

- 표본의 중심을 이루는 값 : 대표값, 중심경향화 값, 중심경향 측정치 등으로 불린다.
- 그 종류에는 평균, 중간값, 최빈수, 사분위수가 있다.
- 산포도 : 표본의 범위, 분산, 표준편차, 변동계수 등으로 구성
- 비대칭도 : 표본이 최대값이나 최소값으로 몰려있는 정도
  - 왜도(skewness)로 표본의 비대칭도 파악.
- 첨도(kurtosis) : 표본의 뾰족한 정도를 나타내는 자료.

### 중심경향도(measure of central tendency)

- 데이터를 종합하여 그 중심을 이루는 값이 어느정도가 될지를 구한 값.
- 평균, 중간값, 최빈수 등이 있다.

#### 평균(mean)

- 가장 많이 활용되는 중심경향도

- 산술평균(arithmetic mean)

  - 산술평균으로부터 관찰값 편차의 합은 0이다.
  - 자료의 분포가 좌우대칭이면 산술평균과 중위수(중앙값)는 같다.
  - 대표값 중에서 가장 많이 사용된다.

  $$ \bar{x}=\frac{x_1+x_2+x_3+...+x_n}{n}=\frac{1}{n}\sum_{i=1}^{n}x_i $$

- 기하평균 (geometric mean)

  - 평균변화율, 평균성장률, 경제성장률 등의 비율을 구할 때 이용하는 수치.
  - 시계열 자료 변동을 대표하는 값으로 가장 적당하다.

  $$ M_g={^n}\sqrt{x_1*x_2*x_3*...*x_n} $$

- 조화평균 (harmonic mean)

  - 양수인 n개의 측정치를 역수로 하여 산술평균을 구하고 이를 다시 역수로 나타낸 평균
  - 가속현상에서 평균속도를 구하는데 사용.

  $$ M_h=\frac{1}{\frac{1}{n}(\frac{1}{x_1}+\frac{1}{x_2}+\frac{1}{x_3}+...+\frac{1}{x_n})} $$

- 산술평균, 기하평균, 조화평균

  - (산술평균) >= (기하평균) >= (조화평균)

- 절사평균(truncated mean)

  - 표본 측청치들 중 편차가 큰 극단치가 존재하는 경우 산술평균을 활용하기 어려워 상위와 하위 일정 부분을 제거하고 계산한 평균.

#### 중간값 (중위수, 중앙값, 중앙치)(median)

- n개의 관측치를 크기 순서로 늘어놓았을 때 관측된 자료의 편중과 상관없이 가운데에 위치한 값.
- n이 홀수 일땐 가운데 값, n이 짝수 일땐 가운데 2개의 표본값에 평균값을 찾는다.

#### 최빈수 (mode)

- 표본에서 가장 많이 나타나는 관측치
- 특징
  - 중심경향의 측정치로 1개 이상 존재 가능
  - 측정치 중 가장 많이 나타난 값. 도수 분포표에서 가장 많이 나타나는 계급의 값
  - 자료 중 평균이나 중간값을 구하기 어려운 경우에 많이 활용(ex-혈액형)

예제 3-5

### 산포도(dispersion)

- 측정된 데이터가 어떻게 분포하는지를 알아야 데이터를 제대로 이해 가능.
- 산포도 : 표본이 가지는 분포의 정도.
- 분산, 표준편차, 범위, 변동계수, 사분위수 등이 사용된다.
- 특징
  - 수치가 작을수록 대표값에 집중되고, 수치가 클수록 대표값으로부터 멀리 흩어져있다.
  - 관측값들이 평균(중심화경향도)으로 부터 멀리 떨어질수록 분산은 커진다.
  - 편차의 총 합은 0이다.
- 척도에 따라 산포도가 가지는 의미
  - 명목척도 : 최빈수만 존재하므로 산포도가 의미 X
  - 서열척도 : 산포도의 범위만 존재.
  - 등간척도, 비율척도 : 범위, 사분편차(사분위수 간의 차이), 분산, 표준편차가 존재한다. 따라서 산포도를 확인하여 표본의 특성 파악O

#### 모분산

- 모평균과 모집단의 개별 측정치들 간의 차를 구해서 제곱하여 모두 더한 후, 그 값을 다시 모집단을 구성하는 개수로 나누어 계산한 값.
- (편차)^2들의 합 / n
- 예제 3-6

#### 표본분산

- 모집단을 기준으로 하지 않고, 표본을 선정해서 표본의 개수 (n-1)로 계산한 분산.
- 표본의 개수에서 1을 빼야 더 정확한 분산을 도출할 수 있다.
  - 자유도(degree of freedom, df)

#### 표준편차

- 분산값에 루트를 씌워 제곱근을 만든 값.

#### 변동계수(변이계수)

- 서로 다른 두 집단을 비교하여 더욱 많은 의미를 찾아냄.
- 변동계수가 작을 수록 평균에 더 밀집.
- CV = s(표준편차) / x(평균)

#### 사분위수(quartile)

- 오름차순에 따라 측정값을 작은 것부터 크기순으로 배열하고, 누적 백분율을 4등분한 각 점의 수치.
- 제1사분위수 = 누적백분율 25%, 제2사분위수 = 50%(중간값과 동일), 제3사분위수 = 75%, 제4사분위수 = 100%
- 사분위수의 범위 : 제 3사분위수와 제 1사분위수의 차이

### 비대칭도

- 표본의 도수분포에서 평균값에 대한 비대칭의 방향이나 정도를 나타내는 척도
- 왜도를 통해 분포곡선이 좌측이나 우측 중 어느 쪽으로 쏠려 있는지를 설명한다.

#### 왜도

- 피어슨의 비대칭도(Pearson`s coefficient of skewness)라고도 하며, 자료의 분포가 어느 정도로 비대칭 적으로 분포되어있는지 나타내는 통계지표.
- 산포의 정도와는 상관 X, 분포의 봉우리 치우침 정도를 나타냄.
- 양의 왜도(정적 왜도 : positive skew)
  - 데이터 중심이 왼쪽으로 치우쳐 오른쪽으로 꼬리가 길게 늘어진 형태
  - 왜도가 0보다 크게 나온다.
  - 평균 > 중위수 > 최빈수 형태의 분포
- 음의 왜도(부의 왜도:negative skew)
  - 데이터 중심이 오른쪽으로 치우쳐 왼쪽으로 꼬리가 길게 늘어진 형태
  - 왜도가 0보다 작다.
  - 평균<중위수<최빈수

### 첨도

- 분포 곡선의 봉우리가 얼마나 뾰족한지를 나타내는 수치.
- 첨도가 높을수록 뾰족하고 낮을수록 완만하다.

## 연습문제

### Q3

 평균, 중간값, 최빈수 등이 있다.

### Q4

측정된 데이터가 어떻게 분포하는지를 알아야 데이터를 제대로 이해 가능하기 때문에 산포도를 파악한다.

분산, 표준편차, 범위, 변동계수, 사분위수 등이 사용된다.
