# MachineLearning

### 1. 군집화 분석 수행 

#### 1.1 데이터 수집

- 아래 data repository에서 원하는 dataset 선택 (단, 변수가 10개 이상, 그리고 실제 label이 있는 데이터 선정)

- https://archive.ics.uci.edu/ml/datasets.php -> 데이터에 대해서 이해한대로 설명

#### 1.2 전처리

- 범주형 변수(categorical variable)는 적절한 변환 처리 필요

- 필요에 따라 스케일링(Scaling), 정규화(Normalization) 수행


#### 1.3 군집화 분석

- K-Means, Hierarchical clustering, DBSCAN 등 학습한 군집화 분석을 수행

- hyperparameter tuning도 수행

- 군집화 적용 결과비교: metric(silhouette score 등) 기반으로 군집 결과

#### 1.4 군집 결과 분석 및 가시화

- 군집화 분석 결과가 적당했는지, 실제 레이블을 기준으로 평가

- PCA 같은 차원축소 등을 통해 2차원 상에 가시화
          
<br>

### 2. 의사결정나무 분석 수행

#### 2.1 (데이터 수집 및 전처리)

- 아래 data repository에서 원하는 dataset 선택 (단, 변수가 15개 이상, 그리고 실제 label이 있는 데이터 선정)

- https://archive.ics.uci.edu/ml/datasets.php -> 데이터에 대해서 이해한대로 설명

- 변수의 타입을 변환 처리 하지 않고 그대로 둘 것

- 해당 데이터에 각 3~5% 씩 결측치(0이 아닌 NaN 의미)와 이상치(극단값) 생성



#### 2.2 의사결정나무 구축 및 실험비교

- 의사결정나무를 구축하고, 가지치기(pruning phase)를 적용하기 전/후 실험결과를 비교

#### 2.3 의사결정나무 학습모델 가시화 및 설명 
    
- 의사결정나무를 graphviz를 이용해 가시화 하고, 해당 diagram을 다양하게 해석
        
#### 2.4 의사결정나무의 특징 코멘트

- 의사결정나무의 특징에 대해서 기술