# DATE:JUNE 2026 TASK:01 OBJECTIVE : DATA EXPLORATION & CLEANING

#  Shopping Dataset — Data Exploration & Cleaning

![Python](https://img.shields.io/badge/Python-3.14-blue)
![Pandas](https://img.shields.io/badge/Pandas-3.0-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Objective
Learn Python basics and perform data exploration 
and cleaning using Pandas on a real Kaggle dataset.

## Dataset
- **Source:** Kaggle — Shopping Dataset
- **Link:** https://www.kaggle.com/datasets/anvitkumar/shopping-dataset
- **Size:** 1000+ rows, 20+ columns

## Tasks Completed
| Step | Task | Status |
|------|------|--------|
| 1 | Load CSV into DataFrame | *WEEK 1 COMPLETED* |
| 2 | Explore data (head/tail/shape/dtypes) |  *WEEK 1 COMPLETED* |
| 3 | Handle missing values |  *WEEK 1COMPLETED* |
| 4 | Filter rows & select columns |  *WEEK 1 COMPLETED* |
| 5 | Remove duplicates |  *WEEK 1 COMPLETED* |
| 6 | Create total_amount column |  *WEEK 1 COMPLETED* |
| 7 | Save cleaned CSV |  *WEEK 1 COMPLETED*~~ |

## 🧹 Cleaning Summary
- **Missing Values Fixed:** what_customers_said, seller_name, videos, variations, discount
- **Duplicates Removed:** Yes
- **New Column Added:** total_amount = initial_price × ratings_count

## 📊 Key Insights
- High rated products (4.0+) identified
- Discount median used for missing values
- Dataset cleaned from raw to analysis-ready

## 🛠️ Tools Used
- Python 3.14
- Pandas
- NumPy
- Jupyter Notebook (VS Code)

## 📁 Files
| File | Description |
|------|-------------|
| `analysis.ipynb` | Main Jupyter Notebook |
| `cleaned_dataset.csv` | Cleaned output file |

## 📖 What I Learned
- **Variables, Loops, Control Flow** - Python basics
- **Lists & Dictionaries** - Data structures
- **read_csv(), head(), info(), describe()** - Dataset exploration
- **Filtering & Grouping** - Data operations
- **Redundancy & Normalization** - Data quality
- **Missing Values & Duplicates** - Data cleaning

## 📈 Dataset Insights
- Total Products: 1000+
- Categories: Clothing, Electronics, Footwear
- High Rated Products (4.0+): Identified & filtered
- Missing Values Fixed: 5 columns cleaned
- New Column Created: total_amount

## 🚀 How to Run
1. Clone this repo
```bash
   git clone https://github.com/Sumit-2706/pandas-data-cleaning.git
```
2. Install requirements
```bash
   pip install pandas numpy
```
3. Open `analysis.ipynb` in VS Code
4. Run All cells

## 👤 Author
**SUMIT KUMAR SINGH**
**Internship Project — Data Engineering**