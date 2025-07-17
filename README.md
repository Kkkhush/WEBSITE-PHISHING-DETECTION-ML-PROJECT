# 📡 Phishing Website Detection using ML Algorithms

This project aims to detect phishing websites using a machine learning-based approach. By leveraging multiple ML models—Decision Tree, Random Forest, XGBoost, and Support Vector Machine—we predict whether a website is legitimate or malicious based on extracted features from a phishing dataset.

---

## 📁 Dataset

- **Source**: Local CSV file (`dataset2.csv`)  
- **Shape**: Multiple features including URL-based indicators and a binary `phishing` label  
- **Cleaning**:
  - Removed duplicates
  - Encoded target label
  - Handled null values

---

## 📊 Exploratory Data Analysis

- Visualized feature distributions using histograms
- Checked label balance
- Correlation matrix plotted for feature importance

---

## 🧠 Models Implemented

| Model             | Train Accuracy | Test Accuracy |
|------------------|----------------|---------------|
| Decision Tree     | 93.1%          | 70.3%         |
| Random Forest     | 78.4%          | 77.7%         |
| XGBoost           | 86.8%          | 80.7%         |
| Support Vector Machine (SVM) | 77.7%    | 77.4%         |

➡️ **Best model for generalization**: **XGBoost** with 80.7% test accuracy.

---

## 🧪 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Feature Importance Visualizations

---

## 📈 Feature Importance

Each model's key predictors were visualized, helping in feature interpretability and trust.

---

## 🗂 Tech Stack

- **Language**: Python
- **Libraries**:
  - `scikit-learn`
  - `xgboost`
  - `matplotlib`, `seaborn`
  - `numpy`, `pandas`

---

## 🧾 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/phishing-detection-ml.git
   cd phishing-detection-ml
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or script:
   - Open `phishing_model.ipynb` in Jupyter Notebook
   - OR run `python phishing_model.py` after organizing code into a script

4. Ensure the dataset path is updated if you're not using the original local directory.

---



## 📌 Future Improvements

- Add real-time URL scraping
- Integrate WHOIS or domain age features
- Build a live phishing detection web interface
- Optimize models with hyperparameter tuning

---


## 📜 License

This project is licensed under the [MIT License](LICENSE).

