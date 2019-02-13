# 2019 6th D2 CampusFest Image Clustering (지정주제)
## 00. 지정주제 개요
```
- 다수의 비분류된 상품 이미지들을 대상으로 Unsupervised Clustering 작업 수행
- 상품 이미지들의 특징을 추출하고 클러스터링 정확도를 올리는 것이 최종 목표 
- 최종 테스트에서는 Cluster number 또한 예측 
```
![샘플 이미지](./wiki/img-sample.png)

(참고: 네이버의 대회 참가용 이미지 공유 정책에 따라 실제 테스트 데이터 이미지는 본 github에 공유하지 않았습니다.)
 
&nbsp;
## 01. Base line code 분석
![베이스 코드분석 이미지](./doc/fig_1.png)
 
&nbsp;
## 02. New Clustering model 
>### 02.0 Model Architecture Concept
![Model Architecture Concept](./doc/fig_2-1.png)

&nbsp;
>### 02.1 True label making
- make_lables_true.py

&nbsp;
>### 02.2 Feature vectorizing network fine tuning (결승전까지 비공개)
- Feature_network_fine_tunig .py
- Using a feature vectorizing model
- Image augmentation + Fine-tunning a network

&nbsp;
>### 02.3 Feature extraction (결승전까지 비공개)
- Feature extraction using fine tuned network model 

&nbsp;
>### 02.4 Clustering
- Another clustering model (결승전까지 비공개)

&nbsp;
>### 02.5 Evaluation
- evaluation.py

&nbsp;
>### 02.6 Visualization

