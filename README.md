# Bigdata_2021_2_class

## 2021년 2학기 빅데이터 분석 수업


### 2 week
* 서울특별시교육청 공공도서관 소장도서 API를 출력하기
  - 파이썬을 검색해서 20건 출력 

### 3 week
* 문제 1 :오픈API를 통해 데이터를 5천 ~ 1만 건 정도 수집해서 파일로 저장
  - !dir 명령어로 출력
* 문제 2 : 노트북에서 pyspark 실행
  - 직접 설치
* 문제 3 : 파일을 읽어서 RDD를 생성하고, 5줄을 화면출력
  - 경기도 의정부시 인구현황 (파일명: ```경기도 의정부시_인구현황_20200904```) https://www.data.go.kr/data/15009613/fileData.do
  - 제주특별자치도 서귀포시 내 연도별 65세이상 인구수 및 고령화비율, 노령화지수 현황 (파일명: ```제주특별자치도 서귀포시_고령화비율및노령화지수현황_20200623```) https://www.data.go.kr/data/15051545/fileData.do

### 4 week
* 강의자료 "ds3_spark_rdd.ipynb"의 'ds_bigdata_wiki.txt'을 저장하고 RDD를 사용하여 word count를 계산하기
  - 단어 빈도수를 내림차순으로 정하여 15개 출력

### 5 week
```
이름 | 과목 | 점수
김하나 | English | 100
김하나 | Math | 80
임하나 | English | 70
임하나 | Math | 100
김갑돌 | English | 82.3
김갑돌 | Math | 98.5

* 문제 3-1: 이름으로 합계를 구해보자. 올바른 출력은 다음과 같다.
'임하나' 170.0
'김하나' 180.0
'김갑돌' 180.8

* 문제 3-2: 과목으로 합계를 계산해 보자. 출력은 다음과 같이 나와야 한다.
'English' 252.3
'Math' 278.5

* 문제 3-3: 이름으로 합계과 개수를 구해보자. 출력은 다음과 같이 계산된다.
'임하나' (170.0, 2)
'김하나' (180.0, 2)
'김갑돌' (180.8, 2)

* 문제 3-4: 이름으로 평균을 계산해 보자. 앞서 3-3에서 사용했던 결과를 활용하고, 올바른 출력은 다음과 같다.
'임하나' 85.0
'김하나' 90.0
'김갑돌' 90.4
```
