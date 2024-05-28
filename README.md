# 2024DT_team5
## 분석 배경
### 기존 예측의 한계
현재 경마 경기 예측은 전문가의 경험과 직관에 주로 의존하고 있어, 
데이터 분석 기반의 과학적 예측 모델이 필요한 상황입니다.
### 경마 경기 자체의 관심 유발
야구와 같이 예측 모델을 만들어 경기 관람에서 상황별 예측치를 제공하여
경마 경기자체의 대중의 관심을 유도
## 분석 목적
### 예측 정확도 향상
기존의 전문가 예측 방식보다 데이터 분석 기반의 모델을 통해 경기 결과를 더 정확하게 예측하는 것이 주요 목적입니다. 이를 통해 경마장 운영자와 베팅 참여자 모두에게 도움이 될 수 있습니다.
### 영향요인 분석
다양한 데이터를 활용하여 경마 경기 결과에 영향을 미치는 주요 요인들을 파악하고자 합니다. 이를 통해 경마 산업 관계자들이 보다 과학적으로 의사결정을 내릴 수 있도록 지원합니다.
### 의사결정 지원
분석 결과를 바탕으로 경마 관련 의사결정을 지원할 수 있는 시스템을 개발하는 것이 목표입니다. 경마장 운영자와 베팅 참여자들이 실제 경기에서 활용할 수 있는 실용적인 도구를 제공하고자 합니다.

## 사용된 라이브러리
```python
import pandas as pd
from datetime import datetime
from sklearn.model_selection import train_test_split
import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns
from sklearn.preprocessing import StandardScaler
from statsmodels.stats.outliers_influence import variance_inflation_factor
from sklearn.linear_model import Ridge, Lasso, LinearRegression
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_squared_error, r2_score
```

## 데이터 분석
### 전처리
1. [1 (1)변수추출_결측치처리.ipynb](./1%20(1)%EB%B3%80%EC%88%98%EC%B6%94%EC%B6%9C_%EA%B2%B0%EC%B8%A1%EC%B9%98%EC%B2%98%EB%A6%AC.ipynb)


