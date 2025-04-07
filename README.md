# 🏃‍♀️ PCA & Bi-Plot Analysis on Heptathlon Data

This project applies **Principal Component Analysis (PCA)** and **biplot visualization** to the Heptathlon dataset, offering insights into the performance patterns of female athletes across seven track and field events.

## 📂 Project Overview

The Heptathlon dataset includes athlete performance in:
- 100m Hurdles
- High Jump
- Shot Put
- 200m Run
- Long Jump
- Javelin Throw
- 800m Run

Each athlete has a calculated **total score**, which we use to analyze and categorize performance levels.

---

## 🎯 Objectives

- Perform PCA to reduce dimensionality and identify key components of variance.
- Create a **biplot** to visualize contributions of individual events to principal components.
- Categorize scores into performance bins: **Low**, **Medium**, and **High**.

---

## 🧠 Key Concepts

- **PCA** was used to identify latent patterns in the event data.
- **scoreCat**: A new categorical variable based on total score (`Low`, `Medium`, `High`).
- **Biplot**: Visualizes the athletes’ scores and the contribution of each event to PC1 and PC2.

---

## 📊 PCA Results

| Component | Standard Deviation |
|-----------|---------------------|
| PC1       | 2.0845              |
| PC2       | 1.1486              |
| PC3       | 0.7676              |

> PC1 and PC2 together capture a significant portion of the dataset's variance.

---

## 📌 Insights from the Biplot

- Arrows represent original variables, showing their contribution to PC1 and PC2.
- **run800m** has a strong positive correlation with PC1.
- **Shot put** and **javelin** show strong negative contributions to PC1.
- Athletes are clearly separated into **Low** (red), **Medium** (green), and **High** (blue) score categories in the biplot.

---

## 📁 Dataset Source

The dataset comes from the R built-in `heptathlon` dataset.

---

## 📎 Repository Link

👉 [GitHub Repository](https://github.com/annissapereira/PCA--Bi-plot)

---

## 👩‍💻 Author

**Annissa Ajit Pereira**  
Course: POM 681 – Business Analytics and Data Mining (Fall 2024)  
University of Massachusetts Dartmouth


