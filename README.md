## **1\. 코딩 컨벤션(Coding Convention)**

\--- 내용 작성 필요 ---

&nbsp;
&nbsp;

## **2\. 네이밍 컨벤션(Naming Convention)**
&nbsp;

### ✍️ 네이밍 기본

---

-   단일 글자로 이름 짓지 않고, 사용 의도를 충분히 알만큼 명확하게 이름을 작성하도록 한다.

``` javascript
// bad
let a = '';
let x = '';
function abc(){};

// good
let plantName = '';
let columnList = [];
function getPlantInfo(){};
```

-   줄임말을 사용하지 않는다.

``` javascript
// bad
let stdName = '';
let rstObj = '';
let eqpId = '';
let eqpNm = '';

// good
let studentName = '';
let resultObj = '';
let equipmentId = '';
let equipmentName = '';
```

-   이름 맨 앞이나 맨 뒤쪽에 **언더바(_)** 를 사용하지 않는다.  

  &nbsp;&nbsp; ${\color{red}※ 언더바를 \space 써야하는 \space 상황이있나? \space}$
    
-   앞에는 항상 **알파벳**으로 시작되어야 한다.
    
-   영어를 사용하되, 한글 발음을 영어 그대로 표기하지 않는다.
    
-   가독성을 위해 약어는 **모두 대문자 혹은 모두 소문자**로 표기한다.

``` javascript
// bad
const SmsMessage = 'message';

// good
const SMSMessage = 'message';
```
    
-   export 되는 파일 내의 모든 상수는 **모두 대문자**로 표기한다.
    
    
``` javascript
// bad
export const apiKey = 'key';

// good
export const APIKEY = 'key';
```

&nbsp;

### 📁 패키지 & 파일(Package & File)

---

-   파일 이름은 ${\color{green}lowerCamelCase}$로 표기한다.
-   패키지 이름은 **소문자**로 표기한다.
-   파일의 이름은 default export의 이름과 일치해야한다.

    
``` javascript
// bad
export default sysLine;

// good
import sysLine from './sysLine'
```
    
&nbsp;

### 🌱 변수(Variable)

---

-   변수명은 ${\color{green}lowerCamelCase}$로 표기한다.  

  &nbsp;&nbsp; ${\color{red}※ 단, \space export \space 되는 \space 파일 \space 내의 \space 상수는 \space 예외.}$
-   **명사**를 사용하여 작성한다.
-   boolean 타입의 변수는 **'is'** 로 시작한다.

``` javascript
// bad
const visible = true;

// good
const isVisible = true;
```

&nbsp;

### 📥 함수(Function)

---

-   함수명은 ${\color{green}lowerCamelCase}$로 표기한다.  
-   함수명은 **동사**를 사용하여 표기한다.

``` javascript
// bad
function tag(){};
function userInfo(){};

// good
function getTag(){};
function getUserInfo(){};
```

-   데이터를 가져올 때(getter) 함수명 앞에 **'get'** 을 붙히고,
    
    데이터를 설정할 때(setter) 함수명 앞에 **'set'** 을 붙힌다.

``` javascript
// bad
function selectPlantList(x,y){};
function changePlantList(x,y){};

// good
function getPlantList(userId, grade){};
function setPlantList(userId, grade){};
```
    
-   ${\color{red}DevExtreme \space 관련 \space 함수는 \space 별도의 \space 네이밍 \space 룰이 \space 필요한가?}$
    
-   함수의 Parameter는 ${\color{green}lowerCamelCase}$로 표기한다.
-   함수의 Parameter는 명확한 쓰임새를 알 수 있는 **명사**를 사용하도록 한다.

``` javascript
// bad
function getClassInfo(x,y){};

// good
function getUserInfo(userId, grade){};
```
    
-   함수를 export 할 때는 ${\color{green}lowerCamelCase}$로 표기한다.

&nbsp;

### 🟦 객체(Object)

---

-   객체명은 ${\color{green}lowerCamelCase}$로 표기한다.  
-   객체명은 끝에 **'obj'** 붙힌다.

``` javascript
// bad
let tag = {};

// good
let tagObj = {};
```
    
-   객체를 export 할 때는 ${\color{green}lowerCamelCase}$로 표기한다.

&nbsp;

### 🟪배열(Array)

---

-   배열명은 ${\color{green}lowerCamelCase}$로 표기한다.
-   배열명은 끝에 **'List'** 붙힌다.

``` javascript
// bad
let tag = [];

// good
let tagList = [];
```
    
-   배열을 export 할 때는 ${\color{green}lowerCamelCase}$로 표기한다.

&nbsp;

### 📜 클래스(Class)

---

-   클래스나 생성자 이름은 ${\color{green}PascalCase}$로 표기한다.
-   클래스를 export 할 때는 ${\color{green}PascalCase}$로 표기한다.
