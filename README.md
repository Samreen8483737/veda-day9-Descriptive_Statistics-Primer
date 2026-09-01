## Objective
Calculate and interpret mean, median, standard deviation, and percentiles for a dataset's key numeric columns to understand data distribution, skew, and spread.
## 1. Summary Statistics Table (Titanic Dataset)

| Statistic | Age (Years) | Fare (Ticket Price) |
| :--- | :--- | :--- |
| **count** | 714.00 | 891.00 |
| **mean** | 29.70 | 32.20 |
| **std** | 14.53 | 49.69 |
| **min** | 0.42 | 0.00 |
| **25%** | 20.12 | 7.91 |
| **50%** (Median) | 28.00 | 14.45 |
| **75%** | 38.00 | 31.00 |
| **max** | 80.00 | 512.33 |

---
## 2. Analysis Write-Up: Skew and Spread
**Analyzing "Fare" (Massive Right Skew)**
* **Skewness:** By comparing the mean to the median, we can instantly spot a massive right skew in the ticket fares. The mean fare is 32.20, but the median (50th percentile) is only 14.45. When the mean is significantly higher than the median, it indicates that a few extreme outliers are pulling the average up. 
* **Spread:** The standard deviation is 49.69, which is larger than the mean itself. This indicates a massive spread in the data. Looking at the percentiles, 75% of passengers paid 31.00 or less, yet the maximum ticket price was 512.33. This shows that while most people bought cheap tickets, a tiny handful of elite passengers bought incredibly expensive suites.
**Analyzing "Age" (Relatively Normal Distribution)**
* **Skewness:** The Age column is much more symmetrical. The mean age (29.70) is very close to the median age (28.00). This tells us the data is fairly evenly distributed without an extreme skew.
* **Spread:** The standard deviation is 14.53. Because the mean is roughly 30, we know that the majority of passengers were between the ages of 15 and 45. The percentiles confirm this: the middle 50% of the data (from the 25th to the 75th percentile) sits neatly between 20 and 38 years old.
