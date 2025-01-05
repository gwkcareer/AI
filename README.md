# AIModelTrainer
***다양한 AI 모델을 학습***시키고, 그 과정과 결과를 기록하며 실험을 진행하는 레포지토리입니다.

## 📖 목차
1. TravelRecommendationModel (여행지 추천 모델)
```
project_name/
├── **data/**               # 데이터 관련 디렉터리
│   ├── raw/                # 원천 데이터 (Raw Data)
│   ├── processed/          # 가공된 데이터 (Processed Data)
│   └── interim/            # 중간 처리 데이터 (Intermediate Data, 선택 사항)
├── **scripts/**            # 데이터 처리 및 분석 코드
├── **models/**             # 학습된 모델 저장소
├── **notebooks/**          # Jupyter 노트북 (분석/실험용)
├── **README.md**           # 프로젝트 설명 파일
└── **requirements.txt**    # 필요 패키지 리스트
```
---

### 📁 data/
- **raw/**: 원천 데이터를 저장합니다. (예: CSV, JSON, 이미지 등)
- **processed/**: 전처리 및 가공된 데이터를 저장합니다. (예: train/test/validation 데이터셋)
- **interim/**: 중간 처리 단계의 데이터를 저장합니다. (선택 사항)

---

### 📁 scripts/
- 데이터 전처리 및 분석 스크립트를 저장합니다.
- 예시: `data_preprocessing.py`, `feature_engineering.py`

---

### 📁 models/
- 학습된 모델을 저장합니다.
- 예: `TravelRecommendationModel.pt`

---

### 📁 notebooks/
- Jupyter Notebook 파일을 저장합니다.
- 예: `exploration.ipynb`

---

### 📋 requirements.txt
- 프로젝트에 필요한 Python 패키지 목록을 명시합니다.

---
