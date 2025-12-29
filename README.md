🚕 Maximizing Revenue for Taxi Drivers
📊 A Data-Driven Analysis of Payment Types & Fare Behavior

Can payment methods influence how much taxi drivers earn?
This project answers that question using real-world NYC Taxi Trip data, statistical testing, and business-focused insights.

🌟 Project Overview

In the fast-paced taxi booking ecosystem, maximizing driver revenue is critical for sustainability and driver satisfaction.
This project explores whether payment type (Cash vs Card) has a statistically significant impact on fare amount and how platforms can nudge customers toward higher-revenue behaviors — without hurting customer experience.

🎯 Objectives

📌 Analyze the relationship between payment type and fare amount

📌 Identify customer payment preferences

📌 Validate findings using hypothesis testing

📌 Provide actionable, data-backed recommendations for revenue optimization

❓ Research Questions

Is there a significant difference in average fare between card and cash payments?

Can encouraging card payments help drivers earn more?

How do trip distance, duration, and passenger count interact with payment behavior?

🗂️ Dataset Overview

Source: NYC Taxi Trip Records

Key Features Used:

👥 passenger_count (1–5)

💳 payment_type (Card / Cash)

💰 fare_amount

📏 trip_distance (miles)

⏱️ trip_duration (minutes)

Data was cleaned and engineered to focus only on relevant analytical variables.

🧠 Methodology
🔹 1. Descriptive Analysis

Compared mean fares and trip distances by payment type

Analyzed payment preference distribution

🔹 2. Hypothesis Testing (T-Test)

H₀ (Null Hypothesis): No difference in average fare between cash and card users

H₁ (Alternative Hypothesis): A significant difference exists

🔹 3. Regression Analysis

Studied the relationship between trip duration and fare amount

📊 Key Insights & Findings
💳 Payment Preference

67.5% of rides are paid via card

32.5% via cash
➡️ Strong customer preference for card payments

💰 Fare & Distance Patterns

Card payments show:

Higher average fare

Longer trip distance
➡️ High-value rides are more likely to be paid by card

👥 Passenger Count Insights

Single-passenger rides dominate for both payment types

Usage declines as passenger count increases

🧪 Hypothesis Testing Results

📈 T-Statistic: 165.5

📉 P-Value: < 0.05

✅ Result: Null hypothesis rejected
➡️ There is a statistically significant difference in average fare between card and cash payments.

🚀 Business Recommendations

🎁 Offer incentives or discounts for card payments

🔐 Ensure seamless, secure digital payment options

📢 Gently nudge customers toward card payments during booking

📈 Leverage card preference to increase driver earnings

🛠️ Tools & Technologies

🐍 Python

📊 Pandas, NumPy

📈 Matplotlib / Seaborn

📐 SciPy (T-Test)

📓 Jupyter Notebook

📁 Project Structure
📦 Maximizing-Taxi-Driver-Revenue
 ┣ 📊 Hypothesis Testing.ipynb
 ┣ 📄 Maximizing_revenue.pdf
 ┣ 📘 README.md

🏁 Conclusion

This project demonstrates how data analytics + statistical testing can uncover hidden revenue opportunities.
By understanding customer payment behavior, taxi platforms can optimize earnings while preserving user experience.

🙌 Acknowledgements

NYC Taxi & Limousine Commission

Open-source Python community
