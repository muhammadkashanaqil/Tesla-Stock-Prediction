# 🚗 Predicting Tesla Stock Price Movements (2010–2020)

## 🧠 Project Overview

This project analyzes Tesla's stock market data (2010–2020) to help investors make better trading decisions using Exploratory Data Analysis (EDA) and Predictive Modeling techniques.

The goal is to:
* Explore and visualize stock price patterns
* Identify market trends and correlations
* Build models to predict Tesla's stock prices and direction

## 📊 Dataset

**Source:** [Kaggle - Tesla Stock Data (2010–2020)](https://www.kaggle.com/)

The dataset contains daily trading data with the following columns:
* `Date` – Trading day
* `Open` – Price at market opening
* `High` – Highest price during the day
* `Low` – Lowest price during the day
* `Close` – Price at market closing
* `Adj Close` – Adjusted closing price
* `Volume` – Number of shares traded

## 🧩 Project Structure

### Section A — Exploratory Data Analysis (EDA)
* Visualized closing price trends over the years
* Analyzed correlations between Open, High, Low, and Close prices
* Identified highest and lowest trading volume days
* Plotted the distribution of closing prices
* Detected and handled missing values and anomalies

### Section B — Linear Regression
* Built a Linear Regression model using `Open`, `High`, `Low`, and `Volume` as predictors
* Evaluated model using:
  * Mean Absolute Error (MAE)
  * Root Mean Square Error (RMSE)
  * R² Score
* Determined the most significant predictor for the closing price

### Section C — Logistic Regression
* Created a binary feature `Price_Up` (1 = next day's price higher, 0 = lower)
* Built a Logistic Regression model to predict `Price_Up`
* Evaluated using:
  * Accuracy
  * Confusion Matrix
  * Precision, Recall, and F1-Score

## 🧰 Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

## 📈 Key Insights

* Tesla's stock prices show a consistent upward trend post-2018
* Strong positive correlation among `Open`, `High`, `Low`, and `Close`
* Linear Regression achieved good prediction accuracy for closing prices
* Logistic Regression provided decent classification of next-day price movement

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/muhammadkashanaqil/Tesla-Price-Prediction.git
   cd tesla-stock-prediction
   ```

2. **Install required libraries**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook Tesla_Stock_Prediction.ipynb
   ```

## 📸 Sample Outputs

<!-- Add your screenshots of graphs, correlation heatmap, confusion matrix, etc. -->
![Closing Price Trend](images/closing_price_trend.png)
![Correlation Heatmap](images/correlation_heatmap.png)
![Confusion Matrix](images/confusion_matrix.png)

## 💡 Future Improvements

* Use advanced models like Random Forest or LSTM
* Incorporate live stock market data for real-time prediction
* Build an interactive dashboard using Streamlit

## 👤 Author

**Muhammad Kashan**

📍 Applied AI & Data Science | Data Analyst | Machine Learning Enthusiast

🔗 [LinkedIn](https://www.linkedin.com/in/muhammadkashanaqil/) • [GitHub](https://github.com/yourusername)

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

* Dataset provided by Kaggle
* Inspired by financial data analysis and machine learning applications in stock market prediction
