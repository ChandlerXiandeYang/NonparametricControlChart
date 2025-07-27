# 📊 Cleaning Validation Trend Analysis

This repository focuses on developing a **custom control chart methodology** tailored for **Cleaning Process Validation** data, which presents unique challenges:

- **Multiple Upper Specification Limits (USLs)**
- **Small sample sizes** per cleaning event
- **High frequency of non-detectable values** (left-censored data)
- **No Lower Specification Limit (LSL)**

Due to these characteristics, **traditional control charts** (e.g., Shewhart, EWMA, CUSUM) are not suitable for trend analysis in this context. Our goal is to design a **specialized control chart** that can effectively monitor and analyze trends in cleaning validation data, accounting for its censored and sparse nature.

This tool aims to support **stability analysis** and **ongoing process verification** by providing a statistically sound and visually interpretable method for tracking cleaning performance over time.
