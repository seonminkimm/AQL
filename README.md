# multivariate time-series datasets of Air Quality Index (AQI)


AQI는 대기 중 공기 오염 수준을 측정하고 보고하는 프로세스를 나타내며 314 대기질 모니터링, 도시 계획 및 환경 보호에 중요한 역할을 합니다. 

AQI는 일반적으로 대기 중 주요 오염 물질에 의해 결정되며 미세먼지(PM2.5, PM10), 오존(O3), 이산화질소(NO2), 일산화탄소(CO) 등을 포함합니다. 

이는 대기 중 오염 물질 농도를 측정하고 이 정보를 하나의 숫자로 표현하여 대기질 상태를 표준화된 방법으로 보고하는데 사용됩니다. 일반적으로 0에서 500 사이의 범위에서 표시되며, 높은 값은 더 나쁜 대기질을 나타냅니다. 

 해당 데이터는 각각의 중국의 302개 도시에 군화된 2,296개의 항공 328 품질 모니터링 스테이션에서 수집된 데이터 중 중국의 3개 도시, 베이징, 텐진, 홍콩에서 파생되었습니다.

2014년 3월부터 2015년 4월까지 대기오염의 한 요소인 PM2.5 pollution을 포함하여 시간별로 수집되었습니다. Figure 3은 이러한 모니터링 stations의 지리적 분포를 보여주며, 각 아이콘은 stations을 나타냅니다.


<p align="center">
<img src=".\img\AQL_Sensor.png" height = "250" alt="" align=center />
<br><br>
Sources of air quality stations.
</p>

<p align="center">
<img src=".\img\table1.png" height = "250" alt="" align=center />
<br><br>
<b>Table 1<b>summary of our datasets: AQI-36, 313 AQI-27 and AQI-15.
</p>
 
변수에는 관측 타임스탬프 데이터, 즉 관측 월과 주가 포함됩니다. 베이징 시에는 36개의 모니터링 스테이션이 있어 AQI-36을 구성합니다. 마찬가지로 AQI-15와 AQI-27은 각각 홍콩과 텐진시의 15개 및 27개 모니터링 스테이션에서 수집됩니다. 3개의 대기 질 데이터 세트는 각각 8,760개의 동일한 인스턴스 수를 공유하며 AQI-15, AQI-27 및 AQI-36 데이터 세트의 경우 무작위로 누락된 값 비율이 각각 18.72%, 20.84%, 13.25%입니다.
