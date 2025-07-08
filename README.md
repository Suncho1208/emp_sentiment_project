# Employee Sentiment Analysis Project

## Overview

This project analyzes employee messages to determine sentiment, rank employees by engagement, identify flight risks, and build a predictive model of sentiment trends.

---

## Results Summary

### Top 3 Positive Employees (January 2010)

| Employee                  | Sentiment Score |
|----------------------------|-----------------|
| kayne.coulter@enron.com   | 9               |
| don.baughman@enron.com    | 5               |
| eric.bass@enron.com       | 5               |

### Top 3 Negative Employees (January 2010)

| Employee                     | Sentiment Score |
|-------------------------------|-----------------|
| rhonda.denton@enron.com     | 2               |
| bobette.riner@ipgdirect.com | 2               |
| johnny.palmer@enron.com     | 0               |

---

### Flight Risk Employees

The following employees were flagged as flight risks due to sending 4 or more negative emails in any rolling 30-day window:

- eric.bass@enron.com
- don.baughman@enron.com
- rhonda.denton@enron.com
- bobette.riner@ipgdirect.com
- lydia.delgado@enron.com
- patti.thompson@enron.com
- johnny.palmer@enron.com
- sally.beck@enron.com
- john.arnold@enron.com

---

## Key Insights and Recommendations

- **Most engaged employees** demonstrated high positive sentiment scores consistently.
- **Flight risks** were identified across multiple departments, suggesting targeted retention interventions may be needed.
- **Predictive modeling** indicated that message frequency is a stronger predictor of sentiment than message length.
- **Recommendation:** Monitor negative sentiment spikes monthly and conduct 1-1 check-ins with flagged employees to reduce attrition risk.

---

## Usage

Run the Jupyter notebook `employee_sentiment_analysis.ipynb` to reproduce all analyses.

