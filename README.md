# sentiment_analysis

https://dacon.io/competitions/official/235914/overview/schedule

제 1회 KRX 금융 빅데이터 활용 아이디어 경진대회 참여

- 개발 프로세스
 
  * 크롤링을 통한 자연어 데이터 수집
  * 수집 데이터 전처리
  * 감정 분석을 위한 자연어 분석모델 개발
  * 감정 데이터에 따른 주가 변화량 분석 및 예측 모델 개발
  * 모델 성능 비교 분석 및 평가
  * 최종 모델 도출

- 아이디어 제안 배경 및 목적
  - 배경
    * 주가를 잘 예측할 수 없을까. 더 주가변동에 flexible한 정보를 넣으면 더 잘 예측 하지않을까
    * 사람들이 많이 보는 정보를 가지고 오면 더 주가를 잘 예측하지 않을까

  - 목적
    * 금융 뉴스 및 주식관련 SNS 감성 분석을 통해 주가 변화를 분석하고, 이를 기반으로 주가 예측 모델 개발
    * 주가 예측 모델 개발을 통해 금융시장 참여자들에게 유용한 정보를 제공할수 있도록 함

- 활용 데이터

  - 자연어 데이터: 네이버 및 다음 증권분류 뉴스 기사, 종목 토론방, 유튜브
  - 기업 및 주가 데이터 : KRX 종목정보 및 거래 실적

- 모델 설명

  - [Model 1] SP based Logistic Regression
  - [Model 2] SP based LSTM (binary)
  - [Model 3] SP based KlueBERT
  - [Model 4] SP based LSTM (multi)
  - [Model 5] Word based Logistic Regression
  - [Model 6] Word based LSTM
  - [Model 7] Word based KlueBERT
  - [Model 8] Customized Sentimental Dict based LSTM
  - [Model 9] Customized Sentimental Dict based Logistic Regression
  - [Model 10] Customized Sentimental Dict based KR-FinBERT
