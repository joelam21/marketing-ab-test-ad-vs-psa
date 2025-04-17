# 📈 Marketing A/B Test — Ad vs. PSA Campaign

This project analyzes a synthetic A/B test dataset comparing the effectiveness of two marketing approaches: a paid **Ad** versus a **Public Service Announcement (PSA)**. The objective is to determine which strategy leads to a higher user conversion rate using statistical rigor and clear visual storytelling.

---

## 🔍 Project Objectives

- Evaluate whether the **Ad group** leads to significantly more conversions than the **PSA group**
- Use **hypothesis testing**, **bootstrapping**, and **visual analysis** to support conclusions
- Provide business recommendations based on statistical evidence

---

## 📁 Folder Structure

```
MARKETING_AB_TEST/
├── data/                      # Data files (original or preprocessed)
├── notebooks/
│   └── marketing_ab_test.ipynb    # Main analysis notebook
├── visuals/                   # Bootstrap plots, charts, confidence intervals
├── requirements.txt           # Python package dependencies
├── README.md                  # You're here!
└── .gitignore                 # Files/folders to exclude from Git versioning
```

---

## 🧪 Methodology Summary

1. **Formulated Hypotheses**
   - H₀: No difference in conversion rates between groups
   - H₁: Ad group has a higher conversion rate than PSA group

2. **Set Significance Level**
   - α = 0.05

3. **Calculated Statistical Power**
   - Sample size requirements confirmed via power analysis

4. **Performed Z-Test**
   - One-tailed Two-Proportion Z-Test to detect directional improvement

5. **Visualized Confidence**
   - Bootstrap resampling (1,000 iterations) with 95% CI
   - Clear visual separation in distributions

6. **Measured Uplift**
   - **Absolute Lift**: 0.77 percentage points
   - **Relative Lift**: 43.09% improvement

---

## 📊 Results

- **Ad Conversion Rate**: 2.55%  
- **PSA Conversion Rate**: 1.78%  
- **p-value**: < 0.001  
- ✅ **Null Hypothesis Rejected**: The Ad group significantly outperformed the PSA group

---

## 💬 Business Implication

The Ad campaign drove **43% more conversions** than the PSA — a statistically significant and business-relevant difference.

**Recommendation:**  
Continue investing in ad-based strategies. Consider testing creative variations or segmenting user groups to refine targeting.

---

## 🧠 Learning Focus

This project showcases:

- End-to-end A/B testing workflow
- Statistical testing with **`statsmodels`**
- Bootstrapping for confidence visualization
- Clear storytelling and business framing

---

## 🧰 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- `statsmodels` for statistical testing
- `scipy` for exact methods
- Jupyter Notebook
- PowerPoint for presentation

---

## 📦 Setup Instructions

1. Clone the repository  
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run `notebooks/marketing_ab_test.ipynb`

---

## 📂 Dataset

- **Source**: [Kaggle Marketing A/B Test Dataset](https://www.kaggle.com/datasets/arezaei81/marketing-ab-test)
- **Note**: This is a synthetic dataset designed for learning and experimentation.

---

## 📣 Final Thoughts

This A/B test highlights how even small percentage changes in conversion can drive meaningful business outcomes when paired with strong statistical confidence.

---

## 🔗 Author & Contact

GitHub: [@joelam21](https://github.com/joelam21)  
Questions? Ideas? Feedback welcome!