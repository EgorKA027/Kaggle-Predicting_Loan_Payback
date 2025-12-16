# 💰 Predicting Loan Payback | Kaggle Playground Series S5E11

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Competition-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/competitions/playground-series-s5e11)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

## 📌 Overview
This repository contains the solution for the **Kaggle Playground Series - Season 5, Episode 11: Predicting Loan Payback**. 

The goal of this competition is to predict whether an applicant will repay a loan based on various demographic and financial factors. The dataset is synthetic, generated from a deep learning model trained on the standard Loan Prediction Problem dataset.

**Competition Link:** [Playground Series S5E11](https://www.kaggle.com/competitions/playground-series-s5e11)

## 📂 Repository Structure

The project is divided into two main notebooks to separate analysis from modeling:

| File | Description |
| :--- | :--- |
| `Predicting_loan_payback_EDA.ipynb` | **Exploratory Data Analysis**. Contains data visualization, missing value analysis and initial insights into feature distributions. |
| `Predicting_loan_payback_MODEL.ipynb` | **Modeling Pipeline**. Model training (Gradient Boosting and MLP), hyperparameter tuning, and submission generation. |

## 📊 Exploratory Data Analysis (EDA)

Key insights and steps performed in the `Predicting_loan_payback_EDA.ipynb` notebook:

*   **Data Quality Check:** Analysis of missing values in columns like `Gender`, `Married`, `Dependents`, `Self_Employed`, `LoanAmount`, and `Loan_Amount_Term`.
*   **Target Distribution:** Checking for class imbalance in the `Loan_Status` target variable.
*   **Feature Distributions:** Visualizing numeric features (ApplicantIncome, CoapplicantIncome) and categorical features to identify outliers and skewness.

## 🤖 Modeling Approach

The solution in `Predicting_loan_payback_MODEL.ipynb` follows this pipeline:

1.  **Model Selection:**
    *   Using of Gradient Boosting algorithms (e.g., **XGBoost**, **CatBoost**, **LightGBM**) and NN (**RealMLP**).
      
2.  **Evaluation:**
    *   Metric: **ROC AUC** (Area Under the Receiver Operating Characteristic Curve).

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed or install the requirements:

```bash
pip install -r requirements.txt
```

---

## 📌 Обзор
Этот репозиторий содержит решение для **Kaggle Playground Series - Season 5, Episode 11: Predicting Loan Payback**.

Цель этого соревнования — предсказать, погасит ли заявитель кредит, основываясь на различных демографических и финансовых факторах. Набор данных является синтетическим, сгенерированным моделью глубокого обучения, обученной на стандартном наборе данных для задачи прогнозирования кредитов.

**Ссылка на соревнование:** [Playground Series S5E11](https://www.kaggle.com/competitions/playground-series-s5e11)

## 📂 Структура репозитория

Проект разделен на два основных блокнота для разделения анализа и моделирования:

| Файл | Описание |
| :--- | :--- |
| `Predicting_loan_payback_EDA.ipynb` | **Исследовательский анализ данных**. Содержит визуализацию данных, анализ пропущенных значений и первоначальные выводы о распределении признаков. |
| `Predicting_loan_payback_MODEL.ipynb` | **Конвейер моделирования**. Обучение моделей (градиентный бустинг), настройку гиперпараметров и генерацию результатов. |

## 📊 Исследовательский анализ данных (EDA)

Ключевые выводы и шаги, выполняемые в блокноте `Predicting_loan_payback_EDA.ipynb`:

* **Проверка качества данных:** Анализ пропущенных значений в столбцах, таких как `Gender`, `Married`, `Dependents`, `Self_Employed`, `LoanAmount` и `Loan_Amount_Term`.

* **Распределение целевой переменной:** Проверка на дисбаланс классов в целевой переменной `Loan_Status`.

* **Распределение признаков:** Визуализация числовых признаков (доход заявителя, доход созаявителя) и категориальных признаков для выявления выбросов и асимметрии.

## 🤖 Подход к моделированию

Решение в файле `Predicting_loan_payback_MODEL.ipynb` следует следующему алгоритму:

1. **Выбор модели:**

* Использование алгоритмов градиентного бустинга (например, **XGBoost**, **CatBoost**, **LightGBM**) и нейронных сетей (**RealMLP**).
  
2. **Оценка:**

* Метрика: **ROC AUC** (площадь под кривой).

## 🚀 Начало работы

### Необходимые условия
Убедитесь, что у вас установлен Python или установите зависимости:

```bash
pip install -r requirements.txt
```
