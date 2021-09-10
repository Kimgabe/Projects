## 케글 필사 (House Prices - Advanced Regression Techniques)

### 추후 참조하면 좋은 내용
- matplotlib + seabron으로 시각화 하기 (jointplot)
- 종속변수 시각화(histplot)에 평균선 넣기
- cv fold 함수 만들기
- 모델에 가중치 부여해서 blending 하기

### 전처리
- 이상치 제거
- 종속변수(Sale Price) 로그화
- 결측치 처리
- 문자열 결측치 처리
- 왜도 처리
- 도출변수 추가
  - 면적 관련
  - 연도 관련
- 더미 변수 만들기

### 모델링
- cv fold 검증
- MAE, MSE, RMSE 함수화
- 모델별 RMSE 시각화
- 기본 모델링 기반 blending 및 시각화


### 제출 결과
![image](https://user-images.githubusercontent.com/74717033/132900295-f1d04a9e-d143-4860-9c5a-37a8a3bc1c57.png)
