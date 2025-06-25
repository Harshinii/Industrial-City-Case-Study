# INDUSTRIAL CITY DATA ANALYSIS - STRATEGIC INSIGHTS

The following insights are produced by analysing the [dataset](https://github.com/Harshinii/Industrial-City-Case-Study/blob/main/Data%20Analysis/Industrial_City_Case_Study.csv) using the [python code](https://github.com/Harshinii/Industrial-City-Case-Study/blob/main/Data%20Analysis/Data_Analysis.ipynb)

## 1. UTILITY DEMAND vs CAPACITY ANALYSIS

### 1.1 CLUSTERS WITH UTILITY CAPACITY SHORTFALLS

CRITICAL CLUSTERS - 2025:

| Cluster | Gap (MW) |  Utilization %  | Risk Level  |
| ------- | -------- | --------------- | ----------- |
| 2       | 20       |  125.0          | CRITICAL    |
| 5       | 20       |  122.2          | CRITICAL    |
| 7       | 20       |  120.0          | HIGH        |
| 9       | 20       |  123.5          | CRITICAL    |
| 10      | 20       |  126.7          | CRITICAL    |
| 4       | 15       |  121.4          | CRITICAL    |
| 1       | 10       |  116.7          | HIGH        |
| 3       | 10       |  120.0          | HIGH        |
| 6       | 10       |  115.4          | HIGH        |
| 8       | 10       |  118.2          | HIGH        |

CRITICAL CLUSTERS - 2030:

| Cluster | Gap (MW) |  Utilization % |  Risk Level  |
| ------- | -------- | -------------- | ------------ |
| 5       | 50       |  155.6         |  CRITICAL    |
| 7       | 50       |  150.0         |  CRITICAL    |
| 2       | 40       |  150.0         | CRITICAL     |
| 9       | 40       |  147.1         |  CRITICAL    |
| 10      | 40       |  153.3         |  CRITICAL    |
| 4       | 35       |  150.0         |  CRITICAL    |
| 6       | 35       |  153.8         |  CRITICAL    |
| 1       | 30       |  150.0         |  CRITICAL    |
| 3       | 30       |  160.0         |  CRITICAL    |
| 8       | 30       |  154.5         |  CRITICAL    |

1.2 MITIGATION STRATEGIES
------------------------------
IMMEDIATE ACTIONS (2025):
- Total capacity shortfall: 155 MW
- Estimated investment needed: $232M (at $1.5M/MW)
- Priority clusters for capacity expansion:
  - Cluster 2: +20 MW needed
  - Cluster 5: +20 MW needed
  - Cluster 7: +20 MW needed

LONG-TERM PLANNING (2030):
- Total capacity shortfall: 380 MW
- Estimated investment needed: $570M
- Recommended strategies:
  - Phased capacity expansion (2025-2030)
  - Demand management programs
  - Alternative energy sources integration
  - Smart grid implementation

## 2. GROWTH LEADERS ANALYSIS

### 2.1 JOB CREATION LEADERS

Top job creators (2025):

| Cluster | New Jobs |  Growth % |  Current  |  Projected |
| ------- | -------- | --------- | --------- | ---------- |
| 9       | 180      |  42.9     |  420      |  600       |
| 10      | 180      |  34.6     |  520      |  700       |
| 2       | 150      |  37.5     |  400      |  550       |
| 3       | 150      |  42.9     |  350      |  500       |
| 4       | 150      |  33.3     |  450      |  600       |

Top job creators (2030):

| Cluster | New Jobs |  Growth % | Current  |  Projected  |
| ------- | -------- | --------- | -------- | ----------- | 
| 10      | 480      |  92.3     |  520     |   1000      |
| 9       | 430      |  102.4    |  420     |   850       |
| 4       | 400      |  88.9     |  450     |   850       |
| 7       | 400      |  50.0     |  800     |   1200      |
| 6       | 380      |  118.8    |  320     |   700       |

### 2.2 GDP CONTRIBUTION LEADERS

Top GDP contributors (2025):

| Cluster | GDP Growth (M) | Growth %  | Current (M) | Projected (M) |
|-------- | -------------- | --------- | ----------- | ------------- |
| 7       | 300            | 42.9      | 700         | 1000          | 
| 5       | 250            | 38.5      | 650         | 900           |
| 1       | 200            | 40.0      | 500         | 700           | 
| 2       | 200            | 33.3      | 600         | 800           | 
| 3       | 200            | 50.0      | 400         | 600           | 

Top GDP contributors (2030):

| Cluster | GDP Growth (M) | Growth %  | Current (M) | Projected (M) |  
| ------- | -------------- | --------- | ----------- | ------------- | 
| 7       | 600            | 85.7      | 700         | 1300          | 
| 5       | 550            | 84.6      | 650         | 1200          |
| 2       | 500            | 83.3      | 600         | 1100          |
| 6       | 460            | 109.5     | 420         | 880           |
| 3       | 450            | 112.5     | 400         | 850           |

## 3. ROI ANALYSIS ON INVESTMENTS AND INCENTIVES

### 3.1 HIGHEST ROI CLUSTERS

Top ROI performers(2025):

| Cluster | ROI 2025%  |  ROI 2030%  |  GDP/Invest |  GDP/Incentive | 
| ------- | ---------- | ----------- | ----------- | -------------- |
| 7       | 20.0       |  30.0       |  0.43       |  2.73          | 
| 5       | 18.0       |  28.0       |  0.42       |  2.50          |
| 10      | 17.0       |  27.0       |  0.38       |  2.22          | 
| 9       | 16.0       |  26.0       |  0.42       |  2.53          | 
| 1       | 15.0       |  25.0       |  0.67       |  4.00          | 

### 3.2 LOWEST ROI CLUSTERS (requiring attention)

Underperforming clusters:

| Cluster | ROI 2025%  |  ROI 2030%  |  GDP/Invest  | Infrastructure% |
| ------- | ---------- | ----------- | ------------ | --------------- |
| 4       | 10.0       |  20.0       |  0.50        | 65              |
| 8       | 11.0       |  21.0       |  0.82        | 72              |
| 2       | 12.0       |  22.0       |  0.40        | 70              |
| 6       | 13.0       |  23.0       |  0.57        | 78              |
| 3       | 14.0       |  24.0       |  0.80        | 75              |

### 3.3 INVESTMENT EFFICIENCY ANALYSIS

Overall performance metrics:

- Average ROI 2025: 14.6%
- Average ROI 2030: 24.6%
- Total Investment: $4290M
- Total Incentives: $710M
- Expected GDP Growth (2025): $2120M
- Overall Investment ROI: 0.49x
- Incentive Efficiency: $2.99 GDP per $1 incentive

## 4. INFRASTRUCTURE vs INVESTMENT CROSS-ANALYSIS

### 4.1 INFRASTRUCTURE READINESS vs INVESTMENT LEVELS

| Cluster | Infrastructure% | Investment/km2 | Completion% | Risk Level  |  
| ------- | --------------- | -------------- | ----------- | ----------- | 
| 1       | 80              | 30.0           | 95          | MEDIUM RISK |
| 2       | 70              | 33.3           | 85          | MEDIUM RISK |
| 3       | 75              | 20.8           | 90          | HIGH RISK   |
| 4       | 65              | 50.0           | 80          | MEDIUM RISK |
| 5       | 85              | 33.3           | 98          | LOW RISK    |
| 6       | 78              | 25.0           | 92          | HIGH RISK   |
| 7       | 90              | 35.0           | 99          | LOW RISK    |
| 8       | 72              | 20.0           | 88          | HIGH RISK   |
| 9       | 82              | 34.6           | 96          | MEDIUM RISK |
| 10      | 88              | 32.5           | 97          | MEDIUM RISK |

### 4.2 CLUSTERS REQUIRING ADDITIONAL INVESTMENT

HIGH RISK CLUSTERS (Immediate Attention Required):

- Cluster 3: Infrastructure 75%, needs ~$145M additional investment
- Cluster 6: Infrastructure 78%, needs ~$111M additional investment
- Cluster 8: Infrastructure 72%, needs ~$142M additional investment

MEDIUM RISK CLUSTERS (Monitor Closely):

- Cluster 1: Infrastructure 80%, completion 95%
- Cluster 2: Infrastructure 70%, completion 85%
- Cluster 4: Infrastructure 65%, completion 80%
- Cluster 9: Infrastructure 82%, completion 96%
- Cluster 10: Infrastructure 88%, completion 97%

### 4.3 INVESTMENT RECOMMENDATIONS

STRATEGIC RECOMMENDATIONS:

- Total additional investment needed: $398M
- Focus on 3 high-risk clusters
- Prioritize infrastructure development over expansion
- Implement milestone-based investment releases
- Consider public-private partnerships for large investments
