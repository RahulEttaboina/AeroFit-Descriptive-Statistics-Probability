# AeroFit Descriptive Statistics & Probability Analysis

## 📌 Project Overview

This project analyzes AeroFit treadmill customer data to identify customer characteristics associated with each treadmill product and to support better product recommendations.

The analysis focuses on **Exploratory Data Analysis (EDA), descriptive statistics, customer segmentation, marginal probability, conditional probability, and customer profiling**.

The original business case asks the market research team to understand differences in customer characteristics across AeroFit treadmill products and use those insights for improved product recommendations.

---

## 🎯 Business Objective

The key objectives of this analysis are to:

- Understand the characteristics of AeroFit treadmill customers.
- Analyze the distribution of demographic, behavioral, and financial variables.
- Identify relationships between customer characteristics and treadmill products.
- Calculate marginal and conditional probabilities.
- Build customer profiles for each treadmill model.
- Translate the analysis into practical marketing and product recommendations.

---

## 📊 Dataset

The dataset contains **180 customer records** and **9 variables**:

| Column | Description |
|---|---|
| `Product` | Treadmill model purchased |
| `Age` | Customer age |
| `Gender` | Customer gender |
| `Education` | Years of education |
| `MaritalStatus` | Customer marital/relationship status |
| `Usage` | Expected treadmill usage per week |
| `Fitness` | Self-rated fitness level |
| `Income` | Annual income |
| `Miles` | Expected weekly running/walking mileage |

### Products

- **KP281**
- **KP481**
- **KP781**

The analysis found no missing values in the dataset. KP281 is the most frequently purchased product. The dataset contains 104 male customers and 76 female customers.

---

## 🔍 Analysis Performed

### 1. Exploratory Data Analysis

- Dataset structure and dimensions
- Data types
- Missing-value checks
- Unique product identification
- Descriptive statistics
- Distribution analysis

### 2. Univariate Analysis

Analyzed the distributions of:

- Age
- Education
- Usage
- Fitness
- Income
- Miles

Used:

- Histograms
- KDE plots
- Box plots
- Count plots
- Pie charts

### 3. Outlier Analysis

Box plots were used to investigate potential outliers.

Key observation:

- Age, Education, and Usage contain relatively few outliers.
- Income and Miles show more pronounced outliers.

### 4. Bivariate Analysis

Examined relationships between treadmill product and:

- Gender
- Marital Status
- Age
- Education
- Usage
- Fitness
- Income
- Miles

### 5. Multivariate Analysis

Analyzed customer characteristics across product and gender combinations using grouped box plots and pair plots.

### 6. Probability Analysis

Calculated:

- Marginal probability
- Conditional probability
- Two-way contingency tables

Probability analysis was performed across:

- Gender
- Age group
- Education group
- Income group
- Weekly mileage group
- Marital status
- Weekly treadmill usage
- Fitness level

### 7. Customer Profiling

Customer profiles were developed for each treadmill model based on the observed characteristics and probability analysis.

---

## 📈 Key Findings

### Product Distribution

The overall product distribution in the analysis was approximately:

| Product | Share |
|---|---:|
| KP281 | 44% |
| KP481 | 33% |
| KP781 | 22% |

### Customer Demographics

- Male customers represent approximately **58%** of the dataset.
- Partnered customers represent approximately **59%** of the dataset.
- KP281 is the most frequently purchased treadmill model.

### Product & Customer Characteristics

The analysis identified several patterns:

- KP281 and KP481 customers have similar median ages.
- Customers aged approximately 25–30 show greater representation among KP781 purchasers.
- Customers with education above 16 years show greater representation among KP781 purchasers.
- Higher expected treadmill usage is associated with greater representation of KP781 purchasers.
- Higher fitness levels show greater representation among KP781 purchasers.
- Customers with income above approximately $60,000 show greater representation among KP781 purchasers.
- Customers expecting higher weekly mileage show greater representation among KP781 purchasers.

These are **observed associations in the analyzed dataset**, not causal conclusions.

---

## 👥 Customer Profiles

### KP281

Typical characteristics identified in the analysis:

- Age: mainly 18–35
- Education: 13+ years
- Income: below approximately $60,000
- Weekly usage: 2–4 times
- Fitness: 2–4
- Weekly mileage: approximately 50–100 miles

### KP481

Typical characteristics identified in the analysis:

- Age: mainly 18–35
- Education: 13+ years
- Income: approximately $40,000–$80,000
- Weekly usage: 2–4 times
- Fitness: 2–4
- Weekly mileage: approximately 50–200 miles

### KP781

Typical characteristics identified in the analysis:

- Gender: predominantly male in the observed data
- Age: mainly 18–35
- Education: 15+ years
- Income: approximately $80,000+
- Weekly usage: 4–7 times
- Fitness: 3–5
- Weekly mileage: 100+ miles

---

## 💡 Business Recommendations

Based on the analysis:

### 1. Targeted Marketing for KP781

Develop targeted campaigns aimed at customer segments that show stronger representation among KP781 purchasers, while also exploring strategies to increase female adoption.

### 2. Affordable Pricing & Payment Plans

Position KP281 and KP481 with accessible pricing and flexible payment options for customers in their identified income segments.

### 3. Fitness & Usage-Based Recommendations

Use customer fitness level, expected weekly usage, and mileage as inputs when recommending treadmill models.

### 4. Digital Product Experience

A treadmill companion application could track usage and mileage and provide personalized workout recommendations based on customer goals and activity levels.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Descriptive Statistics
- Probability Analysis
- Exploratory Data Analysis

---

## 📁 Repository Structure

```text
AeroFit-Descriptive-Statistics-Probability/
│
├── README.md
├── aerofit_treadmill.txt
├── Aerofit_Case_Study.ipynb
└── Aerofit_Case_Study.pdf
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/RahulEttaboina/AeroFit-Descriptive-Statistics-Probability.git
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook Aerofit_Case_Study.ipynb
```

Make sure `aerofit_treadmill.txt` is in the same directory as the notebook.

---

## 📄 Project Files

- **Notebook:** Complete Python analysis and visualizations.
- **Dataset:** AeroFit treadmill customer data used by the notebook.
- **PDF:** Exported version of the completed analysis.
- **README:** Project documentation and business insights.

---

## 📚 Project Context

This project was completed as part of a Data Analytics business-case learning exercise. The analysis and documentation demonstrate practical application of Python, exploratory data analysis, descriptive statistics, probability, and business interpretation.

