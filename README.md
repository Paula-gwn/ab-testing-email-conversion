## 🧪 Project Summary
- **Objective**: Compare the performance of two email designs (Version A vs Version B) using simulated user conversion data.
- **Key Metric**: Conversion Rate (percentage of users who clicked "Buy Now").
- **Dataset**: Simulated dataset with 5,000 users per group.

---

## 📂 Files in This Repository

- `AB_Testing_Report.pdf` — A complete written report
- `ab_testing_analysis.ipynb` — Jupyter Notebook with simulation, analysis, and visualizations 
- `README.md` — This documentation file

---

## 📈 Methodology

1. Simulate A/B test results with NumPy and Pandas
2. Analyze conversion rate differences
3. Apply a Chi-Square Test for statistical significance
4. Visualize results using Matplotlib and Seaborn

---

## 🧪 Results Summary

| Group | Total Users | Conversions | Conversion Rate |
|-------|-------------|-------------|-----------------|
| A     | 5,000       | 611         | 12.22%          |
| B     | 5,000       | 741         | 14.82%          |

- ✅ Version B outperformed Version A with a **statistically significant** improvement (p = 0.00003).

---

## 🛠️ Tools Used

- Python 🐍
- Pandas & NumPy for data handling
- SciPy for hypothesis testing
- Matplotlib & Seaborn for visualization
- ReportLab for PDF generation

---

## 📌 Conclusion

The test results support the rollout of Version B to improve marketing performance. This project demonstrates how A/B testing can be used to guide data-driven decisions.

---

## 🚀 Future Work

- Test subject line variations
- Optimize CTA placement
- Analyze email open rates

---
