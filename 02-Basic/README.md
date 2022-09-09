[Eng | 영어](#02-Core-Syntax)
/
[Kor | 한국어](#02-기초-문법)

# 02-Core Syntax

## 1.1 Varibles & Constants

### Variables
`Variables` : data container | data storage

If you want to change value, it can be accessed using the variable name without keywords(like var, let).

### Constants
`Contants` : to use fixed value, but its also datacontainer | data storage

If you want to change value, it can only be done atthat location. (Only can be edited directly)

```javascript
let userName = 'Max'; // let keyword to made a variable

userName = 'Manu'; // assign a new value to userName

const totalUsers = 15; // const keyword to made a constant

totalUsers = 20; // Error: it(constant) cannot bechanged
```

### Variable Naming
```javascript
// Allowed

let userName // is the Best Practice: use camelCase

let ageGroup5 // Can be used: only letters and digits

let $kindOfSpecial // Can be used: starting with $ is allowed

let _internalValue // Can be used: starting with _ is allowed


// Not Allowed | Not Recommended

let user_name // Can be used(: snake_case) but bad practice => use camelCase

let 21Players // Cannot be used: starting digits not allowed

let user-b // Cannot be used: _ is allowed as mentioned on the left, but other special characters are not allowed no matter where you plan on using them.

let let // Cannot be used: keywords not allowed

```

## 1.2 

 

## 1.3 

## 1.4 

## 1.5 

<br>

# 02-기초 문법

## 1.1 변수와 상수

### 변수
`변수` : 변수는 데이터 저장소와도 같다.

변수에 할당된 값을 변경하고 싶다면, 키워드를 제외한 변수명을 통해 접근 및 재할당이 가능하다.

### 상수
`상수` : 고정된 값을 이용하기 위한 것이지만, 상수 또한 데이터 저장소와도 같이 사용된다.

만약 상수에 할당된 값을 바꾸고 싶다면, 직접수정을 통해서만 그 값을 변경할 수 있다.

```javascript
let userName = 'Max'; // 변수 생성을 위한 let 키워드 사용

userName = 'Manu'; // let 키워드를 사용해 선언한 변수에는 재할당이 가능함

const totalUsers = 15; // 상수 생성을 위한 const 키워드 사용

totalUsers = 20; // Error: 상수(const 키워드)는 재할당이 불가능하다
```

### 변수 네이밍 유의사항
```javascript
// 허용되는 것

let userName // 카멜 케이스 사용이 가장 권장되는 방법이다

let ageGroup5 // 문자와 숫자 혼용이 가능하다

let $kindOfSpecial // 달러기호를 변수이름 시작부분에 사용이 가능하다

let _internalValue // 언더스코어를 변수이름 시작부분에 사용이 가능하다


// 허용되지 않는 것 | 권장되지 않는 것

let user_name // 스네이크 케이스는 일반적으로 자바스크립트에서 사용하기를 권장하지 않지만, 문법적 오류는 발생하지 않는다

let 21Players // 변수명은 숫자로 시작할 수 없다

let user-b // 언더스코어나 달러기호를 시작부분에 붙일 수 있지만, 그 외에 다른 특수기호는 사용이 불가하며 모든 특수문자 등은 뒤에 붙여서 변수명을 짓는데 사용할 수 없다.

let let // 자바스크립트에서 사용하는 키워드(명령어)는 변수이름으로 사용할 수 없다

```

## 1.2 



## 1.3 