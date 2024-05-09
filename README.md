## **1\. 코딩 컨벤션(Coding Convention)**

\--- 내용 작성 필요 ---

## **2\. 네이밍 컨벤션(Naming Convention)**
&nbsp;
&nbsp;
&nbsp;

### ✍️ 네이밍 기본

---

단일 글자로 이름 짓지 않고, 사용 의도를 충분히 알만큼 명확하게 이름을 작성하도록 한다.

```
bad : let a = ''; / let x = ''; / function abc();  
good : let plantName = '' / let columnList = \[\]; / function getPlantInfo();
```

-> bad : let a = ''; / let x = ''; / function abc();**
-> good : let plantName = '' / let columnList = \[\]; / function getPlantInfo();**

-   줄임말을 사용하지 않는다.
    
    **\-> bad : stdName / good : studentName**
    
    **\-> bad : rstObj / good : resultObj**
    
    **\-> bad : eqpId / good : equipmentId**
    
    **\-> bad : eqpNm / good : equipmentName**
    
-   이름 맨 앞이나 맨 뒤쪽에 **언더바(\_)**를 사용하지 않는다.
    
    ※ 언더바(\_)를 써야하는 상황이 있나?
    
-   앞에는 항상 **알파벳**으로 시작되어야 한다.
    
-   영어를 사용하되, 한글 발음을 영어 그대로 표기하지 않는다.
    
-   가독성을 위해 약어는 **모두 대문자 혹은 모두 소문자**로 표기한다.
    
    **\-> bad : const SmsMessage = 'message'; / good : const SMSMessage = 'message';**
    
-   export 되는 파일 내의 모든 상수는 **모두 대문자**로 표기한다.
    
    **\-> bad : export const apiKey = 'key'; / good : export const APIKEY = 'key';**
    

### 📁 패키지 & 파일(Package & File)

---

-   패키지 이름은 소문자로 표기한다.
-   파일 이름은 **lowerCamelCase**로 표기한다.
-   파일의 이름은 default export의 이름과 일치해야한다.
    
    **\-> export default sysLine;**
    
    **\-> import sysLine from './sysLine'**
    

## 🌱 변수(Variable)

---

-   변수명은 **lowerCamelCase**로 표기한다.  
    ※ 단, export 되는 파일 내의 상수는 예외.
-   명사를 사용하여 작성한다.
-   boolean 타입의 변수는 **'is'**로 시작한다.
    
    **\-> bad : const visible = true; / good : const isVisible = true;**
    
-   ???

## 📥 함수(Function)

---

-   함수명은 lowerCamelCase로 표기한다.
-   함수명은 동사를 사용하여 표기한다.
    
    **\-> bad : function tag(); / function userInfo();**
    
    **\-> good : function getTag() / function getUserInfo();**
    
-   데이터를 가져올 때(get) 함수명 앞에 'get'을 붙히고,
    
    데이터를 설정할 때(set) 함수명 앞에 'set'을 붙힌다.
    
-   어떤거는 selectList, 어떤거는 itemList... 통일하고 싶다.
    
    또, Grid 3개일 때 selectListRight, selectListLeft, selectListBottom 등등 이런 것도 통일?
    
-   DevExtreme 관련 함수는 별도의 작성법 필요
    
-   함수의 Parameter는 **lowerCamelCase**로 표기한다.
-   함수의 Parameter는 명확하게 이름을 통해 쓰임새를 알 수 있도록 한다.
    
    **\-> bad : function getClassInfo(x,y); / good : function getUserInfo(userId, grade);**
    
-   함수를 export 할 때는 **lowerCamelCase**로 표기한다.
    

## 🟦 객체(Object)

---

-   객체명은 lowerCamelCase로 표기한다.
-   객체명은 끝에 'obj' 붙힌다.
    
    **\-> bad : tag = {}; / good : tagObj = {};**
    
-   객체를 export 할 때는 **lowerCamelCase**로 표기한다.
    

## 🟪배열(Array)

---

-   배열명은 lowerCamelCase로 표기한다.
-   배열명은 끝에 'List' 붙힌다.
    
    **\-> bad : tag = \[\]; / good : tagList = \[\];**
    
-   배열을 export 할 때는 **lowerCamelCase**로 표기한다.
    

## 📜 클래스(Class) \-> 우리 코드에서 클래스를 잘 사용하지는 않음.

---

-   클래스나 생성자 이름은 **PascalCase**로 표기한다.
-   클래스를 export 할 때는 **PascalCase**로 표기한다.
