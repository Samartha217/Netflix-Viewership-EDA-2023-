# Netflix-Viewership-EDA-2023-

This project presents an exploratory data analysis (EDA) and visualization dashboard of Netflix's 2023 content performance. It aims to uncover strategic patterns in viewership behavior based on content type, release timing, language, and more — providing actionable insights for content planning and product decisions.

---

## 📌 Objectives

- Analyze total hours viewed by content type. (e.g., Movies vs Shows)
- Examine language-based performance patterns.
- Discover seasonal trends and monthly peaks.
- Compare release count vs viewership.
- Identify the best days and months for content drops.

---

## 📊 Tools & Libraries

- Python
- Pandas – Data cleaning & manipulation  
- Plotly – Interactive visualizations  
- Colab – Development environment  

---

## 📈 Key Visualizations

| Analysis Area | Chart Type |
|---------------|------------|
| Content Type Performance | Bar Chart |
| Language-wise Trends | Bar Chart |
| Monthly Release vs Viewership | Dual-Axis Line + Bar |
| Seasonal Viewership | Bar Chart |
| Release Day Effectiveness | Dual-Axis Line + Bar |
| Genre-Level Trends | (Optional extension) |

All visualizations are interactive, cleanly styled, and aligned to business storytelling.

---

## 📥 Dataset

- Source: Provided as `netflix_content_2023.csv`
- Columns include:
  - `Title`, `Content Type`, `Language`, `Release Date`, `Hours Viewed`, etc.

---

## 💡 Insights Summary

- **Shows consistently outperformed movies** in total watch time  
- **June and December** were peak months for viewership, suggesting release timing optimization  
- **English and Korean** content dominated in hours viewed  
- **Friday** emerged as the most strategic release day  
- Releasing fewer but **high-quality shows in summer and winter** could improve engagement

---

## 📌 How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the dataset `netflix_content_2023.csv`
3. Run each section step-by-step to reproduce visual insights
4. Extend or fork the project to experiment with:
   - Genre-level patterns
   - Engagement per release
   - Cross-year trends

---
