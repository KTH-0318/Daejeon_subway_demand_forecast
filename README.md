# Daejeon_subway_demand_forecast

대전 1호선 스마트카드 승하차 데이터에 상가·아파트·버스노선·기온 등 외부 공간변수를
**400m 버퍼로 결합**하고, 로그변환·시간가중치 전처리 후
**XGBoost·LightGBM 앙상블**로 역별·시간대별 수요를 예측.

`Python` `pandas` `GeoPandas` `XGBoost` `LightGBM`
