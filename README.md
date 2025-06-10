# 🚗 Uber Trip Data Analysis

This project explores Uber trip data to identify patterns, trends, and factors affecting ride numbers and earnings. Using Python and various data analysis and machine learning libraries, the notebook investigates questions like:

* What are the peak months, days, and hours for Uber rides?
* What factors contribute to higher ride numbers?
* Does weather or special events affect Uber demand?

## 📊 Dataset Overview

The dataset includes the following columns:

* `Date`: Trip date
* `DayOfWeek`: Day of the week
* `Time`: Time of trip
* `Expected Earnings`, `ActualEarnings`: Predicted vs real earnings
* `Time predicted`, `ActualTime`: Estimated vs actual trip time
* `Hourly`, `Distance`: Hourly rate and trip distance
* `Accepted`: If the trip was accepted
* `Boost`, `ActualBoost`: Predicted and actual boost amounts
* `BaseFare`, `Promotion`, `Tip`: Pricing details
* `NumberOfDeliveries`: Deliveries in that trip

## 🧰 Technologies Used

* Python (Jupyter Notebook)
* pandas, NumPy
* matplotlib, seaborn
* scikit-learn
* scipy

## 🔍 Key Analyses

* Temporal analysis (by month/day/hour)
* Earnings vs time correlation
* Impact of promotions, boosts, and tips
* Clustering analysis to detect ride patterns

## 📁 How to Use

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/uber-trip-analysis.git
   cd uber-trip-analysis
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open and run `Portfolio4.ipynb` using Jupyter Notebook or Google Colab.

## 📌 Notes

* The project includes imputation of missing values and clustering for trip patterns.
* Future improvements could include integrating weather or event data for deeper insights.

## 📜 License

This project is open source under the [MIT License](LICENSE).

