<div><h1>Gangseo_BigData</h1></div>
2022 강서구 빅데이터 공모전 데이터셋 분석 코드
<br>
Python Colab 사용 및 Pycharm 사용
<br>
<h2>데이터 시각화 정보</h2>
<ol>
<li>WordCloud : 길고양이 기사 제목을 크롤링하여 단어구름 만들기</li>
<ul>
<li>WebCrawing.py : 네이버에서 뉴스를 크롤링해옴, 60건의 기사 제목 및 기사 본문 </li>
<li>WordCloud.ipynb : 명사만 추출하여 단어의 빈도 수를 확인하고 단어구름 생성 </li>
</ul><br>
<li>CCTV : CCTV가 많이 설치된 곳에 고양이 급식소 추가 설치</li>
	<ul>
		<li>강서구 CCTV 현황, 강서구 공원 데이터를 활용해 고양이 급식소 추가 설치 제안</li>
		<li>강서구 CCTV 현황 중 CCTV 용도가 공원 방범용인 데이터만 사용</li>
		<li>강서구의 공원 데이터 중 강서구에서 관리하는 공원 데이터만 사용</li>
		<li>두 데이터의 주소를 기반으로 우편번호를 크롤링하여 우편주소가 같은 곳은 고양이 급식소로 적합함</li>
		<li>고양이 급식소로 적합한 곳을 map에 표시</li>
	</ul><br>
<li>Building_Height : 건물 높이 확인해서 낮은 건물 Heat Map으로 표시 </li>
	<ul>
		<li>5층 이하의 주거용 건축물 개수 Heat Map으로 시각화</li>
		<li>강서구와 면적 크기, 인구 조건이 비슷한 강남, 서초, 송파구를 비교 대상으로 지정</li>
	</ul><br>
<li>TNR_Count : 강서구 TNR 고양이 등록 개체 수 타 구와 비교 </li>
  	<ul>
  		<li>동물보호관리시스템 길고양이 중성화사업(TNR) 관리 데이터 기준 최근<br>
    		5년간(2017~2021) 서울특별시 구별 고양이 TNR 완료 개체수 비교 </li>
	</ul>
</ol>
</div>
