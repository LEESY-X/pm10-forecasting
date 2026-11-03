# PM10 Forecasting

PM10 예측 오차가 급변 구간에서 커지는지 확인하고, 추가 피처와 모델 변경의 효과를 비교한 AI+X 중급 프로젝트입니다.

| 노트북 | 내용 |
| --- | --- |
| [01-feature-engineering](01-feature-engineering.ipynb) | 동일 조건에서 추가 피처의 효과 비교 |
| [02-error-analysis](02-error-analysis.ipynb) | 급변 구간 오차와 예측값 집계 방식 검증 |
| [03-model-comparison](03-model-comparison.ipynb) | PM10·PM2.5를 입력 피처에서 제외한 모델 비교 |

## 실행

Python과 Jupyter가 필요합니다. NumPy, pandas, SciPy, scikit-learn, Matplotlib, joblib을 설치한 뒤, 실험별로 필요한 데이터와 모델 경로를 설정합니다. 입력 데이터와 기존 모델은 프로젝트에서 별도로 준비해야 합니다.

세 번째 노트북은 설치된 경우 XGBoost, LightGBM, CatBoost와 Optuna를 사용합니다.
