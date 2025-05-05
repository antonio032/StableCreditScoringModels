# Thesis Project: Stable Credit Scoring Models
This repository contains the source code, scripts, and relevant resources used in the research and development of our master's thesis: **"Stable Credit Scoring Models"** at KU Leuven.

This repository contains all code and resources developed for the master's thesis titled:  
**"Enhancing Stability in Credit Scoring Models: A Benchmarking Study"**  
Conducted as part of the Master of Science in Information Management, KU Leuven.

## 📄 Abstract
The application of classification models to credit scoring has been a major area of interest for both academics and professionals. Developing accurate, transparent, and interpretable models is essential for evaluating the creditworthiness of loan applicants. While high accuracy in default risk prediction is critical for financial institutions, maintaining model stability over time is equally important to ensure consistent and fair decision-making.

This project investigates credit scoring model benchmarking, with a particular focus on stability. It explores recent techniques and technological developments aimed at improving model stability without sacrificing predictive performance.

## 🔑 Keywords

Credit Scoring · Risk Modeling · Stable Models · Classification · Model Benchmarking

## 📁 Repository Structure
```
.
├── data/ # Preprocessed and sample data files
├── notebooks/ # Jupyter notebooks for EDA, training, and evaluation
├── src/ # Source code for data processing, model training, and evaluation
├── models/ # Saved models (if applicable)
├── results/ # Plots, evaluation metrics, and benchmarking results
├── requirements.txt # Python dependencies
└── README.md # Project overview
```

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/antonio032/StableCreditScoringModels.git
cd StableCreditScoringModels
```

2. **Set up the environment**
```
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. **Run the notebooks or scripts**
```
Open any .ipynb notebook in the notebooks/ folder to explore the experiments and results.
```

## Technologies Used
```
Python 3.10+
scikit-learn
pandas
NumPy
Matplotlib / Seaborn
XGBoost / LightGBM (if used)
Jupyter Notebook
```

## Results Summary
The project benchmarks various classification models (e.g., Logistic Regression, Decision Trees, Gradient Boosting) based on both predictive performance and temporal stability. Stability is evaluated using metrics such as population stability index (PSI), AUC drift, and performance consistency across time-based splits.

## 📚 Citation
If you use this repository or reference the research, please cite:

Bal, Kang & Tsai. Enhancing Stability in Credit Scoring Models: A Benchmarking Study. Master’s thesis, KU Leuven, 2025.


## 📫 Contact
For any questions or suggestions:

📧 beyzabbal0@gmail.com

📧 yu-xuan.kang@outlook.com

🔗 [LinkedIn Profile or Personal Website if applicable]
