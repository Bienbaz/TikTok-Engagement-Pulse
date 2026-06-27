# Time Series Analysis – TikTok Engagement Pulse

**Project using pandas, statsmodels, and seasonal decomposition on TikTok view data.**

## Dataset
- 90 days of daily view counts
- Synthetic but realistic time series with trend + weekly seasonality

## DTA Framework Applied

**Discovery**: Data loading, datetime indexing, resampling  
**Technical**: Seasonal decomposition + ADF stationarity test  
**Action**: Peak day identification + content scheduling strategy

## Key Findings
- Strong **weekly seasonality** observed
- Series is **non-stationary** (p-value > 0.05) → requires differencing
- Highest engagement: **Wednesday & Thursday**

## Business Recommendation
Upload high-impact content on **Wednesday/Thursday** and analyze performance trends for better algorithmic reach.

**Next Step**: Build SARIMA model for view count forecasting.

---
**Project completed as part of Time Series Analysis module**
