지난 번에는 저희 팀 R&D를 위해 프론트엔드 테스팅 툴을 조사해봤습니다.

이번에는 우리 팀에 적합한 차트 라이브러리는 무엇이 있을지 조사해보며 정리해봤습니다.

저희 팀은 **Vue.js** 프레임워크를 유지하기로 결정했으니, 이에 최적화되고 눈에 띄었던 차트 라이브러리들을 공유해보고자 합니다.

## ✍️ **차트 라이브러리 종류**

---

### **1) Chart.js**

[##_Image|kage@cMyWRK/btsGcNkFt8s/Tt07Si0DLLNMkdPkjB7jkk/img.jpg|CDM|1.3|{"originWidth":400,"originHeight":277,"style":"alignCenter","width":438,"height":303,"caption":"Chart.js","filename":"chart.js 로고.jpg"}_##]

먼저 **Chart.js** 입니다.

Chart.js는 웹 상에 차트를 그리는데 특화된 라이브러리로, **Canvas**를 이용한 라이브러리 입니다.

Vue.js 프로젝트에서 가장 많이 쓰이는 라이브러리 1위로 알려져있고, 워낙 대중성이 높아 정보 활성화가 잘 되어 있습니다.

현재 중량 모니터링 페이지에서 실시간 데이터를 보이기 위해 **라인 차트**를 사용 중입니다.

### **▶ 장점**

-   **간단한 차트를 표현하기에 편리함**
-   **가벼움**(Highchart 보다 훨씬 가볍다고 함)
-   **러닝 커브(학습 곡선)가** **낮음**
-   많이 사용되기 때문에, 정보 활성화가 잘되어 있음  
      
    

### **▶ 단점**

-   타입과 옵션이 많지 않음
-   기본 옵션 외의 것들의 커스터마이징이 까다로움

**※ 접속 링크**

[https://www.chartjs.org/docs/latest/samples/information.html](https://www.chartjs.org/docs/latest/samples/information.html "https://www.chartjs.org/docs/latest/samples/information.html")

### **2) Apache ECharts**

[##_Image|kage@dx8cnb/btsF9cUwg5P/dw1g8WObt36kKD1VMyt0TK/img.png|CDM|1.3|{"originWidth":758,"originHeight":881,"style":"alignCenter","width":258,"height":300,"caption":"Apache Echarts","filename":"echarts 로고.png"}_##]

먼저 **Apache Echarts** 입니다.

Apache에서 제작한 차트 라이브러리로 **Canvas**를 이용한 라이브러리 입니다.

무료이면서, 설명이나 예제(Demo)가 다양하고 쉽게 정리되어 있습니다.

### **▶ 장점**

-   **데이터 처리에 강점을 보임**
-   **다크 모드, 차트 패턴과 같은 테마 기능을 제공**
-   다양한 차트 유형을 제공
-   커스터마이징이 용이함  
      
    

### **▶ 단점**

-   러닝 커브(학습 곡선)가 조금 높음
-   버전업 주기가 빠름

**※ 접속 링크**

[https://echarts.apache.org/examples/en/index.html](https://echarts.apache.org/examples/en/index.html "https://echarts.apache.org/examples/en/index.html")

### ****3) Highcharts****

[##_Image|kage@cgqwKZ/btsGaYOhGs1/ITk8HWi49XU78dve5jSU2K/img.png|CDM|1.3|{"originWidth":440,"originHeight":180,"style":"alignCenter","caption":"Highcharts","filename":"Highcharts 로고.png"}_##]

먼저 **Highcharts** 입니다.

프레임워크를 떠나서 웹에서 가장 널리 사용되는 차트 도구입니다.

Higncharts는 **SVG**를 이용한 라이브러리 입니다.

현재 저희 프로젝트에서 가장 많이 사용하는 차트 라이브러리 입니다.

### **▶ 장점**

-   **러닝 커브(학습 곡선)가 낮음**
-   **디자인이 이쁘고, 깔끔함**
-   커스터마이징이 용이함  
      
    

### **▶ 단점**

-   무거움
-   상업용도는 유료이기 때문에 무료 버전은 유형과 옵션이 상대적으로 많지 않음

**※ 접속 링크**

[https://www.highcharts.com/demo?\_gl=1\*wn507y\*\_up\*MQ..&gclid=CjwKCAjw5ImwBhBtEiwAFHDZx32EXEia4w2M-UBR5SpdfuPIvQxcmdl\_CrzB2SPiieoi5c\_HQJwaxRoCM9UQAvD\_BwE](https://www.highcharts.com/demo?_gl=1*wn507y*_up*MQ..&gclid=CjwKCAjw5ImwBhBtEiwAFHDZx32EXEia4w2M-UBR5SpdfuPIvQxcmdl_CrzB2SPiieoi5c_HQJwaxRoCM9UQAvD_BwE "https://www.highcharts.com/demo?_gl=1*wn507y*_up*MQ..&gclid=CjwKCAjw5ImwBhBtEiwAFHDZx32EXEia4w2M-UBR5SpdfuPIvQxcmdl_CrzB2SPiieoi5c_HQJwaxRoCM9UQAvD_BwE")

### ****4) ApexCharts****

[##_Image|kage@d46tn8/btsF94VNgte/uEPQ9nnFcVE2BWPkNLzehK/img.png|CDM|1.3|{"originWidth":177,"originHeight":177,"style":"alignCenter","width":235,"height":235,"caption":"ApexCharts","filename":"apexCharts 로고png.png"}_##]

먼저 **ApexCharts** 입니다.

다른 차트 라이브러리들과 달리 상대적으로 신생 라이브러리라고 합니다.

오픈 소스이기 때문에 상용 어플리케이션에서 무료로 사용 가능합니다.

ApexCharts는 **SVG**를 이용한 라이브러리 입니다.

### **▶ 장점**

-   **러닝 커브(학습 곡선)가 낮음**
-   **문서가 잘 정리되어 있고, UI는 깔끔하고, Interaction 부분이 세련되게 구성됨**
-   커스터마이징이 용이함  
      
    

### **▶ 단점**

-   가볍진 않음(속도는 Highcharts와 다를게 없어보임)
-   Highcharts에 비해 눈에 띄는 큰 장점이 없어보임

**※ 접속 링크**

[https://apexcharts.com/javascript-chart-demos/](https://apexcharts.com/javascript-chart-demos/ "https://apexcharts.com/javascript-chart-demos/")

### ****5) AmCharts****

[##_Image|kage@olkzb/btsGctUf8FU/f2KY5K64S5Gn5cC7vBMCh0/img.png|CDM|1.3|{"originWidth":1000,"originHeight":558,"style":"alignCenter","width":396,"height":221,"caption":"AmCharts","filename":"amCharts.png"}_##]

먼저 **AmCharts** 입니다.

데이터 시각화에 최적화된 고급 차트 라이브러리입니다.

개발자라면 한번씩 사용해보고 싶은 라이브러리라고 합니다.

AmCharts는 **SVG**를 이용한 라이브러리 입니다.

### **▶ 장점**

-   차트 라이브러리 중 디자인이 가장 고급지고 깔끔함
-   차트 기능 및 옵션이 많음
-   최근 트렌드와 이슈에 맞는 테마를 적극적으로 업데이트 함

### **▶ 단점**

-   유료 라이센스(조건부 무료)
-   무료 버전은 좌측 하단에 워터마크가 남음(신경 쓰일 정도는 아님)
-   러닝 커브(학습 곡선)가 조금 높음

**※ 접속 링크**

**[https://www.amcharts.com/demos/](https://www.amcharts.com/demos/ "https://www.amcharts.com/demos/")**

  
  

## ✍️ **앞으로의 방향**

---

조사해보니 정말 매력적인 차트 라이브러리가 많았습니다.

차트 라이브러리를 선정하기 전, 팀 내부적으로 가장 고려해야 할 요소는 아래 2가지 입니다.

**1\. 속도**

**2\. 화면 깨짐**

**속도**는 중요합니다. 간혹 대용량 데이터를 조회할 시, 차트 조회 속도가 느렸던 적도 있었습니다. 대용량 데이터 처리에 적합한 차트 라이브러리를 잘 선정하여 사용해보면 좋을 것 같습니다.

**화면 깨짐** 또한 사용자 입장에서 불편한 요소입니다. Canvas 차트가 이에 약점을 보이고 있는데, SVG 차트 라이브러리들과 적극적으로 비교해보고 테스트함으로써 선택하면 좋을 것 같습니다.

이번 R&D 기간을 통해 팀 프로젝트에 적합한 차트 라이브러리를 잘 선정했으면 하는 바램입니다.
