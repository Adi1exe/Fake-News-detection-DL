# 📰 Fake News Detection using Machine Learning

This project is a simple Fake News Detection system built using the **LIAR dataset**. It uses **Logistic Regression** to classify political statements as either **true** or **false** based on text analysis.

## 📂 Dataset
- **Source**: [LIAR Dataset on Kaggle](https://www.kaggle.com/datasets/doanquanvietnamca/liar-dataset)
- The dataset contains political statements labeled as:
  - `true`, `mostly-true`, `half-true`, `barely-true`, `false`, `pants-fire`
- For simplicity, labels are grouped as:
  - **True** → `true`, `mostly-true`, `half-true`
  - **False** → `barely-true`, `false`, `pants-fire`

## ✅ Objective
Build a machine learning model that can:
- Take a political statement
- Predict if it's likely to be **true** or **false**

## 🛠️ Tools & Libraries
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

## 🔍 Process
1. **Data Loading**: Read the `.tsv` file containing statements and labels  
2. **Preprocessing**:
   - Clean and retain only the necessary columns
   - Convert labels to binary (0 = False, 1 = True)  
3. **Feature Extraction**:
   - Use TF-IDF to convert statements to numerical features  
4. **Model Training**:
   - Logistic Regression  
5. **Evaluation**:
   - Accuracy Score
   - Classification Report (precision, recall, f1-score)

## 📈 Results
- Accuracy: ~75-80%
- Model performs reasonably well with basic preprocessing and TF-IDF features

## 📌 How to Run
1. Install required libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
2. Clone the repository and open the notebook in Jupyter/Colab
3. Download the dataset and place ` train.tsv ` in your working directory
4. Run the cells in order

## 📬 Contact Me
[GitHub](https://github.com/Adi1exe/) |
[LinkedIn](https://www.linkedin.com/in/aditya-dolas-992a44265/) |
[My Portfolio](https://adityadolas.netlify.app) |
[E-mail](adityadolas.dev@gmail.com)