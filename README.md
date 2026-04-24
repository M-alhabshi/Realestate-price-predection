# 🏠 Aqar Saudi Real Estate Price Predictor

A data science project focused on estimating rental prices for villas in Saudi Arabia using machine learning.

## 🛠️ Technologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## ⚙️ Methods
* **Outlier Detection:** Applied the **Interquartile Range (IQR)** method to remove extreme price listings and stabilize the model.
* **Dimensionality Reduction:** Grouped hundreds of low-frequency districts into an **"Other"** category to prevent overfitting and reduce feature noise.
* **Encoding:** Utilized **One-Hot Encoding** with `drop_first=True` to handle categorical data (City, Front, District) while avoiding the **Dummy Variable Trap**.
* **Regression:** Implemented **Linear Regression** to calculate feature-based price coefficients and provide an interpretable valuation formula.

## 📊 Results
The model achieved high predictive accuracy for the standard residential market:
* **Train $R^2$ Score:** 0.8872
* **Test $R^2$ Score:** 0.8809
* **Reliability:** Residual analysis confirmed a normal distribution of errors, proving the model captures market trends effectively without being biased by extreme values.

## 👥 Team Members
* **Abdullah bin Maneea**
* * **Abdullah AlOud**
* **Faris Abuthnain**
* **Mohammad Alaqid**
* **Malik Alhabashi -ME-**

