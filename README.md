# 📈 AI Sales Forecasting Dashboard

This is a simple AI-powered sales forecasting web app built with Python and Streamlit.  
Users can upload their own Excel sales data (with Date & Sales columns), and the app uses Meta’s **Prophet** model to predict the next 30 days of sales.

---

## 🔗 Live Demo

👉 [Click here to try the app](https://workgit-2ltmjumjq36eypwxsqhmzf.streamlit.app/)

---

## ⚙️ How It Works

1. Upload your `.xlsx` sales data file
2. The app automatically cleans the data
3. Uses **Prophet** to train a model on your data
4. Predicts the next 30 days of sales
5. Shows an interactive forecast chart + forecast table

---

## 📄 Input File Format

Your Excel file must include **two columns** exactly named:

| Date        | Sales |
|-------------|-------|
| 2024-01-01  | 120   |
| 2024-01-02  | 130   |
| ...         | ...   |

- `Date`: must be a valid date format
- `Sales`: numeric values only

You can use the included file `sample_sales_data.xlsx` for testing.

---

## 🛠️ Tech Stack

- Python 3
- Streamlit
- Prophet (by Meta)
- Pandas
- Matplotlib
- OpenPyXL

---
## 📦 Installation (Run Locally)

```bash
git clone https://github.com/yourusername/ai-sales-dashboard.git
cd ai-sales-dashboard
pip install -r requirements.txt
streamlit run app.py
