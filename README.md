[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Tm6AYAOm)
# Title (Please modify the title)
## Team

| ![박패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![이패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![최패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![김패캠](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | 
|            [장재성](https://github.com/mirrbandi)             |            [이진영](https://github.com/jylee9018)             |            [임종현](https://github.com/LimJongHuyn)             |            [김주형](https://github.com/UpstageAILab)             |
|                            팀장, 담당 역할                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                           |

## 0. Overview
### Environment
- 주최측 제공 서버

### Requirements
astunparse==1.6.3
attrs==23.1.0
brotlipy==0.7.0
dnspython==2.4.2
expecttest==0.1.6
fsspec==2023.9.2
hypothesis==6.87.1
joblib==1.3.2
jsonpointer==2.1
matplotlib==3.8.2
mkl-service==2.4.0
nbformat==5.9.2
pandas==2.1.4
pathlib==1.0.1
plotly==5.18.0
pyarrow==14.0.2
python-dateutil==2.8.2
python-etcd==0.4.5
scikit-learn==1.3.2
scipy==1.11.4
sortedcontainers==2.4.0
threadpoolctl==3.2.0
triton==2.1.0
types-dataclasses==0.6.6
tzdata==2023.4 

## 1. Competiton Info

### Overview

- 

### Timeline

- 2024.10.02 - Start Date
- 2024.10.24 - Final submission deadline

## 2. Components

### Directory

- _Insert your directory structure_

e.g.
```
├── code
│   ├── jupyter_notebooks
│   │   └── model_train.ipynb
│   └── train.py
├── docs
│   ├── pdf
│   │   └── (Template) [패스트캠퍼스] Upstage AI Lab 1기_그룹 스터디 .pptx
│   └── paper
└── input
    └── data
        ├── eval
        └── train
```

## 3. Data descrption

### Dataset overview

- 학습 데이터에 대한 Histogram
![image](https://github.com/user-attachments/assets/024f5365-eb32-4773-be7b-f018e59317a9)


### EDA

- _Describe your EDA process and step-by-step conclusion_

### Data Processing

- _Describe data processing process (e.g. Data Labeling, Data Cleaning..)_

## 4. Modeling

### 장재성

- _Write model train and test process with capture_
  
### 이진영

- 오토인코더를 활용한 이상 탐지
    - 오토인코더의 주요 하이퍼파라미터 설정 (Optuna 활용)
        - Bottleneck(Hidden Layer)의 수, Latente Vector의 차원 수 등
    - 훈련 데이터의 모든 피처(총 52개)를 이용했으나 피처 선택이 주요
        - 상관계수는 피처 간의 관계를 나타내는 지표로서, 본 화학 공정 분야 특성상 피처 선택 기준으로 부적합할 수 있음
      
### 김주형

- _Write model train and test process with capture_

### 임종현

- _Write model train and test process with capture_

## 5. Result

### Leader Board

![image](https://github.com/user-attachments/assets/937ab830-2b28-40b8-9632-fc6ea43912b5)


### Presentation

-[presentaion file(pdf) link_](https://github.com/UpstageAILab3/upstage-ai-advanced-ad1-private/blob/main/%5B%ED%8C%A8%EC%8A%A4%ED%8A%B8%EC%BA%A0%ED%8D%BC%EC%8A%A4%5D%20Upstage%20AI%20Lab%203%EA%B8%B0_AD_%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C_1%EC%A1%B0.pdf)

## etc

### Meeting Log

- _Insert your meeting log link like Notion or Google Docs_

### Reference

- _Insert related reference_
