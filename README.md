**A/B Testing: Website Theme Performance Analysis**

**Overview**

This project analyzes the impact of Light Theme and Dark Theme on key website performance metrics using A/B testing. The goal is to determine whether a particular theme leads to better engagement and conversion rates.

**Dataset**

**The dataset consists of 1000 entries with the following features:
**
Theme: Light Theme or Dark Theme

Click Through Rate (CTR): Percentage of users clicking on links

Conversion Rate: Percentage of users making a purchase

Bounce Rate: Percentage of users leaving without interaction

Scroll Depth: How far users scroll on the page

Age: User age

Location: Geographic location of users

Session Duration: Time spent on the website (in seconds)

Purchases: Whether a purchase was made (Yes/No)

Added_to_Cart: Whether an item was added to the cart (Yes/No)

**Methodology
**
**1. Data Cleaning & Exploration
**
Checked for missing values (none found)

Summarized key statistics

Visualized distributions of CTR, conversion rates, and session durations

**2. Data Visualization
**
Scatter Plots: CTR vs. Conversion Rate

Histograms: Click-Through and Conversion Rate distributions

Box Plots: Bounce Rate comparison

**3. Statistical Testing
**
A/B Testing for Purchases

Used proportion z-test to compare conversion rates:

Light Theme: 53.08%

Dark Theme: 50.39%

p-value = 0.3936 → No significant difference

A/B Testing for Session Duration

**Used two-sample t-test:**

Light Theme Avg: 930.83s

Dark Theme Avg: 919.48s

p-value = 0.7243 → No significant difference

**Conclusion
**
There is no statistically significant difference between Light and Dark themes in terms of conversion rate, session duration, and purchase behavior.

Other factors such as user preferences, device type, and accessibility should be considered before making a final decision.

Further testing with a larger sample size or additional A/B test parameters is recommended.

**Dependencies
**
pandas

plotly

statsmodels

scipy

****How to Run**

**Install dependencies using:**

pip install pandas plotly statsmodels scipy

**Run the script:
**
python ab_test_analysis.py

**Future Improvements**

Conduct A/B testing on different user segments

Evaluate theme preference based on device type

Incorporate qualitative user feedback for better insights

