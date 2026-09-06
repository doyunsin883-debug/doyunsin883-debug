# Shin Do Yun · 신도윤

**Industrial Engineering, Gachon University**  
Manufacturing analytics · Quality engineering · Machine learning · Operations research

I study how data can support decisions in manufacturing systems—not only by predicting an outcome, but also by explaining process change and connecting model output to an operational choice.

## Core Research · 핵심 연구

### Risk-Aware Predictive Maintenance Decision Framework

> **SQC로 공정 이상을 찾고 → ML로 실제 고장위험을 추정하고 → 최적화로 실행 가능한 운전 후보를 탐색한 독립 연구**

| 핵심 저장소 | 역할 | 바로가기 |
|---|---|---|
| **Research Paper & Reading Guide** | 국·영 논문, 모바일 리더, 쉬운 해설, 핵심 결과와 연구 논리 | [Paper repository](https://github.com/doyunsin883-debug/risk-aware-predictive-maintenance-paper) |
| **Reproducible Analysis & Code** | EDA, I-MR SQC, 모델 비교, 임계값 선택, 보류 테스트, 제약 최적화 | [Code repository](https://github.com/doyunsin883-debug/risk-aware-predictive-maintenance) |

```text
AI4I 2020 data
      ↓
EDA & data audit
      ↓
SQC: Is the process different from its baseline?
      ↓
ML: Is the state likely to become an actual failure?
      ↓
Optimization: How should the machine be operated under constraints?
      ↓
Risk-aware maintenance decision
```

The paper repository explains **why the analysis is structured this way and what can responsibly be concluded**. The code repository shows **how each number, figure, and model artifact was produced**. Together they form one end-to-end research portfolio.

**Quick result:** the held-out Gradient Boosting model detected 21 of 29 failures (recall 0.7241, PR-AUC 0.7463). The study also reports an important negative result: binary SPC alarm flags added little predictive value once continuous process variables were already included, while remaining valuable for process interpretation and drift monitoring.

## About Me

I am an Industrial Engineering student interested in solving real-world problems with data, especially in manufacturing, quality engineering, SCM, and business analytics. I value analyses that preserve the boundary between evidence, interpretation, and operational recommendation.

## Interests

- Manufacturing AI and predictive maintenance
- Statistical quality and process control
- Machine learning for imbalanced events
- SCM and operations analytics
- Optimization and decision support
- Business intelligence and data visualization

## Tech Stack

- **Analysis:** Python, Pandas, NumPy, SciPy, Excel
- **Machine Learning:** scikit-learn, feature engineering, model evaluation
- **Visualization:** Matplotlib, Seaborn, Plotly, Streamlit
- **Data & Tools:** SQL, MySQL, Git, GitHub, VS Code

## Additional Projects

### LG DACON Quality Classification AI Project

Machine-learning project focused on manufacturing quality classification.

### Foreign Resident Dashboard

Interactive analysis of foreign-resident distribution by region and nationality.

### Seoul Subway Congestion Analysis

Exploratory analysis and visualization of urban transit congestion patterns.

## Current Goals

- Build rigorous, reproducible industrial-engineering portfolios
- Deepen Python, SQL, statistics, and machine-learning practice
- Participate in DACON and Kaggle competitions
- Prepare for SQLD and ADsP certifications
- Gain research and industry experience

## Contact

- Email: doyunsin883@gmail.com
- GitHub: [@doyunsin883-debug](https://github.com/doyunsin883-debug)
