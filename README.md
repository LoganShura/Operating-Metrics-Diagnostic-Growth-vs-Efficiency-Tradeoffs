# Operating Metrics Diagnostic - Growth vs Efficiency

**Overview:**

This project is a lightweight business operations diagnostic designed to identify whether performance pressure is driven by growth deceleration, cost efficiency erosion, or downstream margin impact.

Using simulated monthly operating data, the analysis focuses on isolating early signals and sequencing effects to support faster, higher-quality leadership decisions.
#
**Business Question:**

Is operating underperformance driven by demand, cost efficiency, or margin compression — and in what order do those signals appear?
#
**Approach:**

The diagnostic follows a standard BizOps / Strategy workflow:

1. Baseline Operating Data

• Monthly revenue, users, CAC, support costs, and gross margin

2. Metric Derivation

• Growth rates, unit economics, and cost ratios validated in Excel

3. Visual Diagnostics

• Executive-facing Tableau dashboard highlighting signal sequencing

4. Insight Framing

• Focus on cause vs effect rather than recommendations

All data is simulated for illustrative purposes.
#
**Key Insights:**

• Revenue growth decelerates ahead of margin compression, indicating demand or monetization pressure before cost impact is visible

• Support costs scale faster than revenue, signaling operating model inefficiency as volume increases

• Gross margin erosion lags upstream signals, confirming margin pressure is a downstream consequence rather than a root cause
#
**Artifacts:**

Excel Model (metrics validation):
analysis/Operating_Metrics_Model.xlsx

Tableau Dashboard (executive diagnostic):
tableau/Operating_Metrics_Dashboard.twbx

Raw Data (simulated):
data/Operating_Metrics_Monthly.csv
