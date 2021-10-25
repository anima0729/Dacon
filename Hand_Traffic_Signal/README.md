# Competition : Hand_Traffic_Signal_Classification <br>(2021 교통 수(手)신호 동작 인식 AI 경진대회)

[2021 교통 수(手)신호 동작 인식 AI 경진대회](https://www.dacon.io/competitions/official/235806/overview/description)

## Final Model
- EfficientNet-B0 (Inference Time과 Dataset의 양을 고려해 더 복잡한 모델을 사용하지는 않았습니다.)

## Data Preprocessing
- Image Crop
- Train Partial Image Set (Not All Train Data)
- Augmentation(ShiftScaleRotate, GaussianBlur, GaussianNoise, RandomGamma)

## Reference

[[BASELINE] VGG16을 이용한 교통수신호 예측](https://www.dacon.io/competitions/official/235806/codeshare/3365?page=1&dtype=recent)
- by. Dacon.MockingJay

[Key Point를 이용하여 손 동작 이미지만 크롭](https://www.dacon.io/competitions/official/235805/codeshare/3362?page=2&dtype=recent)
- by. 5252
