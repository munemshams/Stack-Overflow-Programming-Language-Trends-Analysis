# Stack Overflow Programming Language Trends Analysis

This project analyzes programming language popularity using data from **Stack Overflow**, one of the largest developer communities in the world.

Stack Overflow questions are tagged with programming languages and technologies. By analyzing the number of questions associated with each tag over time, we can estimate the popularity of different programming languages and identify trends in developer activity. 

This analysis focuses on understanding:

- The popularity of the **R programming language**
- The percentage of Stack Overflow questions tagged with R in **2020**
- The **five most discussed programming languages between 2015 and 2020**
- Trends in programming language popularity over time

---

# Project Overview

Programming languages evolve constantly, and developers must decide which technologies to learn and invest time in. One way to understand these trends is by analyzing developer discussions on platforms like Stack Overflow.

Since Stack Overflow contains millions of programming questions, the frequency of tags related to different languages can provide insights into which technologies are widely used and actively discussed in the developer community.

This project uses Stack Overflow data to analyze programming language popularity trends and visualize how developer interest has evolved over time. This project was completed using **R**.

---

# Dataset

The dataset used in this project contains yearly counts of Stack Overflow questions tagged with different programming languages.

| Column | Description |
|------|-------------|
| year | The year the question was asked |
| tag | Programming language or technology tag |
| num_questions | Number of questions with that tag |
| year_total | Total number of Stack Overflow questions asked that year |

The dataset covers **2008–2020**.

---

## Libraries Used

The following R libraries were used in this project:

- **readr** – loading CSV datasets  
- **dplyr** – data transformation and aggregation  
- **ggplot2** – data visualization  
- **scales** – formatting axis values and percentages  

These libraries were used for:

- loading and cleaning data
- transforming datasets
- calculating percentages
- generating visualizations

---

# Analysis Approach

The analysis follows these steps:

1. Load and inspect the Stack Overflow dataset  
2. Calculate the percentage of questions associated with each programming language  
3. Analyze the popularity of **R over time**  
4. Identify the **five most discussed programming languages between 2015 and 2020**  
5. Visualize programming language trends using charts  

This workflow helps reveal how developer interest changes over time.

---

# Key Insights

Several insights emerged from the analysis:

- Stack Overflow data provides a strong indicator of developer interest in programming languages.
- The **R programming language** maintains a consistent presence due to its importance in data science and analytics.
- A small number of programming languages dominate most developer discussions.
- Trends in Stack Overflow questions can help identify emerging technologies.

---

# Files Included

| File | Description |
|-----|-------------|
| `stack_overflow_language_trends.Rmd` | R Markdown notebook containing the full analysis |
| `stack_overflow_language_trends.html` | Knitted HTML output of the analysis |
| `stack_overflow_language_trends_report.pdf` | Written report summarizing the analysis |
| `stack_overflow_data.csv` | Dataset used for the analysis |
| `visuals/` | Folder containing generated charts and visualizations |
| `README.md` | Project documentation |

---

# Visualizations

The analysis includes visualizations such as:

- Popularity of **R over time**
- Trends of the most discussed programming languages
- Comparison of language popularity between **2015–2020**

These charts help illustrate changes in developer interest across technologies.

---
