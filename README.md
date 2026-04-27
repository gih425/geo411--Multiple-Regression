#Title
Improved Linear Regression Model for Housing Prices

#Overview

This project improves a base linear regression model used to predict housing prices. The goal was to address issues in the original model, including unrealistic coefficient signs, omitted variables, and violations of regression assumptions, while increasing the model’s explanatory power.

---

# **c. Methods**

The base model was modified by transforming the dependent variable to the natural logarithm of price to reduce skewness and improve model assumptions. Additional housing variables (floors, waterfront, and lot size) were included to better capture property characteristics. Less effective variables were removed, and socioeconomic indicators were improved by replacing HS and SC with BACH and prop_poverty. The improved model was evaluated using R², adjusted R², and diagnostic plots.

---

# **d. Key Findings**

The improved model has a higher R² and similar adjusted R², indicating better explanatory power without overfitting. Coefficient signs are now more realistic, and diagnostic plots show improved adherence to regression assumptions. Variables such as square footage, bathrooms, and waterfront location positively influence price, while poverty levels negatively impact price.

---

# **e. Tools**

* R
* Linear regression (`lm()` function)
* Diagnostic plots (`plot()` in R)

---

# **f. Reflection**

This project demonstrated how model specification significantly impacts results. Small changes, such as transforming variables and selecting more appropriate predictors, can greatly improve model performance and interpretation. It also highlighted the importance of checking assumptions rather than relying solely on statistical output.

---

If you want, I can make a **slightly more “A-level” version** (stronger wording) or format it as a **downloadable Word/PDF** 👍
