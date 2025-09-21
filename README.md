# 🏎️ F1 Top 5 Predictor – Decision Tree Classifier

This project uses **machine learning** to predict whether an F1 driver will finish in the **Top 5** of a race, based on race and driver statistics.  
It uses **scikit-learn's DecisionTreeClassifier** to train a model and then predict on new race data, with probability scores and a color-coded table for visualization.

---

## 📌 Features
- ✅ **Loads historical race data** to train the model  
- ✅ **Predicts Top 5 finishes** for upcoming races  
- ✅ **Displays probabilities** of finishing in the Top 5  
- ✅ **Color-coded results** for easy interpretation (Green = Top 5, Red = Not Top 5)  
- ✅ Clean, beginner-friendly implementation with `scikit-learn`

---

## 🛠️ Tech Stack
- **Python 3**
- **pandas** – data loading & manipulation
- **scikit-learn** – Decision Tree model
- **Jupyter Notebook** – interactive development & visualization

---

## 📂 Project Structure
📁 F1-DecisionTree
┣ 📜 f1_top5_predictor.ipynb # Main Jupyter Notebook
┣ 📜 README.md # Project documentation (this file)
┣ 📜 sklearndecisiontrees.ipynb 

---

## 🚀 How to Run

1. **Clone this repository:**
```bash
git clone https://github.com/your-username/F1-DecisionTree.git
cd F1-DecisionTree
pip install pandas scikit-learn
Jupyter Notebook f1_top5_predictor.ipynb
