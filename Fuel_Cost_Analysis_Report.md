<style>
.report-container { font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; max-width: 800px; margin: auto; color: #333; line-height: 1.6; }
.header { text-align: center; border-bottom: 2px solid #004080; padding-bottom: 10px; margin-bottom: 20px; }
.header h1 { margin: 0; color: #004080; font-size: 24px; }
.header p { margin: 5px 0 0 0; color: #555; font-size: 12px; }
.summary { background-color: #e6f0ff; border-left: 5px solid #004080; padding: 15px; margin-bottom: 25px; }
.summary h2 { margin-top: 0; font-size: 18px; color: #004080;}
.section-title { color: #004080; font-size: 20px; border-bottom: 1px solid #ccc; padding-bottom: 5px; margin-top: 30px; }
.chart { text-align: center; margin: 20px 0; }
.chart img { max-width: 100%; border: 1px solid #ddd; }
.chart-caption { font-size: 12px; color: #666; font-style: italic; margin-top: 5px; }
.recommendations ol { padding-left: 20px; }
.recommendations li { margin-bottom: 10px; }
.footer { text-align: center; font-size: 12px; color: #777; margin-top: 40px; border-top: 1px solid #ccc; padding-top: 10px; }
</style>

<div class="report-container">

<div class="header">
<h1>Northern Logistics Inc.</h1>
<p>Internal Memo: For Management Review</p>
</div>

TO: Operations & Finance Management

FROM: Kevin Yuan, Business & Data Analyst

SUBJECT: Strategic Analysis: Pinpointing Fuel Cost Exposure in North American Freight Lanes

<div class="summary">
<h2>Executive Summary</h2>
<p>An analysis of July 2025 trip data reveals that <strong>long-haul, cross-border routes, particularly Toronto to Dallas, are 15% more sensitive to fuel price volatility than key domestic routes</strong>. This heightened exposure, driven by long distances and less efficient vehicles, presents a strategic opportunity for targeted cost-saving measures that could mitigate significant financial risk.</p>
</div>

<h3 class="section-title">Key Finding: Long-Haul Routes Show Highest Cost Per Kilometer</h3>

The analysis of all 50 trips in July 2025 shows a direct correlation between route distance and fuel cost per kilometer. As illustrated in the chart below, cross-border routes to the United States are the most expensive to operate from a fuel perspective.

<div class="chart">
<img src="blob:vscode-webview://178p91fpburms38p1u28fm0c2c6ho64ev1vaed5qtk0t5h3rusgo/3a32115c-08bc-4003-8359-5220e154d1d6" alt="Bar chart showing the average fuel cost per kilometer by route. The Toronto to Dallas route is the highest at over $0.60/km.">
<p class="chart-caption">Figure 1: Comparison of average fuel cost per kilometer for key routes. Long-haul routes show significantly higher costs.</p>
</div>

Key Insight: The Toronto to Dallas route averaged $0.61/km in fuel costs. This is substantially higher than shorter domestic routes like Toronto to Windsor, which averaged $0.58/km on the same vehicle type, and significantly more than the $0.25/km cost for van routes. This disparity is magnified during periods of price volatility.

<h3 class="section-title">Context: Fuel Price Volatility</h3>

The month of July saw a consistent upward trend in diesel prices, increasing by over 10% from start to finish. This volatility magnifies the financial risk on our longest and most frequent routes.

<div class="chart">
<img src="blob:vscode-webview://178p91fpburms38p1u28fm0c2c6ho64ev1vaed5qtk0t5h3rusgo/7757c2d6-c935-4800-8366-3cda9256bad9" alt="Line chart showing fuel price trends for July 2025, indicating a steady increase throughout the month.">
<p class="chart-caption">Figure 2: Daily average price of diesel in Ontario for July 2025.</p>
</div>

<h3 class="section-title">Actionable Recommendations</h3>

Based on these findings, the following actions are recommended to mitigate risk and improve cost efficiency:

Prioritize Aerodynamic Upgrades for Long-Haul Fleet: Focus capital investment on fuel-saving technologies (e.g., side skirts, trailer tails) for trucks dedicated to the Dallas, Chicago, and New York lanes. A 5% efficiency gain on these routes will yield greater absolute savings than a 10% gain on shorter domestic routes.

Test Smaller, More Efficient Vehicles on Shorter Routes: Initiate a pilot program to test if smaller, more fuel-efficient vehicles can service the Toronto-Windsor lane without impacting delivery times. The current cost per kilometer on this route is disproportionately high for a domestic trip.

Explore Fuel Hedging Options for Q4: Engage with the finance department to evaluate fuel hedging strategies. Locking in fuel prices for a portion of our anticipated Q4 consumption could protect us from market volatility during the high-demand holiday season.

<div class="footer">
For a complete breakdown of the methodology, data cleaning steps, and Python code, please refer to the <a href="https://www.google.com/search?q=https://github.com/your-username/fuel_analysis" target="_blank">full analysis in the project's Jupyter Notebook on GitHub</a>.
</div>

</div>
