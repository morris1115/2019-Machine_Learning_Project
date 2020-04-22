# 2019-Machine_Learning_Project
## 2019년 2학기 머신러닝 프로젝트 팔표자료
* 프로젝트 설명
  * 제조사 별 중고차 가격 예측 프로그램
      * 제조사 및 연식 운행거리등의 6019의 rows와 14의 columns 구성된 train data set과 1234개의 rows와 13개의 columns로 구성된 test data set을 활용한다.
      -------
      * 프로젝트 발표의 순서 
      1) 데이터 설명 
      2) 데이터 정제 
      3) 데이터 시각화 
      4) 모델 선택 및 예측으로 구성한다.
      * 데이터 정제
      1) 불필요한 값 제거를 한다. 단지 데이터 리스트의 번호는 기계학습을 시키는데에 불필요하므로 제거한다.
      2) 빠진값을 채운다. data set을 잘 살펴보면 빠진값이 존재한다. 이를 전체 데이터셋의 중간값으로 대체한다.
      3) One-Hot-Encoding 한다. 원핫인코딩을 통해 1과 0으로 변환한다.
      
      * 데이터 시각화 - 히토그램및 그래프로 정제된 데이터를 시각화한다.
      
      * 모델 선택 및 예측
      1) LinearRegression
      2) DecisionTreeRegressor
      3) RandomForestRegressor
