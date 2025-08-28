Life Expectancy Analysis
📌 About the Dataset

This project explores the factors affecting life expectancy across 193 countries from 2000–2015. Unlike earlier studies that focused mainly on demographic and income variables, this dataset also considers immunization factors (Hepatitis B, Polio, Diphtheria), the Human Development Index, and a broader set of health, social, and economic indicators.

The dataset consists of:

2938 rows (country-year records)

22 columns (1 target variable — Life Expectancy, and 20 predictors)

Variables grouped into categories:

Immunization-related factors

Mortality factors

Economic factors

Social factors

The data was collected from the WHO Global Health Observatory and United Nations.

🎯 Project Goal

The aim is to build regression models (Multiple Linear Regression and Mixed Effects Models) to determine which factors truly influence life expectancy, and how governments can use these insights to improve public health.

🔑 Key Questions

This analysis seeks to answer:

Which variables significantly affect life expectancy?

Should countries with low life expectancy (<65 years) increase healthcare expenditure?

How do infant and adult mortality rates influence lifespan?

What is the relationship between life expectancy and lifestyle choices (smoking, alcohol, diet, exercise)?

What role does schooling play in human lifespan?

Does population density affect life expectancy?

How does immunization coverage contribute to longevity?

📂 Dataset Information

Source: WHO Global Health Observatory, UN Data Repository

Time period: 2000–2015

Countries: 193

Missing data: Mainly for population, Hepatitis B, and GDP (common in small island nations like Vanuatu, Tonga, Cabo Verde).

Preprocessing: Missing data handled in R (Missmap), with countries having too many gaps excluded.

⚙️ How to Run This Project
1️⃣ Clone the repository
git clone https://github.com/your-username/life-expectancy-analysis.git
cd life-expectancy-analysis

2️⃣ Install dependencies

If you’re using Python:

pip install -r requirements.txt


If you’re using R, open the .R file and install necessary packages:

install.packages(c("tidyverse", "lme4", "ggplot2", "Amelia"))

3️⃣ Run the analysis

For Python → run the Jupyter Notebook:

jupyter notebook


and open life_expectancy_analysis.ipynb.

For R → open life_expectancy_analysis.R in RStudio and run the code.
