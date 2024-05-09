<p data-ke-size="size18"><span style="color: #333333;"><span style="font-size: 1.12em; letter-spacing: 0px;">지난 번에는 저희 팀 R&amp;D를 위해 프론트엔드 테스팅 툴을 조사해봤습니다.</span></span></p>
<p data-ke-size="size18">&nbsp;</p>
<p data-ke-size="size18"><span style="color: #333333;"><span style="font-size: 1.12em; letter-spacing: 0px;">이번에는 우리 팀에 적합한 차트 라이브러리는 무엇이 있을지 조사해보며 정리해봤습니다.</span></span></p>
<p data-ke-size="size18">&nbsp;</p>
<p data-ke-size="size18"><span style="font-size: 20.0704px;">저희 팀은 <span style="color: #009a87;"><b>Vue.js</b></span>&nbsp;프레임워크를 유지하기로 결정했으니, 이에 최적화되고 눈에 띄었던 차트 라이브러리들을 공유해보고자 합니다.</span></p>
<p data-ke-size="size18">&nbsp;</p>
<p style="color: #333333; text-align: start;" data-ke-size="size18">&nbsp;</p>
<p data-ke-size="size16">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<h2 id="️-렌더링-순서" style="background-color: #ffffff; color: #212529; text-align: start;" data-ke-size="size26">✍️<b><span><span> 차트 라이브러리 종류</span></span></b></h2>
<hr data-ke-type="horizontalRule" data-ke-style="style5" />
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><span><b>1) Chart.js</b></span></h3>
<p>[##_Image|kage@cMyWRK/btsGcNkFt8s/Tt07Si0DLLNMkdPkjB7jkk/img.jpg|CDM|1.3|{"originWidth":400,"originHeight":277,"style":"alignCenter","width":438,"height":303,"caption":"Chart.js","filename":"chart.js 로고.jpg"}_##]</p>
<h3 style="color: #555555;" data-ke-size="size23">&nbsp;</h3>
<p style="color: #555555;" data-ke-size="size18">먼저<span>&nbsp;</span><span style="color: #ef5369;"><b>Chart.js</b></span><span>&nbsp;</span>입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">Chart.js는 웹 상에 차트를 그리는데 특화된 라이브러리로,<span><span>&nbsp;</span></span><u><b>Canvas</b>를 이용한 라이브러리</u><span>&nbsp;</span>입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">Vue.js 프로젝트에서 가장 많이 쓰이는 라이브러리 1위로 알려져있고, 워낙 대중성이 높아 정보 활성화가 잘 되어 있습니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">현재 중량 모니터링 페이지에서 실시간 데이터를 보이기 위해 <b>라인 차트</b>를 사용 중입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 장점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;"><b><span style="color: #ee2323;">간단한 차트</span><span style="color: #ee2323;">를 표현하기에 편리함</span></b></li>
<li style="list-style-type: disc; color: #000000;"><span style="color: #ee2323;"><b>가벼움</b></span>(Highchart 보다 훨씬 가볍다고 함)</li>
<li style="list-style-type: disc; color: #000000;"><span style="color: #ee2323;"><b>러닝 커브(학습 곡선)가&nbsp;</b><b>낮음</b></span></li>
<li style="list-style-type: disc; color: #000000;"><span style="color: #000000; text-align: left;">많이 사용되기 때문에, 정보 활성화가 잘되어 있음</span><br /><br /></li>
</ul>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 단점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;">타입과 옵션이 많지 않음</li>
<li style="list-style-type: disc; color: #000000;">기본 옵션 외의 것들의 커스터마이징이 까다로움</li>
</ul>
<p data-ke-size="size16">&nbsp;</p>
<p style="color: #333333; text-align: start;" data-ke-size="size16"><b>※ 접속 링크</b></p>
<p data-ke-size="size16"><a title="https://www.chartjs.org/docs/latest/samples/information.html" href="https://www.chartjs.org/docs/latest/samples/information.html" target="_blank" rel="noopener">https://www.chartjs.org/docs/latest/samples/information.html</a></p>
<div style="color: #333333; text-align: start;">
<p style="color: #000000;" data-ke-size="size16">&nbsp;</p>
<p style="color: #000000;" data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><span><b>2) Apache ECharts</b></span></h3>
[##_Image|kage@dx8cnb/btsF9cUwg5P/dw1g8WObt36kKD1VMyt0TK/img.png|CDM|1.3|{"originWidth":758,"originHeight":881,"style":"alignCenter","width":258,"height":300,"caption":"Apache Echarts","filename":"echarts 로고.png"}_##]
<p style="color: #555555;" data-ke-size="size18">먼저<span>&nbsp;</span><span style="color: #6164c6;"><b>Apache Echarts</b></span><span>&nbsp;</span>입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">Apache에서 제작한 차트 라이브러리로 <u><b>Canvas</b>를 이용한 라이브러리</u><span>&nbsp;</span>입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">무료이면서, 설명이나 예제(Demo)가 다양하고 쉽게 정리되어 있습니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 장점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;"><b><span style="color: #ee2323;">데이터 처리에 강점을 보임</span></b></li>
<li style="list-style-type: disc; color: #000000;"><b><span style="color: #ee2323;">다크 모드, 차트 패턴과 같은 테마 기능을 제공</span></b></li>
<li style="list-style-type: disc; color: #000000;">다양한 차트 유형을 제공</li>
<li style="list-style-type: disc; color: #000000;">커스터마이징이 용이함<br /><br /></li>
</ul>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 단점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;">러닝 커브(학습 곡선)가 조금 높음</li>
<li style="list-style-type: disc; color: #000000;">버전업 주기가 빠름</li>
</ul>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16"><b>※ 접속 링크</b></p>
<p data-ke-size="size16"><a title="https://echarts.apache.org/examples/en/index.html" href="https://echarts.apache.org/examples/en/index.html" target="_blank" rel="noopener">https://echarts.apache.org/examples/en/index.html</a></p>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><span><b><span><b>3) Highcharts</b></span></b></span></h3>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
[##_Image|kage@cgqwKZ/btsGaYOhGs1/ITk8HWi49XU78dve5jSU2K/img.png|CDM|1.3|{"originWidth":440,"originHeight":180,"style":"alignCenter","caption":"Highcharts","filename":"Highcharts 로고.png"}_##]
<h3 style="color: #000000;" data-ke-size="size23">&nbsp;</h3>
<p style="color: #555555;" data-ke-size="size18">먼저<span>&nbsp;</span><span style="color: #009a87;"><b>Highcharts</b></span><span>&nbsp;</span>입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">프레임워크를 떠나서 웹에서 가장 널리 사용되는 차트 도구입니다.</p>
<p style="color: #555555;" data-ke-size="size18"><span>Higncharts는<span>&nbsp;</span></span><u><b>SVG</b></u><span><u>를 이용한 라이브러리</u><span>&nbsp;</span>입니다.</span></p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18"><span>현재 저희 프로젝트에서 가장 많이 사용하는 차트 라이브러리 입니다.</span></p>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 장점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;"><span style="color: #ee2323;"><b>러닝 커브(학습 곡선)가 낮음</b></span></li>
<li style="list-style-type: disc; color: #000000;"><span style="color: #ee2323;"><b>디자인이 이쁘고, 깔끔함</b></span></li>
<li style="list-style-type: disc; color: #000000;"><span style="color: #000000; text-align: left;">커스터마이징이 용이함</span> <br /><br /></li>
</ul>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 단점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;">무거움</li>
<li style="list-style-type: disc; color: #000000;"><span style="color: #000000; text-align: left;">상업용도는 유료이기 때문에 </span>무료 버전은 유형과 옵션이 상대적으로 많지 않음</li>
</ul>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16"><b>※ 접속 링크</b></p>
<p data-ke-size="size16"><a title="https://www.highcharts.com/demo?_gl=1*wn507y*_up*MQ..&amp;gclid=CjwKCAjw5ImwBhBtEiwAFHDZx32EXEia4w2M-UBR5SpdfuPIvQxcmdl_CrzB2SPiieoi5c_HQJwaxRoCM9UQAvD_BwE" href="https://www.highcharts.com/demo?_gl=1*wn507y*_up*MQ..&amp;gclid=CjwKCAjw5ImwBhBtEiwAFHDZx32EXEia4w2M-UBR5SpdfuPIvQxcmdl_CrzB2SPiieoi5c_HQJwaxRoCM9UQAvD_BwE" target="_blank" rel="noopener">https://www.highcharts.com/demo?_gl=1*wn507y*_up*MQ..&amp;gclid=CjwKCAjw5ImwBhBtEiwAFHDZx32EXEia4w2M-UBR5SpdfuPIvQxcmdl_CrzB2SPiieoi5c_HQJwaxRoCM9UQAvD_BwE</a></p>
<div style="color: #333333; text-align: start;">&nbsp;</div>
<div style="color: #333333; text-align: start;">&nbsp;</div>
<h3 style="color: #000000;" data-ke-size="size23"><span><b><span><b>4) ApexCharts</b></span></b></span></h3>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
[##_Image|kage@d46tn8/btsF94VNgte/uEPQ9nnFcVE2BWPkNLzehK/img.png|CDM|1.3|{"originWidth":177,"originHeight":177,"style":"alignCenter","width":235,"height":235,"caption":"ApexCharts","filename":"apexCharts 로고png.png"}_##]
<h3 style="color: #000000;" data-ke-size="size23">&nbsp;</h3>
<p style="color: #555555;" data-ke-size="size18">먼저<span>&nbsp;</span><span style="color: #0593d3;"><b>ApexCharts</b>&nbsp;</span>입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">다른 차트 라이브러리들과 달리 상대적으로 신생 라이브러리라고 합니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">오픈 소스이기 때문에 상용 어플리케이션에서 무료로 사용 가능합니다.</p>
<p style="color: #555555;" data-ke-size="size18"><span>ApexCharts는<span>&nbsp;</span></span><u><b>SVG</b></u><span><u>를 이용한 라이브러리</u><span>&nbsp;</span>입니다.</span></p>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 장점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;"><span style="color: #ee2323;"><b>러닝 커브(학습 곡선)가 낮음</b></span></li>
<li style="list-style-type: disc; color: #000000;"><span style="color: #ee2323;"><b>문서가 잘 정리되어 있고, UI는 깔끔하고, Interaction 부분이 세련되게 구성됨</b></span></li>
<li style="list-style-type: disc; color: #000000;">커스터마이징이 용이함<br /><br /></li>
</ul>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 단점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;">가볍진 않음(속도는 Highcharts와 다를게 없어보임)</li>
<li style="list-style-type: disc; color: #000000;">Highcharts에 비해 눈에 띄는 큰 장점이 없어보임</li>
</ul>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size16"><b>※ 접속 링크</b></p>
<p style="color: #555555;" data-ke-size="size16"><a title="https://apexcharts.com/javascript-chart-demos/" href="https://apexcharts.com/javascript-chart-demos/" target="_blank" rel="noopener">https://apexcharts.com/javascript-chart-demos/</a></p>
</div>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><span><b><span><b>5) AmCharts</b></span></b></span></h3>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<p>[##_Image|kage@olkzb/btsGctUf8FU/f2KY5K64S5Gn5cC7vBMCh0/img.png|CDM|1.3|{"originWidth":1000,"originHeight":558,"style":"alignCenter","width":396,"height":221,"caption":"AmCharts","filename":"amCharts.png"}_##]</p>
<p style="color: #555555;" data-ke-size="size18">먼저<span>&nbsp;</span><span style="color: #1a5490;"><b>AmCharts</b>&nbsp;</span>입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">데이터 시각화에 최적화된 고급 차트 라이브러리입니다.</p>
<p style="color: #555555;" data-ke-size="size18">&nbsp;</p>
<p style="color: #555555;" data-ke-size="size18">개발자라면 한번씩 사용해보고 싶은 라이브러리라고 합니다.</p>
<p style="color: #555555;" data-ke-size="size18"><span>AmCharts는<span>&nbsp;</span></span><u><b>SVG</b></u><span><u>를 이용한 라이브러리</u><span>&nbsp;</span>입니다.</span></p>
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 장점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;">차트 라이브러리 중 디자인이 가장 고급지고 깔끔함</li>
<li style="list-style-type: disc; color: #000000;">차트 기능 및 옵션이 많음</li>
<li style="list-style-type: disc; color: #000000;">최근 트렌드와 이슈에 맞는 테마를 적극적으로 업데이트 함</li>
</ul>
<h3 style="color: #000000;" data-ke-size="size23"><b>▶ 단점</b></h3>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li style="list-style-type: disc; color: #000000;">유료 라이센스(조건부 무료)</li>
<li style="list-style-type: disc; color: #000000;">무료 버전은 좌측 하단에 워터마크가 남음(신경 쓰일 정도는 아님)</li>
<li style="list-style-type: disc; color: #000000;">러닝 커브(학습 곡선)가 조금 높음</li>
</ul>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16"><b>※ 접속 링크</b></p>
<p data-ke-size="size16"><b><a title="https://www.amcharts.com/demos/" href="https://www.amcharts.com/demos/" target="_blank" rel="noopener">https://www.amcharts.com/demos/</a></b></p>
<p data-ke-size="size16"><br /><br /></p>
<h2 id="️-렌더링-순서" style="background-color: #ffffff; color: #212529; text-align: start;" data-ke-size="size26">✍️<b><span><span><span> 앞으로의 방향</span></span></span></b></h2>
<hr data-ke-style="style5" data-ke-type="horizontalRule" />
<p style="color: #555555;" data-ke-size="size16">&nbsp;</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16">조사해보니 정말 매력적인 차트 라이브러리가 많았습니다.</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16">&nbsp;</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16">차트 라이브러리를 선정하기 전, 팀 내부적으로 가장 고려해야 할 요소는 아래 2가지 입니다.</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16">&nbsp;</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16"><span style="color: #ef5369;"><b>1. 속도</b></span></p>
<p style="color: #555555; text-align: start;" data-ke-size="size16"><span style="color: #ef5369;"><b>2. 화면 깨짐</b></span></p>
<p style="color: #555555; text-align: start;" data-ke-size="size16">&nbsp;</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16"><span style="color: #ef5369;"><u><b>속도</b></u></span>는 중요합니다. 간혹 <span style="color: #555555; text-align: start;">대용량 데이터를 조회할 시, </span>차트 조회 속도가 느렸던 적도 있었습니다. 대용량 데이터 처리에 적합한 차트 라이브러리를 잘 선정하여 사용해보면 좋을 것 같습니다.</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16">&nbsp;</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16"><span style="color: #ef5369;"><u><b>화면 깨짐</b></u></span> 또한 사용자 입장에서 불편한 요소입니다. Canvas 차트가 이에 약점을 보이고 있는데, SVG 차트 라이브러리들과 적극적으로 비교해보고 테스트함으로써 선택하면 좋을 것 같습니다.</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16">&nbsp;</p>
<p style="color: #555555; text-align: start;" data-ke-size="size16">이번 R&amp;D 기간을 통해 팀 프로젝트에 적합한 차트 라이브러리를 잘 선정했으면 하는 바램입니다.</p>
