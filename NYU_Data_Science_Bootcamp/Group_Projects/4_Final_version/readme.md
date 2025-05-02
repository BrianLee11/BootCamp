# 🌏 Air Quality in India: Policy, Trends, and Prediction

## 📊 NYU Data Science Bootcamp Final Project
**Team Name**: *Data Scientists*  
**Presentation Date**: Friday, May 2, 2025, 12PM – 2PM

---

## 🚀 Project Overview

This project explores India’s air pollution trends across time and regions, with a special focus on **policy impacts**—particularly the **CNG mandate in Delhi (2001–2003)**. Through data analysis, visualization, and machine learning models, we aimed to answer:

> **“Does Delhi have cleaner air due to stricter CNG policies?”**

Our work combines **temporal decomposition, regional variation analysis**, and **predictive modeling** to evaluate the effectiveness of environmental regulations.

---

## 📌 Key Questions

1. **Policy Impact**  
   - India launched the **Auto Fuel Policy (2003)** introducing Euro-style BS-I and BS-II norms.
   - Delhi enforced a **strict CNG mandate (2001–2003)** for public transport.

2. **Temporal Trends**
   - Do pollution levels change over time?  
   ✅ **Yes** — Significant differences found between 1987–1989 and 2003–2014 (Two-group t-test).
   - How much does time contribute to variation?  
   ✅ **Yes** — Confirmed via **time-series decomposition** (trend, seasonality, residual).

3. **Regional Variation**
   - Does air quality differ by region?  
   ✅ **Yes** — Statistical dispersion measures (StdDev, IQR, Skew, Kurtosis) show clear variation.
   - Do differences between cities and states matter?  
   ❌ **No** — State/city distinction was not statistically significant.

---

## 🧠 Predictive Modeling

We built models to predict **SO₂ and NO₂** levels using time, region, and lag features:

| Model       | Description |
|-------------|-------------|
| **Random Forest** | Uses many "mini-expert" trees to make robust predictions |
| **XGBoost** | Learns iteratively by correcting mistakes from previous trees |
| **LSTM**    | Remembers long-term patterns in time-series pollution data |

📈 **Best R² score achieved**: `0.63` on validation set.

---
---

## 📌 Conclusion

✅ Delhi **does** have cleaner air following the CNG mandate  
✅ Temporal and regional factors significantly affect pollution levels  
✅ Predictive modeling is feasible and meaningful (R² = 0.63)  

---

## 📎 References

- India Air Quality Dataset (Kaggle / StatLib CMU)
- Indian Auto Fuel Policy Reports
- BS Emission Norms (2000–2003)
- Scikit-learn, XGBoost, TensorFlow, and Matplotlib

---

## 🙏 Acknowledgments

Thank you to the NYU Data Science Bootcamp faculty and peers for their support.




