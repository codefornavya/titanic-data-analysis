# titanic-data-analysis
📄 README.md
markdown

# 🚢 Titanic Survival Prediction

This project analyzes and predicts survival outcomes of passengers aboard the Titanic using machine learning. The analysis is based on the classic Titanic dataset, and a Logistic Regression model is used to predict whether a passenger survived or not.

---

## 📁 Dataset

The dataset used in this project is `tested.csv`, which contains passenger details such as:

- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: # of siblings/spouses aboard
- `Parch`: # of parents/children aboard
- `Fare`: Passenger fare
- `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- `Survived`: Survival (0 = No, 1 = Yes)

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/titanic-survival-prediction.git
   cd titanic-survival-prediction
Install required Python packages:

pip install pandas seaborn matplotlib scikit-learn
Place the tested.csv dataset in the project root directory.

▶️ Usage
Run the analysis script:


python titanic_analysis.py
This script performs:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Logistic Regression training

Accuracy and classification metrics evaluation

Visualization of survival distribution by gender

📊 Sample Output
Model accuracy score

Confusion matrix and classification report

Bar chart showing survival by gender

📌 Project Structure
bash

titanic-survival-prediction/
│
├── tested.csv               # Input dataset
├── titanic_analysis.py      # Main analysis script
├── README.md                # Project documentation
└── requirements.txt         # (Optional) Package list
🧠 Model
We used Logistic Regression for binary classification. It predicts the probability that a passenger survived based on selected features.

📬 License
This project is open-source and free to use under the MIT License.

🙋‍♂️ Contact
For questions or suggestions, feel free to open an issue or contact yourname.

---
