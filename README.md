# Cervical Cancer Detection Using Machine Learning

## What This Project Does

This project uses computer programs to predict cervical cancer risk by analyzing health information from 835 patients. It looks at 36 different factors about each person's health and lifestyle.

## What Information We Used

* **Basic Info**: How old the patient is
* **Personal Health History**: Number of sexual partners, pregnancies, age when first sexually active
* **Lifestyle Habits**: Smoking behavior
* **Medical Background**: Birth control usage, sexually transmitted disease history, HPV status, test results
* **Final Answer**: Whether the patient has cancer (No or Yes)

## Tools We Used

Python programming language with helpful tools like NumPy, Pandas, Matplotlib, Seaborn, Plotly, Scikit-learn, XGBoost, and Imbalanced-learn

## How We Did It

1. **Cleaning the Data**: Removed information with too many gaps, filled in missing numbers with average values
2. **Studying the Data**: Looked at patterns, checked how factors relate to each other, removed very similar factors
3. **Training the Models**: Fixed the uneven number of cancer vs non-cancer cases, taught 5 different computer models to make predictions

## How Well It Worked

| Model | How Often It Was Right |
|-------|------------------------|
| Random Forest | 100% |
| Logistic Regression | 100% |
| XGBoost | 100% |
| Decision Tree | 99% |
| SVC | 89% |

## How to Use This
```bash
# Download the required tools
pip install numpy pandas matplotlib seaborn plotly scikit-learn xgboost imbalanced-learn

# Get the project and run it
git clone https://github.com/Vi-dh-i/Cervical_Cancer_Detection.git
cd Cervical_Cancer_Detection
python cervical_cancer_detections.py
```

## Important Findings

* **Big Difference in Numbers**: Only 18 patients had cancer while 817 didn't, so we used special techniques to balance this out
* **Main Risk Factors**: Age, number of sexual partners, STD history, HPV infection, smoking, and birth control pill use

## Project Creator

**Vidhi Patel**
- Email: vidhipatel1892000@gmail.com
- GitHub: [@Vi-dh-i](https://github.com/Vi-dh-i)

## Important Note

This is for learning purposes only. Always talk to real doctors for health advice and decisions.
