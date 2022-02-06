# 번개장터 CTR(클릭율) 향상을 위한 신규 게시글 등록 가이드

## Overview
### 프로젝트 기간
2021년 12월 13일 ~ 2022년 1월 24일
### Team
|                            김동영                            |                            심태양                            |                            선명한                            |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| [![Avatar](https://avatars.githubusercontent.com/u/89237850?v=4)](https://github.com/dongyoung0) | [![Avatar](https://avatars.githubusercontent.com/u/89237873?v=4)](https://github.com/taeyang1224) | [![Avatar](https://avatars.githubusercontent.com/u/89237880?v=4)](https://github.com/Sunmyunghan) |
| [Github](https://github.com/dongyoung0) | [Github](https://github.com/taeyang1224) | [Github](https://github.com/Sunmyunghan) |

<<<<<<< HEAD
### Environments
`https://github.com/shenweichen/DeepCTR-Torch`

### 프로젝트 목적

### 파이프라인

![image](https://user-images.githubusercontent.com/89237850/151507927-8e9942b4-72b5-4b9e-a3d1-23b163eadcfd.png)

### CTR 예측 모델
####  LightGBM
####  DeepFM

### 결과


## Code Structure
```
├── notebooks/
│   ├── 데이터 수집 및 전처리/
│   │   ├── 전처리 및 병합.ipynb
│   │   ├── 신규 게시글 크롤링.ipynb
│   │   ├── image/
│   │   │       background_OpenCV.ipynb
│   │   │       image_background.ipynb
│   │   │       image2vec_practice.ipynb
│   │   │
│   │   └── text/
│   │           brand.txt
│   │           FastText.ipynb
│   │           train_text2vec.ipynb
│   │
│   ├── CTR Prediction/
│   │   ├── LightGBM/
│   │   ├── DeepFM/
│   │   └── CTR prediction.ipynb
│   │
│   ├── 특징 분석/
│   │       모델 비교 EDA.ipynb
│   │       정형 데이터 분석.ipynb
│   │       이미지 분석.ipynb
│   │       텍스트 분석.ipynb
│   │
│   ├── SQL.py
│   └── SQL_업로드.py
│
├── code/
│   ├── data/
│   │
│   ├── deepctr_torch/
│   │
│   ├── requirements.txt
│   ├── preprocess.py
│   ├── feature_extractor.py
│   ├── predictor.py
│   ├── app.py
│   └── README.md
│
├── documents
│   ├── 기획안
│   └── 발표자료
│
└── README.md
```


## Web demo
```
$ cd code
pip install -r requirements.txt
```

```
$ streamlit run app.py
```
=======
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
>>>>>>> fc1299c77f4743e1be549ecf7d7a287f070dfad0
