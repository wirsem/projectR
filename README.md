# 📊 projectR — Customer Segmentation & Data Visualization in R

An R-based data analysis project covering customer data exploration, segmentation, and multi-series data visualization using `ggplot2` and base R functions.

---

## 📁 Project Structure

| File | Description |
|---|---|
| `customer_segmentation.R` | Customer data exploration and segmentation — includes data type checking, structural analysis, and aggregate statistics by gender, profession, and annual spending |
| `visualisasi Histogram.R` | Histogram-based distribution visualization for exploratory data analysis |
| `visualisasi rules dengan graph.R` | Graph-based visualization of association rules from market basket analysis |
| `viusalisasi.R` | Multi-series line chart visualization of employee productivity across months using `ggplot2`, with annotations highlighting peak performance |

---

## 🔍 What This Project Covers

**Customer Segmentation (`customer_segmentation.R`)**
- Converting raw data into a proper R DataFrame using `as.data.frame()`
- Inspecting data with `head()`, `tail()`, and `str()`
- Checking column data types using `lapply()` with `class`
- Aggregating insights:
  - Average age by gender (`Jenis.Kelamin`)
  - Total count per profession (`Profesi`)
  - Average annual spending per profession (`NilaiBelanjaSetahun`)

**Data Visualization (`viusalisasi.R`)**
- Multi-series line chart with `ggplot2` comparing productivity of employees A, B, C, D, and E across months
- Highlighting top performer (Karyawan E) with `darkblue` emphasis
- Custom annotations using `annotate()` to label peak productivity and per-employee averages
- Dynamic labels using `paste()` and `toString()` for real-time stat display

---

## 🛠️ Tools & Libraries

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![RStudio](https://img.shields.io/badge/RStudio-75AADB?style=flat&logo=rstudio&logoColor=white)

```r
library(ggplot2)   # Data visualization & multi-series line charts
library(dplyr)     # Data manipulation
library(arules)    # Association rule mining
library(arulesViz) # Graph-based rule visualization
```

---

## 🚀 How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/wirsem/projectR.git
   ```

2. Open any `.R` file in **RStudio**

3. Install required packages if not already installed:
   ```r
   install.packages(c("ggplot2", "dplyr", "arules", "arulesViz"))
   ```

4. Run the script line by line or use **Source** in RStudio

---

## 👤 Author

**Wira Tarumta Timothy Sembiring**
- 🔗 [LinkedIn](https://linkedin.com/in/wira-tarumta-timothy-sembiring)
- 🐙 [GitHub](https://github.com/wirsem)
