# 💎 Diamonds Price Visualization Project

## 📌 Project Overview
This project explores how diamond prices are influenced by the **Four Cs** —  
**Carat, Cut, Color, and Clarity** — using a structured **explanatory data visualization** approach.

The analysis follows a clear progression:
- 🔍 **Univariate exploration** (individual variables)
- 🔗 **Bivariate exploration** (relationships between two variables)
- 🧩 **Multivariate exploration** (interactions between multiple variables)
- 🎨 **Explanatory polishing** (clean, audience-ready visualizations)

The goal is not prediction, but **understanding and communicating** which quality attributes matter most for diamond pricing.

---

## 📊 Dataset Description
The dataset contains information on approximately **54,000 round-cut diamonds**, collected in **2008**, with the following key variables used in this project:

### 🔢 Numerical Variable
- **price** 💰 — Diamond price in US dollars

### 💎 The Four Cs (Categorical Quality Measures)
- **carat** ⚖️ — Diamond weight (1 carat = 0.2 grams)
- **cut** ✂️ — Cut quality: Fair → Good → Very Good → Premium → Ideal
- **color** 🎨 — Color grade: J → I → H → G → F → E → D (best)
- **clarity** 🔍 — Clarity grade: I1 → SI2 → SI1 → VS2 → VS1 → VVS2 → VVS1 → IF

Other physical dimensions (x, y, z, depth, table) exist in the dataset but are **not the focus** of this case study.

---

## 🔍 Analysis Structure

### 1️⃣ Univariate Exploration
- Distribution of diamond prices and carat weights
- Identification of strong right-skewness and outliers
- Logarithmic transformations used **only to improve visual interpretability**

📌 *Purpose:* Understand individual variable behavior.

---

### 2️⃣ Bivariate Exploration
- Price vs. carat relationships
- Apparent paradox: higher quality grades initially appear cheaper
- Visualization reveals **confounding effects** between carat size and quality

📌 *Purpose:* Detect misleading marginal relationships.

---

### 3️⃣ Multivariate Exploration
- Conditioning price comparisons on fixed carat values
- Clear evidence that **higher cut, color, and clarity increase price**
- Cubic transformations used to visually relate linear dimensions to volume-related effects

📌 *Purpose:* Isolate true quality effects from size effects.

---

### 4️⃣ Explanatory Polishing 🎨
- Selection of the most informative plots
- Clean labels, consistent color palettes, and focused narratives
- Removal of intermediate exploratory noise

📌 *Purpose:* Communicate insights clearly to a non-technical audience.

---

## 💡 Key Findings
- **Carat weight is the dominant driver of diamond price**
- The apparent negative relationship between quality and price is due to **smaller diamonds tending to have higher quality**
- When controlling for carat, **better cut, color, and clarity consistently increase price**
- Log and power transformations are used as **visual tools**, not modeling assumptions

---

## 🎯 Final Takeaway
This project demonstrates how **careful visualization design** prevents incorrect conclusions and reveals the true influence of diamond quality on pricing.

📊 *Good visualization doesn’t just show data — it explains reality.*

---

## 🛠️ Tools & Techniques
- Python (Jupyter Notebooks)
- pandas, matplotlib, seaborn
- Explanatory Data Analysis (EDA)
- Visual transformations for interpretability

---

✨ *Designed as a clean, end-to-end example of explanatory data visualization.*
