# Weekly-Growth-Analysis-of-Application-Users-
This just for storage or sharing purpose not for active development
## Overview  
This project analyzes **weekly user growth** by categorizing users into four segments:  
- **New Users**: First-time users in a given week  
- **Retained Users**: Users who were active in the previous week and are still active  
- **Resurrected Users**: Users who were inactive in the previous week but returned  
- **Churned Users**: Users who were active previously but are no longer active  

Additionally, key growth metrics like **Retention Rate** and **Quick Ratio** are calculated to evaluate user engagement and growth trends.  

## Key Metrics & Formulas  

### 1. Retention Rate  
The **Retention Rate** measures how many users continue using the app over time.  

\[
Retention\ Rate = \left( \frac{\text{Retained Users}}{\text{Users from Previous Week}} \right) \times 100
\]  

### 2. Quick Ratio  
The **Quick Ratio** evaluates user growth efficiency by comparing new and resurrected users to churned users.  

\[
Quick\ Ratio = \frac{\text{New Users} + \text{Resurrected Users}}{\text{Churned Users}}
\]  

A Quick Ratio **greater than 1** indicates growth, while a value **below 1** suggests user decline.  
