# SaaS Revenue Retention & Expansion Model (Google Sheets)

This model calculates Gross Revenue Retention (GRR), Net Revenue Retention (NRR), and MRR expansion over a 12-month period using churn and upsell assumptions.

Built in Google Sheets, this model helps visualize how customer retention and expansion affect recurring revenue over time.

---

## 📊 What It Does

- Simulates monthly MRR retention and growth  
- Calculates GRR and NRR for each month  
- Tracks churned MRR, expansion MRR, and ending MRR  
- Input-driven and easy to modify  

---

## 🧮 Key Formulas

- **Churned MRR** = `Starting MRR × Churn Rate`  
- **Expansion MRR** = `(Starting MRR - Churned MRR) × Expansion Rate`  
- **Ending MRR** = `Starting MRR - Churned MRR + Expansion MRR`  
- **GRR** = `(Starting MRR - Churned MRR) ÷ Starting MRR`  
- **NRR** = `(Ending MRR ÷ Starting MRR)`  

---

## 🧾 How to Use

1. Update the **Starting MRR**, **Churn Rate**, and **Expansion Rate** in the Inputs section.  
2. The model will automatically calculate outputs across 12 months.  
3. Adjust assumptions to test different retention and growth scenarios.  

---

## 📎 Google Sheets Link

[Open the Sheet](https://docs.google.com/spreadsheets/d/1L4AmVdEF6Hy1e_rehi-nYyB-UhzmeyV-97cdkbaXP3k)

---

## 👨‍💻 Author

Built by [Timothy T. Pham](https://github.com/TimothyTPham)
