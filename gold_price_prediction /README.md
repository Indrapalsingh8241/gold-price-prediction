#  Gold Price Prediction using Machine Learning

## 📌 About This Project

This project is an attempt to understand how different financial factors affect the price of gold and to build a machine learning model that can predict gold prices.

I used historical data containing stock market index (SPX), oil prices (USO), silver prices (SLV), and currency exchange rate (EUR/USD) to predict the gold price (GLD).



## 📊 Dataset

The dataset includes:

* Date (for reference)
* SPX – S&P 500 Index
* GLD – Gold price (target variable)
* USO – Oil price
* SLV – Silver price
* EUR/USD – Currency exchange rate

---

## 🧠 What I Did

* Explored and understood the dataset
* Checked correlations between features
* Cleaned and prepared the data
* Split the dataset into training and testing sets
* Trained a machine learning model
* Evaluated the model performance
* Visualized predictions vs actual values



## 🤖 Model Used

I used a **Random Forest Regressor** because it performs well on structured data and handles feature relationships effectively.

---

# 📈 Results

The model gives a good prediction performance with an R² score of:

👉 **(Add your score here)**

---

## ⚙️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 How to Run This Project

1. Download or clone this repository
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
notebook/gold_analysis.ipynb
```

4. Run all cells to see the results

---

## 📁 Project Structure

```
gold-price-prediction/
│
├── data/
│   └── gld_price_data.csv
│
├── notebook/
│   └── gold_analysis.ipynb
│
├── requirements.txt
└── README.md
```

---

## 🔮 Future Improvements

* Try more models like XGBoost
* Perform hyperparameter tuning
* Build a simple web app using Streamlit
* Use real-time data

---

## 👨‍💻 Author

**Indrapal Singh**

---

If you found this project useful or interesting, feel free to ⭐ the repository!
