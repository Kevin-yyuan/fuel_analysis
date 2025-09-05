<style>
.report-container { font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; max-width: 800px; margin: auto; color: #333; line-height: 1.6; }
.header { text-align: center; border-bottom: 2px solid #993300; padding-bottom: 10px; margin-bottom: 20px; }
.header h1 { margin: 0; color: #993300; font-size: 24px; }
.header p { margin: 5px 0 0 0; color: #555; font-size: 12px; }
.summary { background-color: #fff0e6; border-left: 5px solid #993300; padding: 15px; margin-bottom: 25px; }
.summary h2 { margin-top: 0; font-size: 18px; color: #993300;}
.section-title { color: #993300; font-size: 20px; border-bottom: 1px solid #ccc; padding-bottom: 5px; margin-top: 30px; }
.chart { text-align: center; margin: 20px 0; }
.chart img { max-width: 100%; border: 1px solid #ddd; }
.chart-caption { font-size: 12px; color: #666; font-style: italic; margin-top: 5px; }
.recommendations ol { padding-left: 20px; }
.recommendations li { margin-bottom: 10px; }
.footer { text-align: center; font-size: 12px; color: #777; margin-top: 40px; border-top: 1px solid #ccc; padding-top: 10px; }
</style>

<div class="report-container">

<div class="header">
<h1>XYZ Logistics Inc. | Toronto Operations</h1>
<p>Internal Memo: For Immediate Management Review</p>
</div>

TO: Operations & Finance Management

FROM: Kevin Yuan, Business & Data Analyst, Toronto

SUBJECT: Final Analysis: Mitigating Risk from Fuel Volatility and Lane Inefficiencies

<div class="summary">
<h2>Executive Summary</h2>
<p>This analysis of July 2025 data reveals a critical business risk driven by a combination of external market pressure and internal operational inefficiencies. Fuel prices in the GTA rose by over 10% in July, exposing vulnerabilities in our network. This market volatility disproportionately impacts our least efficient lanes, particularly the Brampton to Montreal route, which operates at an abnormally high $0.602/km. This report recommends immediate actions to address this specific inefficiency hotspot, optimize our fleet, and explore financial instruments to hedge against further market shocks.</p>
</div>

<h3 class="section-title">Context: A Volatile and Rising Fuel Market</h3>
The primary driver of risk in July was the external market. Diesel prices in the Greater Toronto Area showed a consistent upward trend, increasing our baseline costs and making every operational inefficiency more costly.

<div class="chart">
<img src="daily_average_price.png" alt="Line chart showing fuel price trends for July 2025, indicating a steady increase throughout the month.">
<p class="chart-caption">Figure 1: Daily average price of diesel in Ontario for July 2025.</p>
</div>

<h3 class="section-title">Finding 1: The Brampton-Montreal Lane Inefficiency Hotspot</h3>
The rising market prices magnify the impact of our least efficient lanes. By analyzing fuel cost per kilometer, the data shows the Brampton-Montreal route is a significant operational outlier, costing more per kilometer than even our longest cross-border routes.

<div class="chart">
<img src="efficiency_by_route.png" alt="Bar chart showing the average fuel cost per kilometer by route. The Brampton to Montreal route is the highest at over $0.60/km.">
<p class="chart-caption">Figure 2: The Brampton-Montreal lane stands out as our most inefficient route based on July data.</p>
</div>

<h3 class="section-title">Finding 2: The Underlying Cause—Our Fleet Efficiency Gap</h3>
This specific route issue is amplified by a fundamental challenge in our fleet composition. Our trucks are inherently more than twice as expensive to operate per kilometer as our vans, making any inefficiency on truck-dominated routes significantly more impactful to our bottom line.

<div class="chart">
<img src="cost_per_km_by_vehicle.png" alt="Bar chart comparing the fuel cost per kilometer for Trucks and Vans. Trucks are at $0.57/km and Vans are at $0.25/km.">
<p class="chart-caption">Figure 3: The operational cost gap between Trucks and Vans is the primary driver of high per-kilometer costs.</p>
</div>

<h3 class="section-title">Actionable Recommendations</h3>

Based on this comprehensive analysis, the following actions are recommended for immediate implementation:

Launch an "Efficiency Audit" on the Brampton-Montreal Lane: We must immediately determine why this specific route is an outlier. I recommend tasking a logistics coordinator with a two-week audit of this lane, focusing on vehicle assignment, route optimization software performance, and driver metrics.

Mitigate Market Risk via Financial Hedging: Given the clear price volatility shown in Figure 1, we must engage the finance department to evaluate fuel hedging strategies for Q4 2025. Locking in prices for a portion of our consumption will insulate our budget from further market shocks.

Initiate a Fleet "Right-Sizing" Program: The data in Figure 3 proves our vans are dramatically more efficient. We should immediately identify all freight on shorter domestic routes (e.g., Toronto-Ottawa, Toronto-Windsor) that could be shifted from trucks to vans to lower our fleet's overall average cost per kilometer.

<div class="footer">
For a complete breakdown of the methodology, data cleaning steps, and Python code, please refer to the <a href="https://github.com/Kevin-yyuan/fuel_analysis.git" target="_blank">full analysis in the project's Jupyter Notebook on Github</a>.
</div>

</div>
