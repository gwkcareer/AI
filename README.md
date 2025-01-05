# AIModelTrainer
***다양한 AI 모델을 학습***시키고, 그 과정과 결과를 기록하며 실험을 진행하는 레포지토리입니다.

## 📖 목차
1. TravelRecommendationModel (여행지 추천 모델)

## 폴더 구조
project_name/
├── data/
│   ├── raw/           # 원천 데이터 (Raw Data)
│   ├── processed/     # 가공된 데이터 (Processed Data)
│   └── interim/       # 중간 처리 단계 데이터 (Intermediate Data, optional)
├── scripts/           # 데이터 처리 및 분석 스크립트
├── models/            # 학습된 모델 저장 디렉터리
├── notebooks/         # 분석 또는 실험용 Jupyter 노트북
├── README.md          # 프로젝트 설명 파일
└── requirements.txt   # 필요한 패키지 목록

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
