# 📈 NormalDistribution_CI_R

Simulation of normal samples and confidence interval estimation in **R**.  
Моделирование выборок из нормального распределения и построение доверительных интервалов в **R**.

---

## 📌 About / О проекте

🎓 Developed as part of a course on post-statistical methods of machine learning.  
💡 Demonstrates generation of normal samples, visualization (QQ-plots, histograms), calculation of numerical characteristics, and construction of confidence intervals.  
📦 Explores the effect of sample size on point estimates and interval width.  

🎓 Разработано в рамках курса по статистическим методам машинного обучения.  
💡 Демонстрирует генерацию выборок из нормального распределения, визуализацию (QQ-графики, гистограммы), вычисление числовых характеристик и построение доверительных интервалов.  
📦 Исследует влияние объема выборки на точечные оценки и ширину интервала.  

---

## 🔧 Features / Возможности

- 🎲 Sample generation from Normal(μ, σ) with sizes N = 100, 500, 1000  
  Генерация выборок из Normal(μ, σ) для N = 100, 500, 1000

- 📊 QQ-plots and histograms for normality assessment  
  QQ-графики и гистограммы для проверки нормальности

- 🧮 Sample statistics: mean, variance, standard deviation  
  Выборочные характеристики: среднее, дисперсия, СКО

- 📐 Confidence intervals for the mean:  
  - Known variance (σ² given)  
  - Unknown variance (σ² estimated from sample)  
  Доверительные интервалы для мат. ожидания:  
  - Дисперсия известна (σ² задана)  
  - Дисперсия неизвестна (оценивается по выборке)

- 📈 Plot of sample means and confidence intervals vs sample size  
  График зависимости средних и доверительных интервалов от объема выборки

---

## 📁 Structure / Структура

- **Step 1** — Generate samples of size 100, 500, 1000  
  *Генерация выборок объемом 100, 500, 1000*

- **Step 2** — QQ-plots & histograms  
  *QQ-графики и гистограммы*

- **Step 3** — Numerical characteristics (mean, variance, std)  
  *Числовые характеристики (среднее, дисперсия, СКО)*

- **Step 4** — Confidence intervals (σ² known)  
  *Доверительные интервалы при известной дисперсии*

- **Step 5** — Confidence intervals (σ² unknown)  
  *Доверительные интервалы при неизвестной дисперсии*

- **Step 6** — Plots of point estimates and CI boundaries vs N  
  *Графики зависимости точечных оценок и границ ДИ от объема выборки*

---
