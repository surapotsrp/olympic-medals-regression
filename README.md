# 🏅 Predicting Olympic Medals Using Regression Models

This project investigates how GDP and population influence the number of medals won in the 2012 Olympic Games. It applies multiple regression techniques, model comparison via AIC, and a Poisson-based probability estimate for Great Britain.

📄 **Full Report:** [Using Regression Models to Predict Olympic Medals (PDF)](./Using%20Regression%20Models%20to%20Predicting%20the%20Olympic%20Games.pdf)

---

## 📊 Project Highlights

### 🔹 Task 1: Linear Regression  
- Inputs: GDP, Population  
- Output: Medal count in 2012 Olympics  
- Result: GDP is significant; Population is not

### 🔹 Task 2: Log-Transformed Linear Regression  
- Improved model performance (AIC ↓ from 553 → **201**)  
- Handles skewed data & outliers  
- GDP remains significant; Population still not

### 🔹 Task 3: Quadratic Regression  
- Added squared terms for non-linearity  
- Captured **diminishing returns** in GDP → Medal relationship  
- AIC improved vs Task 1 but not Task 2

### 🔹 Task 4: Model Selection (via AIC)  
- Best model = **Log-Transformed Linear Regression**  
- Justified by AIC, model simplicity, and interpretability

### 🔹 Task 5: Real-World Application (UK Medals)  
- Used selected model to predict UK’s medal count  
- Estimated ~10.43 medals  
- Calculated **probability of UK winning ≥1 medal** = **99.997%**

---

## 🛠 Tools Used

- **Language:** R  
- **Packages:** `ggplot2`, `dplyr`, `caret`, `glm`, `boot`, `poisson`  
- **Evaluation Metrics:** AIC, confidence intervals, significance testing

---

## 💡 Key Takeaways

- **GDP is a consistent and significant predictor** of Olympic success  
- **Log-transformation improves model performance** for skewed outcome data  
- Poisson-based probability estimation adds real-world interpretability

---

## 👤 Author

**Surapot Nonpassopon**  
MSc Data Science and Analytics – University of Leeds  
📂 GitHub Portfolio: [github.com/surapotsrp](https://github.com/surapotsrp)
