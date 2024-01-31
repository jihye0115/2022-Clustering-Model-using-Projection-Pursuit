# 2022-Clustering-model-using-Projection-Pursuit

### 📰 [논문 바로가기](https://dspace.ewha.ac.kr/handle/2015.oak/264320?mode=full) 

### 이화여대 통계학 석사 학위 논문 
- Paper 스터디 : 2022.01 ~
- 모델 : Projection Pursuit (사영 추적)
- Tool : R 
- 관련 Skill : 차원축소, Clustering

<br> </br>
💡 주제 <br>
차원축소 방법론인 Projection Pursuit(PP)을 이용하여 고차원 데이터를 원하는 정보를 담고있는 방향의 저차원으로 투영시켜가며, 반복적으로 클러스터링하는 기법을 제안한다.

💡 제안 모형 <br>
1. 사영 : 고차원 데이터를 원하는 사영 추적 지수를 사용하여 최적 방향으로 사영
2. 군집화 : 사영된 데이터의 분포를 추정하고, 최소인 지점을 기준으로 데이터 분리
3. 반복 : 원하는 군집 개수가 될 때까지 사영 및 군집화 과정을 반복

💡 강점 <br>
- Projection Pursuit은 Index를 통해 원하는 정보를 정의하여, 의도에 따라 다양한 방향으로 클러스터링 가능
- 실제 그룹 정보를 학습에 사용하지 않았음에도 일부 데이터에서는 랜덤포레스트보다 더 높은 정확도를 보임
- 최적 사영 벡터의 계수를 통해 중요 변수 파악 가능
- 변수의 선형 결합 (최적 사영 벡터) 식이 곧 군집을 나누는 기준이 되어, 해석 가능


### Poster
![Poster  Clustering-Model-using-Projection-Pursuit](https://github.com/jihye0115/2022-Clustering-Model-using-Projection-Pursuit/assets/77092027/fe7069d7-361d-45f2-b208-dd293175e7c1)

