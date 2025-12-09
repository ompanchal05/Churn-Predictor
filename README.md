# 📊 Customer Churn Prediction System

A fully interactive **AI-powered Streamlit web application** that predicts customer churn and generates business insights using Machine Learning.

This app helps telecom or subscription-based businesses identify high-risk customers, understand churn patterns, and take proactive retention actions.

---

## 🚀 Key Features

* 🔥 Real-time churn prediction
* 📂 Auto-feature alignment (no cleaning required)
* 📊 Interactive dashboard with KPIs
* 📉 Probability and churn distribution charts
* 🧠 Feature importance insights (ML explainability)
* 💡 Smart business recommendations based on risk score
* 📥 Downloadable prediction results
* 🎨 Modern responsive UI (professional-grade dark theme)

---

## 🛠 Tech Stack

| Layer           | Technology                             |
| --------------- | -------------------------------------- |
| Web App         | Streamlit                              |
| Model           | XGBoost                                |
| Language        | Python                                 |
| Data Processing | Pandas, NumPy                          |
| Visualization   | Seaborn, Matplotlib                    |
| Deployment      | Streamlit Cloud / Render / HuggingFace |

---

## 📁 Project Structure

```
📦 churn-prediction-app
 ┣ 📂 saved_models
 ┃ ┣ retention_model.pkl
 ┃ ┗ model_features.pkl
 ┣ 📂 dataset (optional)
 ┣ app.py
 ┣ requirements.txt
 ┗ README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```sh
git clone https://github.com/YOUR-USERNAME/churn-predictor.git
cd churn-predictor
```

### 2️⃣ Create Virtual Environment

```sh
python -m venv venv
venv\Scripts\activate        # Windows
source venv/bin/activate     # Mac/Linux
```

### 3️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```sh
streamlit run app.py
```

---

## 📂 Input Format

Upload a CSV file with customer-based attributes such as:

* Tenure
* Monthly Charges
* Total Charges
* Contract Type
* Payment Method
* Demographics
* Usage metrics

Missing columns are automatically detected and corrected.

---

## 📊 Example Output

```
✔ Model Loaded: XGBoostClassifier
✔ Data processed successfully

📌 CHURN SUMMARY

• Total Customers: 1000
• High-Risk Customers: 109 (10.9%)
• Predicted Model Accuracy: ~89%
• Avg churn probability: 25.3%
```

---

## 🔍 Application Insights

The dashboard provides:

* High-risk customer count
* Overall churn probability confidence
* Risk visualization by histogram
* Feature importance insights to understand *why* customers churn

---

## 💡 Business Recommendations

Depending on churn level, the system suggests:

* 🎁 Targeted retention offers
* 📞 Customer service follow-ups
* ⭐ Loyalty reward programs
* 💬 Satisfaction surveys
* 📢 Personalized re-engagement campaigns

---

## 📦 Outputs Provided

* 📄 Prediction CSV
* 📊 Feature importance chart
* 📈 Risk distribution analysis

---

## 🌍 Deployment Ready

| Platform           | Compatible |
| ------------------ | ---------- |
| Streamlit Cloud    | ✅          |
| Render             | ✅          |
| HuggingFace Spaces | ✅          |
| AWS EC2            | ✅          |
| Railway            | ✅          |

---

## 🧪 Future Enhancements

* ⬜ SHAP Visualization for Explainable AI
* ⬜ Auto retraining pipeline
* ⬜ CRM Integration (Salesforce / HubSpot)
* ⬜ Role-based login dashboard

---

## 👤 Author

**Om Panchal**

💼 Aspiring Data Scientist / Machine Learning Engineer

---

## ⭐ Support

```
If you found this useful:
⭐ Star the repo
🍴 Fork it
📢 Share it!
```

---

> *“Successful businesses don’t react — they predict.”*

---

