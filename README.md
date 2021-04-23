# [P Stage 2] 정형 데이터 분류
![stage2](https://user-images.githubusercontent.com/71882533/115874316-e8975b00-a47e-11eb-8a75-70557f25469d.png)

## 개요
- 2021.04.12(월) ~ 04.22(목) 23:59
- 5914명의 2009년 11월 ~ 2011년 11월 데이터를 이용하여 각 고객들의 2011년 12월의 총 구매액이 300 달러(약 337,553 원)을 넘을 확률값을 예측한다.
- 고객들의 미래 소비를 예측하여 고객들에게 프로모션을 통해 성공적인 마케팅을 한다.

## 데이터 컬럼
- order_id : 주문 번호. 데이터에서 같은 주문번호는 동일 주문을 나타냄
- product_id : 상품 번호
- description : 상품 설명
- quantity : 상품 주문 수량
- order_date : 주문 일자
- price : 상품 가격
- customer_id : 고객 번호
- country : 고객 거주 국가
- total : 총 구매액(quantity X price)