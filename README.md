# Python-Project by Samukelisiwe Thwala
----
# 📊 COVID-19 Data Analysis: Kenya, South Africa, and Lesotho

## 📝 Project Overview

This project analyzes COVID-19 data with a specific focus on three African countries: **Kenya**, **South Africa**, and **Lesotho**. It explores case trends, death rates, vaccination rollout, and comparative analysis across countries using data visualization and statistical methods.

---

## 📌 Key Features

- Clean and preprocess COVID-19 data using `pandas`
- Handle missing values and convert date fields
- Filter and analyze data for specific countries
- Calculate key metrics such as death rate and vaccination percentage
- Generate visualizations:
  - Bar charts (top countries by total cases)
  - Line charts (cases, deaths, vaccinations over time)
  - Pie charts (vaccinated vs. unvaccinated)
- Provide a Markdown-based narrative and summary table with insights

---

## 🧰 Tools and Libraries Used

| Library         | Purpose                                        |
|-----------------|------------------------------------------------|
| `pandas`        | Data manipulation and preprocessing            |
| `matplotlib`    | Data visualization                             |
| `seaborn`       | Enhanced statistical plotting (optional)       |
| `numpy`         | Numerical operations                           |
| `Jupyter`       | Interactive notebook environment               |

---

## 📁 Dataset

The dataset used is the **[Our World in Data COVID-19 dataset]**. It contains:
- Daily case and death numbers
- Vaccination counts
- Country-level statistics

### Columns used in this project:
- `date`
- `location` (country name)
- `total_cases`
- `new_cases`
- `total_deaths`
- `total_vaccinations`
- `people_vaccinated` (if available)
- `population` (if not present, added manually)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/covid19-country-analysis.git
cd covid19-country-analysis
