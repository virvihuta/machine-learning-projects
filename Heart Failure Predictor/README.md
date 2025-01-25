## 📖 Overview
This project predicts the risk of heart failure using patient health metrics. It employs machine learning techniques to achieve high accuracy and provide valuable insights for healthcare applications.

## 🗂️ Project Structure
Heart_Failure_Predictor_RFC.ipynb  (Code notebook)

heart.csv  (Dataset)

README.md  (Documentation)

## ⚙️ Workflow
1. Data Preprocessing:
   - Encoded categorical variables using OneHotEncoder and OrdinalEncoder.
   - Scaled numerical variables using StandardScaler.
   - Worked within a Column Transformer
2. Model Building:
   - Trained a Random Forest Classifier.
   - Worked within a Pipeline
3. Evaluation:
   - Measured performance using accuracy, f1, and Cross Validation.

## 📈 Results
- Accuracy: 84.6%
- Improved Accuracy: 86.4%
- Features: Age,	Sex,	ChestPainType,	RestingBP,	Cholesterol,	FastingBS,	RestingECG,	MaxHR, ExerciseAngina, Oldpeak,	ST_Slope, HeartDisease.

## 📂 Dependencies
- pandas
- numpy
- scikit-learn
- matplotlib

## 🌟 Future Improvements
- Test other machine learning algorithms like XGBoost and SVM.
- Use Optuna for further Hyperparameter Improvements.
