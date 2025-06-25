# PROBLEM 1: INFRASTRUCTURE DELAYS IMPACT ANALYSIS

## 1.1 Job Creation Prediction Model

Linear Regression: R² = -1.606 (±2.913)
Ridge Regression: R² = -0.755 (±2.110)
Random Forest: R² = -0.919 (±2.830)
Gradient Boosting: R² = -1.565 (±2.684)

### Best model for job creation: Ridge Regression
### Cross-validation R² score: -0.755

## 1.2 GDP Contribution Prediction Model

Linear Regression: R² = 0.398 (±0.517)
Ridge Regression: R² = 0.414 (±0.515)
Random Forest: R² = -0.459 (±1.400)
Gradient Boosting: R² = -0.458 (±1.202)

### Best model for GDP contribution: Ridge Regression
### Cross-validation R² score: 0.414

## 1.3 Infrastructure Delay Impact Analysis

### Infrastructure Delay Impact Summary:

| Scenario   | Total Jobs |  Job Loss   |  Total GDP (M) |  GDP Loss (M)   |
| ---------- | ---------- | ----------- | -------------- | --------------- |
| No_Delay   |    6100    |     0       |    7430        |    0            | 
| 10%_Delay  |    5958    |    142      |   7565         |  -135           |
| 20%_Delay  |    5815    |    285      |   7700         |  -270           |
| 30%_Delay  |    5673    |    427      |   7835         |  -405           |
