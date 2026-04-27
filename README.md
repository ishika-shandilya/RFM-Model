# 🛍️ RFM Customer Segmentation — Superstore Dataset

Most businesses treat all customers the same. This project shows why that's a mistake.

---

## 💡 Problem Statement

Retail businesses often spend marketing budgets uniformly across their customer base — 
rewarding loyal customers and churning ones with the same message.

This project uses **RFM Analysis** to segment customers by actual behavior, so businesses 
can act differently for different segments.

**RFM stands for:**
- **Recency** — How recently did the customer purchase?
- **Frequency** — How often do they purchase?
- **Monetary** — How much do they spend?

---

## 📈 Key Findings

- Identified distinct customer segments: Champions, Loyal Customers, At-Risk, and Lost
- Champions drove disproportionately higher revenue despite being a small % of customers
- At-Risk segment showed high historical spend but recent inactivity — prime targets for win-back campaigns
- Lost customers had low recency, frequency, and monetary scores — indicating minimal recovery potential

---

## ⚙️ Tech Stack

- **Python** — Pandas, NumPy, Matplotlib, Seaborn
- **Dataset** — Sample Superstore (retail transactions)

---

## 📊 Approach

1. Calculated R, F, M scores for each customer using transaction history
2. Scored each metric on a 1–4 scale using quartile-based binning
3. Combined scores into a composite RFM segment label
4. Visualized segment distribution and revenue contribution

---

## 💼 Business Implications

| Segment | Recommended Action |
|---|---|
| Champions | Reward them, ask for reviews |
| Loyal Customers | Upsell higher-value products |
| At-Risk | Send personalized win-back offers |
| Lost | Low priority — minimal spend on reactivation |

---

## 🚀 Outcome

Shifted customer strategy from one-size-fits-all marketing to **behavior-based segmentation**, 
enabling targeted retention and higher ROI on marketing spend.
