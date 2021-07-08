# sns_crawling

## 수집 목적 
다양한 채널의 sns을 수집하여 텍스트 분석의 Row Data를 확보하고자 한다.
추후에는 이를 활용한 키워드 분석, 주제 분석 등 
데이터를 활용한 마케팅 및 사업 기획,운영에 인사이트를 제공할 수 있는 로직으로 구현할 예정임. 
<br>

## <span style="color:red"> 1. Naver_Blog_Crawling </span> 

### 원하시는 키워드를 입력하시면, 해당 키워드가 속한 
### 내용의 네이버 블로그의 제목, 내용. 날짜를 크롤링할 수 있습니다. 


<br>
<br>

## 🐱‍🏍Process 

 Selenium을 활용하여 크롤링을 진행했으며, sleep 내 인자의 숫자를 랜덤으로 지정하여 

봇으로 인지할 수 있는 확률을 줄였습니다. 
개인적으로 1400여건 정도 수집하여 데이터 분석에 활용했으며,
그 이상의 데이터 또한 수집이 가능합니다. 

##### *크롤링의 기준은 정확도순이 아닌 최신순입니다. 

<br>
<br>
<br>

##  2. Tweeter_Crawling
### 원하시는 키워드를 입력하시면, 해당 키워드가 속한 
### 내용 트위터 내용과 날짜를 크롤링 하실 수 있습니다.
#### 해당 크롤링은 API를 활용하는 것이 아닌 Selenium을 활용한 크롤링입니다. 

<br>
<br>

## 🐱‍🏍Process 

Selenium을 활용하여 크롤링을 진행했으며, sleep 내 인자의 숫자를 랜덤으로 지정하여 

봇으로 인지할 수 있는 확률을 줄였습니다. 

무한 스크롤 방식으로 수집하며, 수집 기준은 Top 순이 아닌 최신 기준입니다.


##### *해당 프로세스를 만드는데 참고가 됐던 ICHI.PRO님과 Xeros.Lab님께 감사드립니다 :) 

<br>
<br>
<br>

##  3. Insta_Crawling
### 원하시는 키워드를 입력하시면, 해당 키워드가 속한 
### 내용 인스타 피드의 내용을 크롤링하실 수 있습니다. 


<br>
<br>

## 🐱‍🏍Process 

Selenium을 활용하여 크롤링을 진행했으며, sleep 내 인자의 숫자를 랜덤으로 지정하여 

봇으로 인지할 수 있는 확률을 줄였습니다. 

토르 브라우저를 설치하여 IP를 우회하여 진행했습니다. 

##### *해당 프로세스를 만드는데 참고가 됐던 솜씨좋은 님께 감사드립니다 :) 
