/model/xgb_final_0818.ipynb  

모델 A : 개별 건물별 학습 진행 (Type 1 : base_1 feature)
- 100개의 건물에 대해서 100개의 모델이 학습

모델 B: 개별 건물별 학습 진행 (Type 1 : base_1 feature + detail_1)
- 100개의 건물에 대해서 100개의 모델이 학습

모델 C: 전체 데이터로 학습 진행 (Type 2 : base_2 feature + detail_2)
- 100개의 건물에 대해서 1개의 모델이 학습

모델 D: 전체 데이터로 학습 진행 (Type 2 : base_2 feature + detail_2)
- 100개의 건물에 대해서 1개의 모델이 학습

모델 A, B, C, D의 결과를 단순 평균 앙상블하여 최종 예측값을 도출