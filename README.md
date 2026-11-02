# 🚗 Comprehensive Car Depreciation Analysis

A data-driven analysis of vehicle depreciation patterns using CarDekho market data. This project investigates how factors such as vehicle age, mileage, fuel type, transmission, seller type, and ownership history affect a car's ability to retain value over time.

## 📋 Project Overview

The purpose of this study is to understand the key drivers of vehicle depreciation and identify patterns that can help:

Car owners maximize resale value
Used-car buyers make informed purchasing decisions
Automotive analysts understand market trends
Dealerships optimize pricing strategies

To standardize comparisons across vehicles, a Value Retention Percentage metric was calculated:

Plain Text
Value Retention (%) = (Selling Price / Present Price) × 100

This metric represents how much of a vehicle's original value remains at the time of resale.

## 🎯 Objectives

This analysis seeks to answer the following questions:

How quickly do vehicles depreciate over time?
Does fuel type affect resale value retention?
Do automatic cars depreciate differently from manual cars?
Which has a greater impact on depreciation: age or mileage?
Does seller type influence vehicle value retention?
How does ownership history affect resale value?
## 📊 Key Findings
1. Baseline Depreciation Curve

Vehicle value declines most rapidly during the early years of ownership.

Vehicle Age	Value Retained	Depreciation1 Year	87.85%	12.15%
3 Years	72.21%	27.79%
5 Years	56.85%	43.15%
10 Years	29.43%	70.57%
Insight

The first five years account for the majority of value loss. After that, depreciation continues at a slower rate.

2. Impact of Fuel Type
Fuel Type	Average Value RetentionDiesel	67.96%
Petrol	62.41%
CNG*	50.98%

*CNG results are based on a very small sample size (n=2).

Insight

Diesel vehicles retain value better than petrol vehicles, suggesting stronger market demand and perceived long-term efficiency.

3. Impact of Transmission Type
Transmission	Average Value RetentionAutomatic	63.93%
Manual	63.37%
Insight

Despite generally costing more when new, automatic vehicles depreciate at nearly the same percentage rate as manual vehicles.

4. Mileage vs. Vehicle Age
Mileage Effect

For every additional:

Plain Text
10,000 *m driven

A vehicle loses approximately:

Plain Text
2.63% of its or*ginal value
Correlation Analysis
Factor	Correlation with Value RetentionVehicle Age	-0.8487
Mileage (Kms Driven)	-0.5059
Insight

Age is a significantly stronger predictor of depreciation than mileage.

5. Seller Type Dynamics
Seller Type	Average Value RetentionDealer	64.00%
Individual	62.42%
Insight

Dealer-listed vehicles maintain slightly higher resale values and show less volatility in older age groups.

6. Impact of Ownership History
Ownership Category	Average Value RetentionFirst Owner	64.24%
Second Owner	45.82%
Third Owner+	10.54%
Insight

Multiple ownership transfers significantly reduce market value. Buyers heavily discount vehicles with extensive ownership histories.

### 📈 Strategic Recommendations
✅ Best Time to Sell

Sell a vehicle between:

Plain Text
Year 3 and*Year 4

This allows owners to avoid the steep depreciation experienced after the 5-year mark.

✅ Best Used-Car Purchase

The analysis suggests that the best value-for-money vehicle is:

Plain Text
3-5*Year Old Diesel*Manual Car

Benefits:

Avoids initial depreciation shock
Retains strong utility
Offers favorable resale value
Higher value retention compared to alternatives
✅ Preservation Over Low Mileage

Since age has a greater impact than mileage:

Maintain service records
Preserve vehicle appearance
Ensure regular mechanical maintenance
Avoid neglecting older, low-mileage vehicles

Well-maintained vehicles consistently outperform poorly maintained counterparts in the resale market.

### 🔍 Key Takeaways
Vehicles lose value fastest during the first five years.
Diesel vehicles retain value better than petrol vehicles.
Automatic and manual transmissions depreciate at similar rates.
Vehicle age impacts resale value more than mileage.
Dealer vehicles command slightly higher retention rates.
Ownership history significantly influences resale pricing.
The optimal resale window is between Years 3 and 4.
The ideal used-car purchase is a 3-5-year-old diesel manual vehicle.
🛠 Dataset

Source: CarDekho Vehicle Market Dataset

Features Analyzed:

Selling Price
Present Price
Vehicle Age
Kilometers Driven
Fuel Type
Transmission Type
Seller Type
Number of Previous Owners
### 📚 Conclusion

This analysis demonstrates that depreciation is driven primarily by time, not usage. While factors such as fuel type, ownership history, and seller type influence resale value, vehicle age remains the most powerful determinant of value retention. Understanding these patterns enables both buyers and sellers to make smarter financial decisions in the automotive marketplace.

### 👨‍💻 Author

Data Analytics Project | Vehicle Depreciation Analysis using CarDekho Market Data

Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook, Exploratory Data Analysis (EDA), Statistical Correlation Analysis. 
[Inspired by VibhutiNair24]

Download Data here

https://raw.githubusercontent.com/VibhutiNair24/Car-Dekho-Data-Analysis-Market-Trends/main/1776311302-P3-Car%20Market%20Trends%20Analysis%20with%20Car%20Dekho%20Data.csv


