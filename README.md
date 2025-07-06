# 📈 Marketing Mix Modeling (MMM) – Excel-Based Simulation

This project showcases an end-to-end Marketing Mix Modeling (MMM) workflow built entirely in Microsoft Excel using **simulated 30-week data**. The objective was to explore the influence of media spends on sales, apply key transformation techniques like **adstock** and **diminishing returns**, and optimize advertising spend to minimize **Cost per Output (CPO)**.

---

## 🧠 Project Highlights

- ✅ Simulated 30 weeks of weekly marketing data (3 media spend variables + 1 sales column)
- ✅ Performed exploratory data analysis (scatter plots, Pearson correlation)
- ✅ Built a baseline linear regression model  
  • R² = 0.84  
  • RMSE = 2.05  
  • MAPE = 12%
- ✅ Checked for multicollinearity using VIF
- ✅ Applied **adstock** and **diminishing return** transformations
- ✅ Tuned hyperparameters (decay & alpha) to improve model
- ✅ Final model performance:  
  • R² = 0.88  
  • RMSE = 1.73  
  • MAPE reduced from 12% to 10%
- ✅ Used **Excel Solver** to optimize marketing budget allocation
- ✅ Achieved **CPO = ₹26.77** for predicted sales of **1.47**

---

## 📊 Key Techniques Used

- **Adstock Transformation** – Models carryover effects of advertising
- **Diminishing Returns** – Captures saturation of media impact
- **Solver Optimization** – Finds lowest possible CPO for given budget
- **Manual Hyperparameter Tuning** – For best-fit decay and saturation rates
- **Data Visualization** – Includes scatter plots, diminishing curves, and adstock decay trends

---

## 📂 Tools & Technologies

| Tool            | Purpose                                |
|-----------------|----------------------------------------|
| **Microsoft Excel** | Data modeling, transformation, Solver optimization |
| **Excel Charts** | Visualizing patterns & results        |
| **Formulas & Logic** | Entire model built without macros or external code |

---

## 🧾 Use Case

This project is ideal for:
- Practicing MMM logic when real business data is unavailable
- Demonstrating modeling capabilities in Excel for interviews or portfolios
- Understanding adstock, saturation, and regression in a hands-on way

---

## 📌 Repository Structure (If Applicable)

