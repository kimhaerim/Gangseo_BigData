<div><h1>Gangseo_BigData</h1></div>
2022 강서구 빅데이터 공모전 데이터셋 분석 코드
<br>
Python Colab 사용 및 Pycharm 사용 <br>
사용 라이브러리, 모듈, 패키지 : BeautifulSoup, Request, Konlpy, collection, Wordcloud, pandas, numpy, matplotlib, seborn, folium
<br>
<h2>데이터 시각화 정보</h2>
<ol>
<li>길고양이 문제의 화제성</li>
	<ul>
		<li>사용 라이브러리, 모듈, 패키지 : </li>
		<li>WebCrawing.py : 네이버에서 뉴스를 크롤링해옴, 60건의 기사 제목 및 기사 본문 </li>
		<li>WordCloud.ipynb : 명사만 추출하여 단어의 빈도 수를 확인하고 단어구름 생성 </li>
		</ul><br>
		![cat_WordCloud](https://user-images.githubusercontent.com/71517226/159154716-c5f1891a-023c-4ae3-a4c2-f0f82b61d97e.png)
		<br>
		<br>
	
<li>강서구 주거용 건축물(저층) 분포도 분석</li>
	
	<ul>
		<li>5층 이하의 주거용 건축물 개수 Heat Map으로 시각화</li>
		<li>강서구와 면적 크기, 인구 조건이 비슷한 강남, 서초, 송파구를 비교 대상으로 지정</li>
	</ul><br>
	![송파구 지역별 주거용 건축물 층 별 분포도](https://user-images.githubusercontent.com/71517226/159155170-a066e9f3-f6b7-4aed-b92e-76404d461822.png)
	![서초구 지역별 주거용 건축물 층 별 분포도](https://user-images.githubusercontent.com/71517226/159155173-d1189e83-cd7c-4261-a62b-83d237f8178c.png)
	![강남구 지역별 주거용 건축물 층 별 분포도](https://user-images.githubusercontent.com/71517226/159155174-2bced40c-cd5d-4d21-9278-70a3b0f094f9.png)
	![강서구 지역별 주거용 건축물 층 별 분포도](https://user-images.githubusercontent.com/71517226/159155176-7382fbb9-9895-40dd-bb6d-bb3709dc491f.png)
<br><br>
	
<li>강서구의 고양이 개체 조절 및 TNR 사업 현황</li>
  	<ul>
  		<li>동물보호관리시스템 길고양이 중성화사업(TNR) 관리 데이터 기준 최근<br>
    		5년간(2017~2021) 서울특별시 구별 고양이 TNR 완료 개체수 비교 </li>
	</ul>
	<br>
	![자치구별 면적 대비 TNR 시행 횟수(scatter)](https://user-images.githubusercontent.com/71517226/159155146-f963c123-6179-495a-b54d-df9b98e8ab8c.png)
	![2017~2021서울시 TNR 시행 건 수 강서, 송파, 강남, 서초](https://user-images.githubusercontent.com/71517226/159155147-aadacb10-50c0-4329-9d13-c40b260e4524.png)
	![2017~2021서울시 TNR 시행 건 수 최상위와 최하위 구 비교](https://user-images.githubusercontent.com/71517226/159155148-4577ffd6-a3c3-41d2-8803-c4cb33f430c8.png)
	![2017~2021서울시 TNR 시행 건 수 상위 5개 구 비교](https://user-images.githubusercontent.com/71517226/159155149-73a3938d-2eea-4b08-b498-9e44e37340f5.png)
	![2017~2021서울시 TNR 시행 건 수 하위 5개 구 비교](https://user-images.githubusercontent.com/71517226/159155152-bf29c8a5-5550-4910-868d-42d616d367fb.png)

<br><br>
<li>새로운 정책 제안을 위한 길고양이 급식소 자리 선정 CCTV 분석</li>
	<ul>
		<li>강서구 CCTV 현황, 강서구 공원 데이터를 활용해 고양이 급식소 추가 설치 제안</li>
		<li>강서구 CCTV 현황 중 CCTV 용도가 공원 방범용인 데이터만 사용</li>
		<li>강서구의 공원 데이터 중 강서구청에서 관리하는 공원 데이터만 사용</li>
		<li>두 데이터의 주소를 기반으로 우편번호를 크롤링하여 우편주소가 같은 곳은 고양이 급식소로 적합함</li>
		<li>고양이 급식소로 적합한 곳을 map에 표시</li>
	</ul><br>

![CCTV지도](https://user-images.githubusercontent.com/71517226/159154735-fcd28a43-b6aa-4ccd-8c94-9db2761e56ab.jpeg)
<br>
<br>
</ol>
</div>
