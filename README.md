# zomato-growth-analysis-2022-2024
In-depth analysis of Zomato’s business transformation from FY22 to FY24 using annual report data. Includes metrics like GOV, adjusted revenue, PAT, marketing ROI, and efficiency ratios.



# 🚀 Zomato’s Business Growth: 2022–2024 📊

This repository presents an analysis of Zomato’s financial and operational performance from FY22 to FY24 using insights from their **Annual Report 2024**. It tracks growth in core business metrics, user monetization, marketing efficiency, and profitability.

---

## 🔑 Key Highlights

| Metric                    | FY22        | FY24        | Growth      | Insight |
|---------------------------|-------------|-------------|-------------|---------|
| Gross Order Value (GOV)   | ₹21,297 Cr  | ₹47,918 Cr  | +125%       | Massive growth in food delivery |
| Adjusted Revenue          | ₹5,541 Cr   | ₹13,545 Cr  | +144%       | Topline growth across B2C + B2B |
| Adjusted EBITDA           | ₹-973 Cr    | ₹372 Cr     | Improved    | Strong turnaround |
| EBITDA                    | ₹-1,861 Cr  | ₹42 Cr      | Profitability Achieved | All-inclusive profitability |
| Profit After Tax (PAT)    | ₹-1,223 Cr  | ₹351 Cr     | Profit Achieved | Key milestone |

---

## 📊 Marketing & Efficiency Metrics

| Metric                     | Value       | Insight |
|----------------------------|-------------|---------|
| Ad Spend                   | ₹1,432 Cr   | Total annual spend |
| Ad Spend as % of Revenue   | 10.6%       | Down from 14.1% YoY |
| Avg Monthly Users          | 23.5M       | Large user base |
| Ad Spend/User              | ₹5.08/month | Efficient cost |
| Revenue/User               | ₹48/month   | 9x return on marketing |

---

## 📈 Profitability Ratios

| Ratio                   | Formula                            | Value  | Meaning |
|-------------------------|-------------------------------------|--------|---------|
| PAT-to-GOV              | (351 / 47,918) × 100                | 0.73%  | ₹0.73 profit per ₹100 order value |
| PAT-to-Adjusted Revenue | (351 / 13,545) × 100                | 2.59%  | ₹2.59 profit per ₹100 earned |

---

## 🧠 Key Takeaways

- ✅ **Zomato is now profitable**, with growing GOV and strong cost control.
- 🧮 **Smarter marketing**: Lower ad-to-revenue ratio, higher ROI per user.
- 💸 **Efficient monetization**: Every ₹1 in ads leads to ₹9 in revenue.
- 📈 A true case of **scale + efficiency = sustainable growth**.

---

## 🔍 Zomato’s Business Verticals

| Segment           | Description |
|-------------------|-------------|
| 🍽️ Food Delivery  | Zomato App  |
| 🚀 Quick Commerce | Blinkit     |
| 🎉 Dining & Events| Going Out   |
| 🧾 B2B Supplies   | Hyperpure   |

---

## 📂 Bonus: Python Code to Visualize Revenue & Profitability

```python
import matplotlib.pyplot as plt

years = ['FY22', 'FY24']
adjusted_revenue = [5541, 13545]
pat = [-1223, 351]

plt.bar(years, adjusted_revenue, label='Adjusted Revenue (₹ Cr)', color='orange')
plt.plot(years, pat, label='PAT (₹ Cr)', marker='o', color='green')

plt.title("Zomato's Growth & Profitability (FY22–FY24)")
plt.xlabel("Year")
plt.ylabel("Amount (₹ Cr)")
plt.legend()
plt.grid(True)
plt.tight_layout()
plt.show()

