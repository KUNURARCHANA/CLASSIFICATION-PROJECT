# Classification Project

This project focuses on building a classification model using machine learning.

## 📂 Files
- `Final Classification.ipynb` - Jupyter Notebook with code and analysis.
- `Syndey_rain prediction.csv/` - Contains the dataset 
- `Box Plot for all parameters to detect outliers.png
   Heatmap for correlation b/w parameters.png
   decision tree classifier.png
   XG Boost Classifier.png/` - 4  Visualization outputs.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/classification-project.git
   cd classification-project
2. Install dependicies
   pip install -r requirements.txt
3.open Jupiter notebook
   jupyter notebook
## 📊 Results

🔹 **Model Used**: Multiple Logistic Regression,Linear Discriminant Model,Bagging,Random Forest Classifier , Decision Tree Classifier,KNN classifier ,Grid Search,Gradient Boosting,ADA Boost,XG Boosting
🔹 **Accuracy**: different accuaracy aquired by different methods,but highest accuracy by Gradient Boosting --84.7%
        ![accuracy by different methods](https://github.com/user-attachments/assets/e1f9819a-36d2-4d9b-863d-ef2d4a359db6)

📌 **Key Insights:**
1️⃣ The most important feature for classification was `feature_X`, followed by `feature_Y`.  
2️⃣ The model performed well but could be improved by hyperparameter tuning.  
3️⃣ Handling class imbalance through SMOTE or weighted loss could further improve recall.  



