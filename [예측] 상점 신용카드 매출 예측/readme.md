# 1. 주제 : 상점 신용카드 매출 예측

- 2019.07 ~ 2019.10 에 DACON에서 주최한 상점 신용카드 매출 예측 경진대회의 데이터
- 데이터 제공자 : 핀테크 기업 FUNDA 


- 문제 : 2019년 2월 28일까지의 카드 거래 데이터를 이용해 2019년 3월 1일 ~ 5월 31일 까지의 상점별 3개월 총 매출 예측하기
---
# 2. 데이터 소개
[데이터 출처] : DACON(https://dacon.io/competitions/official/140472/data) 

funda_train.csv : 모델 학습용 데이터
- store_id : 상점의 고유id
- card_id : 사용한 카드의 고유 id
- card_company : 비식별화된 카드 회사
- transcated_date : 거래 날짜
- transacted_time : 거래 시간
- installment_term : 할부 개월 수 
- region : 상점이 위치한 지역
- type_of_business : 상점 업종
- amount : 거래액 (단위: 미상) 
