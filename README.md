# 📁 Project Structure

```
cloud-service-cost-analyzer/
├── app.py
├── requirements.txt
└── README.md
```

---

## 📄 requirements.txt

```
streamlit
pandas
numpy
matplotlib
seaborn
scikit-learn
google-generativeai
```

---

## 📄 README.md

````markdown
# ☁️ Cloud Service Cost Analyzer

This is a Streamlit web application that uses Google's Gemini AI to recommend cloud services (AWS, GCP, Azure) based on your project description, and provides detailed cost estimations and visualizations.

## 🌟 Features

- ✅ Accepts project description and preferences (provider, region, scale)
- 🤖 Uses Gemini AI to suggest suitable cloud services
- 📈 Estimates cost projections (daily, weekly, monthly)
- 📊 Visualizes:
  - Service cost breakdown
  - Cost distribution
  - Scaling behavior
  - Cumulative cost over time
  - Multi-cloud provider comparison

## 🛠 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **AI Integration**: Google Gemini API
- **Visualization**: Matplotlib & Seaborn
- **ML Model**: Linear Regression from scikit-learn

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Abinayashri-Gupta/CloudChecker.git
   cd cloud-service-cost-analyzer
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set your Gemini API Key:**

   In `cld.py`, replace the placeholder value:

   ```python
   API_KEY = "YOUR_API_KEY_HERE"
   ```

4. **Run the Streamlit app:**
   ```bash
   streamlit run clk.py
   ```
````
