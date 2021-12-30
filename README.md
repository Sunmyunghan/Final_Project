# Final_Project

## 팀원
- 김동영, 선명한, 심태양

## 프로젝트 소개
- 주제: 번개장터 데이터를 활용한 머신러닝 프로젝트
- 작업환경: Colab, Git-hub, Jupyter-Notebook
- 사용언어: python
- 세부사항은 introduce.md 확인


## Code Structure
```text
├── 0.crawling_bunjang 
│   ├── ad_content_crawling.ipynb
│   ├── advertiser_title 크롤링(21.12.15).ipynb
│   └── crawling.md
│ 
├── 1.processing_code
│   ├── age_ch_processing.ipynb
│   ├── b_pay_rate_processing.ipynb
│   ├── EDA_category-emergency(21.12.16).ipynb
│   ├── image_to_feature.ipynb
│   ├── merge_data.ipynb
│   ├── place.py
│   ├── 전처리_및_병합.py
│   └── processing.md
│
├── 2.model_code                  
│   ├── deepctr_torch
│   │   │
│   │   ├── layers
│   │   │   ├── __init__.py
│   │   │   ├── activation.py
│   │   │   ├── core.py
│   │   │   ├── interaction.py
│   │   │   ├── sequence.py
│   │   │   └── utils.py
│   │   │
│   │   ├── models
│   │   │   ├── __init__.py
│   │   │   ├── basemodel.py
│   │   │   └── deepfm.py
│   │   │
│   │   ├── __init__.py
│   │   ├── callbacks.py
│   │   ├── inputs.py
│   │   └── utils.py
│   │
│   ├── lgb_model
│   │    └── grid_100_result.csv
│   │   
│   ├── DeepFM(예시).ipynb
│   ├── DeepFM_1227_동영.ipynb
│   ├── DeepFM_태양.ipynb
│   ├── LightGBM(예시).ipynb
│   ├── LightGBM_display.ipynb
│   └── Model.md
│
├── documents
│   └── documents.md
│
├── img
│
├── .gitignore
├── DeepFM_동영.ipynb
├── introduce.md
├── LICENSE
└── README.md
