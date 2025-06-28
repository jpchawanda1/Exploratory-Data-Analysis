
# 💎 Diamond Pricing Analysis using EDA in R

This project performs an Exploratory Data Analysis (EDA) on the `diamonds` dataset using R. The goal is to uncover key pricing drivers such as **cut**, **clarity**, and **color**, and to develop visual tools and metrics to guide optimal diamond selection.

---

## 📊 Project Highlights

- **Dataset**: Built-in `diamonds` dataset from `ggplot2` (contains 54,000+ records).
- **Tools Used**: `ggplot2`, `dplyr`, `tidyr`, `patchwork`
- **Key Insights**:
  - Cut and clarity significantly influence diamond pricing.
  - Ideal cut with IF clarity offers the highest value (price/carat).
  - Developed a custom **value index** to filter mid-range options for best buys.

---

## 🛠️ Features

- Clean and structured data preprocessing using `dplyr` and `tidyr`
- Informative visualizations: boxplots, heatmaps
- Combined plots for comparative analysis using `patchwork`
- Data-driven recommendations for buyers and sellers

---

## 📁 File Overview

- `Exploratory-Data-Analysis.Rmd`: Main analysis and report generation in RMarkdown
- Outputs: HTML report (generated from the `.Rmd`)

---

## 📌 Getting Started

To run this analysis:
```r
# Install required packages (if not already)
install.packages(c("ggplot2", "dplyr", "tidyr", "patchwork"))

# Open and knit the RMarkdown file
rmarkdown::render("Exploratory-Data-Analysis.Rmd")

```

## 🧠 Author

**Justice Chawanda**  
Exploratory Data Analysis enthusiast, focused on practical data insights.
