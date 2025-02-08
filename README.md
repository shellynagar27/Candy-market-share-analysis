# Candy Market Share Analysis
 - [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGJlMjQzNzYtZmY4OS00YmRiLWEyNTQtNDg4NWM3ZDRjMzQ3IiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9)
 - [Linkedin Post](https://www.linkedin.com/feed/update/urn:li:activity:7271093984687542272?utm_source=share&utm_medium=member_desktop)
 - [Challenge details](https://zoomcharts.com/en/microsoft-power-bi-custom-visuals/challenges/fp20-analytics-november-2024?loginSuccess=1)

## Overview
This project was created as part of the **FP20 Analytics November 2024 Challenge**. It analyzes market share dynamics in the European confectionery industry, leveraging **Power BI for visualization, Python and Power Query for exploratory data analysis (EDA), and Figma for UX design**. Freepik and Flaticon were used for icons.

## Dataset
The dataset originates from a leading European market research company specializing in the confectionery industry. It provides detailed information on major manufacturers, their brands, packaging, and sales volumes within a specific regional market. 

The objective of this analysis is to visualize market trends, conduct category-level analysis, and explore consumption volumes over time. The insights generated will support strategic decision-making for company researchers.

## Key Questions Addressed
This Power BI report aims to answer the following questions:

1. What are the **top 10 candy items by sales volume (weight) in 2022 and 2023**?
2. What are the **top 10 candy items by sales volume (monetary value) in 2022 and 2023**?
3. How has **candy sales volume (weight) trended monthly from 2022 to 2023**?
4. Which **manufacturer had the highest sales volume (EUR) in 2022**?
5. Which **manufacturer had the lowest sales volume (weight) in 2023**?
6. What **package type** is the most popular for sales by weight?
7. Which **candy category** generated the most revenue?
8. Which **candy brand sold the most chips in 2022**?
9. Which **candy brand sold the most chocolate-related candies in 2023**?
10. What is the **most profitable distribution channel** for selling candies?

## Dataset Structure
The dataset consists of multiple sheets:
- **Candy Data** – The main dataset containing sales information.
- **Dictionary** – Provides a description of each column.
- **Measure Table** – Stores all created measures.
- **Calendar Table** – A separate table for date-based analysis.

Additional components:
- **Field Parameter** – Enables a slicer to switch between "Items", "Brands", "Manufacturer", "Category", "Distribution Channel", "Package Type" and "Product Type".

## Data Model
![Screenshot 2025-02-08 111830](https://github.com/user-attachments/assets/db1786e0-d7a2-4ad3-9a59-e1f1f1a0267f)

## Methodology
### 1. Data Processing
- **Data Exploration**: Understanding key variables and relationships.
- **Data Cleaning**: Removing extra whitespaces, handling duplicates.
- **Data Transformation & Formatting**:
  - Created a date column.
  - Ensured proper formatting and data types.
  - Generated a **Calendar** table for time-based analysis.

### 2. Data Modeling
- Established relationships between the **Candy Data (fact table)** and the **Calendar (dimension table)** table.
- Created necessary **measures** for analysis.

### 3. Visualization & Interactivity
- Built Power BI **visualizations** to answer the key business questions.
- Designed **slicers** to enhance report interactivity.
- Created an **Information Page** to guide users on navigating charts and slicers.

---
## Key Findings
_(To be added later)_

---
## Recommendations
_(To be added later)_

---
### Tools Used
- **Power BI** – Data visualization and dashboard creation.
- **Python & Power Query** – Data exploration and transformation.
- **Figma** – UX design.
- **Freepik & Flaticon** – Icons for visualization.

## Conclusion
This project provides a comprehensive analysis of candy market share, offering valuable insights into manufacturer performance, category trends, and sales distribution. The Power BI report facilitates data-driven decision-making for industry researchers.

---
## Future Scope
- Enhancing **UX design** for better interactivity.
- New insights to be addded.

---
🔍 For more details, feel free to explore the repository and interact with the Power BI dashboard.

If you have any queries, suggestions, or feedback regarding this project, feel free to reach out.

---
### Author
Shelly Nagar
 - LinkedIn Profile-[https://www.linkedin.com/in/shellynagar/](https://www.linkedin.com/in/shellynagar/)
 - Email- [shelly.nagar@outlook.com](mailto:shelly.nagar@outlook.com)
