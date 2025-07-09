# Netflix Data SQL Analysis – Project Overview

This project presents an SQL-based analysis of a dataset named `netflix_data_1`, focused on exploring trends and insights from Netflix's content library. The analysis includes content distribution over time, genre trends, maturity rating distributions, language analytics, and detection of duplicate entries.

---

## Dataset Description

The dataset (`netflix_data_1`) contains the following key fields:

- **title**: The name of the Netflix content.
- **release_year**: The year in which the content was released.
- **main_genre**: The primary genre category.
- **sub_genre**: Additional genre categorization.
- **maturity**: Age/maturity rating (e.g., PG, R, TV-14).
- **original_audio**: Original language of the content.
- **recommendation**: Textual review or recommendation attached to the content.

---

## Key Insights and Queries Performed

- **Data Loading and Structure**: Checked the total entries, verified the schema, and loaded the full table for review.
- **Content Release Trends**: Identified the range of release years and calculated the number of titles released each year.
- **Genre Distribution**: Analyzed both main and sub-genres, highlighting the most common ones and checking for any missing or null values.
- **Maturity Rating Trends**: Assessed how content ratings vary by year and in general distribution.
- **Language Analysis**: Identified top original audio languages used in Netflix content.
- **Region-Specific Trends**: Counted the number of titles that include references to "Us" in the sub-genre field.
- **Recommendations**: Measured the average length of recommendations across different genres.
- **Duplicate Detection**: Found repeated titles and their rows using grouping and common table expressions (CTEs).

---

## Notes

- This project is part of a broader data analysis portfolio.
- SQL was used as the primary querying tool, and outputs were interpreted for insights.
- All code is documented in a separate Word file uploaded to GitHub.
- Ideal for demonstrating exploratory SQL querying, business intelligence preparation, and report generation.

