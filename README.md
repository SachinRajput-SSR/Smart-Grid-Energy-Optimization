# AI-Powered Smart Grid Energy Optimization

## Project Overview
This project aims to develop an intelligent system for predicting and optimizing the stability of smart electrical grids using machine learning (ML), deep learning (DL), and computer vision technologies. The system also incorporates cybersecurity anomaly detection to safeguard critical energy infrastructure.

The goal is to enhance energy efficiency, support renewable energy integration, and improve grid reliability through AI-driven analysis of power system data.

## Dataset
- The project uses the [Smart Grid Stability Dataset](https://www.kaggle.com/datasets/pcbreviglieri/smart-grid-stability) from Kaggle.
- The dataset contains simulated measurements of grid parameters (voltage, current, power flow, etc.) labeled with stability status (stable/unstable).

## Repository Structure
```
Smart-Grid-Energy-Optimization/
│
├── data/
│ ├── raw/ smart_grid_stability_augmented.csv
│
├── notebooks/
│ ├── 01_data_exploration.ipynb
│
├── README.md # Project overview and instructions
├── requirements.txt # Python dependencies
├── LICENSE # License information
```

### Features
- Uses real-world inspired Smart Grid Stability dataset
- Supervised learning (classification) with Random Forest and other models
- Supports data exploration, cleaning, feature engineering, model training, and evaluation
- Produces stability predictions and explains influential factors
- Promotes sustainability and cyber-physical resilience in smart grids

### Prerequisites
- Python 3.x
- Libraries: pandas, scikit-learn, matplotlib, seaborn, numpy
- Install required packages using:
  - pip install -r requirements.txt

## License
This project is licensed under the MIT License.

---
