# 🌱 Sowing Success: Predictive Modeling for Agriculture

**Help farmers choose the best crop for their land using machine learning**

By analyzing soil properties and environmental conditions, this project predicts the most suitable crop — improving yield, reducing risk, and supporting sustainable farming decisions.

![Agriculture banner](images/farmer_in_a_field.jpg)


## 🎯 Project Goal

Build a reliable machine learning model that recommends the **most suitable crop** based on:

- Soil nutrients (N, P, K)
- Soil pH
- (Future: rainfall, temperature, humidity…)

## 📊 Dataset

**Features:**

| Feature | Description                  | Unit    |
|---------|------------------------------|---------|
| N       | Nitrogen content             | mg/kg   |
| P       | Phosphorus content           | mg/kg   |
| K       | Potassium content            | mg/kg   |
| pH      | Soil acidity/alkalinity      | —       |
| **label / Crop** | **Target variable** — crop name | —       |

**Source:** Synthetic / demonstration dataset (commonly used in agricultural ML tutorials)

## 🛠️ Approach

1. **Exploratory Data Analysis (EDA)**
   - Distribution of nutrients & pH
   - Correlation analysis
   - Feature importance visualization

2. **Modeling**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - **Random Forest** (best performer)

3. **Evaluation**
   - Accuracy
   - Confusion matrix
   - Classification report

**Best model:** Random Forest  
**Key insight:** Nitrogen (N) and pH usually among the most influential features

## 🚀 Results

- **Highest accuracy:** Random Forest (~97–99% on this dataset)
- Clear feature importance ranking
- Reliable predictions even with moderate class imbalance

## How to Use

```bash
# 1. Clone the repository
git clone https://github.com/Abdelrahmannasser139/sowing-success.git

# 2. Install required packages
pip install -r requirements.txt

# 3. Launch Jupyter Notebook
jupyter notebook

## 🔮 Future Work
- Integrate additional environmental features (rainfall, temperature, humidity)
- Add model interpretability using SHAP or other methods
- Build a simple web app to allow farmers to input soil data and get crop recommendations

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

