# Supply-chain-Analysis-pareto-analysis-segmentation-and-ABC-analysis
Project Overview
In a typical supply chain, 20% of items often account for 80% of the volume. 
This project implements a data-driven approach to inventory classification using Python. 
By segmenting items based on total quantity (ABC Analysis) and demand volatility (XYZ Analysis), we can optimize stock levels, reduce carrying costs, and improve service levels.

🛠️ Key Features
Data Reshaping: Transformed raw transactional data into a time-series matrix using pandas pivot tables.
Statistical Profiling: Calculated Mean, Standard Deviation, and Coefficient of Variation (CV) for every SKU.
Demand Classification: Categorized items into demand patterns:
Smooth: Stable demand (CV < 0.5)
Erratic: Moderate fluctuations (0.5 < CV < 1.0)
Lumpy: High volatility (CV > 1.0)
Data Cleaning: Filtered out inactive SKUs to ensure statistical accuracy for forecasting.

💻 Technologies Used
Python 3.x
Pandas: For data manipulation and aggregation.
NumPy: For statistical calculations.
Matplotlib: For visualizing demand trends.

Acknowledgments
This project was developed as part of my Business Analytics portfolio at FAST NUCES.
Special thanks to the community and online educators (Samir Saci, youtube= 'Supply Science') 
for providing the foundational framework that I adapted and extended for this analysis.
