# Institutional Facility Energy Demand & CapEx Optimization Engine

Business Case Overview
Large public networks and school districts face high volatility in utility costs alongside unpredictable structural decay. This data science project builds a predictive forecasting and prescriptive resource optimization pipeline. It calculates building-level risk scores, models non-linear utility inflation trajectories, and mathematically rationalizes how to allocate capped capital budgets to achieve maximum fiscal return on investment (ROI).

Technical Architecture & Workflow
The project operates through an advanced 5-phase data science lifecycle implemented in Python:

Phase 1: Institutional Ingestion:  Structured an asset registry tracking 12 independent facilities across profiles like square footage, HVAC age, and historical consumption baselines.

Phase 2: Operational Feature Engineering: Developed a composite: Structural Risk Score** and calculated localized emergency failure liabilities to measure physical depreciation.

Phase 3: Supervised Machine Learning (Polynomial Forecasting): Implemented a 2nd-degree Polynomial Regression model to forecast curved utility inflation trends across upcoming fiscal years.

Phase 4: Prescriptive CapEx Optimization: Built a capital allocation sorting algorithm utilizing a CapEx Efficiency Ratio** to dynamically prioritize building upgrades under a strict $250,000 budget constraint.

Phase 5: Executive Dashboard Synthesis – Visualized complex data into a multi-axis matrix mapping structural risks against inflation forecasts, segmented by corporate funding status.

Tech Stack Used
- Language: Python 3
- Environment: Google Colab
- Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
