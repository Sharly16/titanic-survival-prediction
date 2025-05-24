# titanic-survival-prediction
Machine Learning web app to predict Titanic passenger survival using Gradio and Random Forest.

# 🚢 Titanic Survival Prediction Web App

A machine learning web application that predicts whether a passenger would have survived the Titanic disaster based on their information. This project is built using **scikit-learn** for model training and **Gradio** for creating a simple and interactive user interface — all in **Google Colab**.

---

## 📊 Dataset

The model is trained on the classic [Titanic dataset](https://www.kaggle.com/c/titanic/data) containing passenger data such as:

- Age
- Sex
- Passenger class
- Fare
- Number of siblings/spouses or parents/children aboard
- Embarkation port

---

## 🚀 Features

- Interactive **Gradio web interface**
- Real-time predictions
- Simple and clean UI
- Trained with **Random Forest Classifier**
- Works entirely in **Google Colab** — no setup needed!

---

## 🧠 Tech Stack

- **Python**
- **pandas** – data preprocessing
- **scikit-learn** – model training and evaluation
- **Gradio** – web UI
- **joblib** – model serialization

---

## 🛠️ How to Run in Google Colab

1. Open [Google Colab](https://colab.research.google.com/)
2. Paste the full notebook code.
3. Make sure this line runs at the top:
   ```python
   !pip install gradio scikit-learn pandas joblib

Run all cells.

A public Gradio app link will appear — click it to interact with the model.

✅ Survived
| Field    | Value     |
| -------- | --------- |
| Pclass   | 1         |
| Sex      | Female    |
| Age      | 28        |
| SibSp    | 0         |
| Parch    | 0         |
| Fare     | 100       |
| Embarked | Cherbourg |

❌ Did Not Survive
| Field    | Value       |
| -------- | ----------- |
| Pclass   | 3           |
| Sex      | Male        |
| Age      | 45          |
| SibSp    | 1           |
| Parch    | 0           |
| Fare     | 8           |
| Embarked | Southampton |

📈 Model Evaluation
Accuracy: ~82%

Classification Report and Confusion Matrix included in the notebook output.


🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

📜 License
This project is open-source and free to use under the MIT License.

🙋‍♂️ Author
SHARLY PRICILLA A
