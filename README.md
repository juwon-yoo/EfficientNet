# EfficientNet
EfficientNet_b0모델을 사용한 이미지 분류 모델 개발

-------
# 적용 방법
1. 데이터 하나의 크기가 (224, 224, 30)로 구성되어 이를 (224, 224, 3)크기의 10개 이미지로 분리
2. 위의 데이터로 모델 훈련
3. 테스트 데이터로 라벨 예측
4. 예측한 라벨을 10개씩 나누어 가장 예측 빈도가 높은 라벨로 결과 리스트에 저장
