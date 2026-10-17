# Netflix-content-distribution
mini project

# Project Description

This project analyzes Netflix's global collection of movies and TV shows to understand what content is on the platform, who it is made for, and where it comes from. The raw data was first cleaned, organized, and prepared in Microsoft Excel. Then, it was imported into Power BI to build an interactive dashboard with charts, filters, and cards that clearly show key trends and patterns.

# Project Objectives

- Perform comprehensive data pre-processing

- handling missing values

- standardizing attributes

- eliminating inconsistencies within Excel.

- Establish a dimensional data model (Star Schema) separating facts and dimensions to optimize reporting performance.

- Build an interactive, executive-ready Power BI dashboard featuring dynamic KPI cards, drill-downs, cross-filtering, and visualizations.
  
   
# Dataset Description
- Source: [Netflix Movies and TV Shows Dataset (Kaggle)]
  
https://www.kaggle.com/datasets/lovishbansal123/netflix-dataset

- Total Records:8,807 titles

- Attributes:12 features (`show_id`, `type`, `title`, `director`,
`cast`, `country`, `date_added`,
`release_year`, `rating`, `duration`, `listed_in`, `description`)

#Tools used
- Microsoft Excel
- POWER BI Desktop

# Data Pre-Processing in Excel

- Handling missing values

- Standardizing formats

- Categorized each audience segment using the VLOOKUP function

- Calculated columns created for:

- Added year(dim_date):	extracted from the date using YEAR date function

- Added month(dim_date):	extracted using date function to evaluate monthly patterns.

# Key Insights & Findings

•	Movies vs. TV Shows: Most of the content consists of movies (about 70%), while TV shows make up around 30%.

•	Audience: Most titles are made for adults and teens (mainly TV-MA and TV-14 ratings).

•	Top Countries: The United States produces the highest number of shows, followed by India, the UK, Japan, and South Korea.

•	Movie Length: The average movie is about 100 minutes long.

•	Platform Growth: The number of titles added grew very quickly after 2016, reaching a peak between 2018 and 2020.

# Conclusion
​This project successfully analyzed Netflix's catalog by cleaning and preparing the data in Microsoft Excel and building an interactive dashboard in Power BI. The findings show that Netflix focuses primarily on movies, caters mainly to adult and teen audiences, and has built most of its library through rapid content growth led by regions like the United States and India. Overall, the dashboard provides a clear, visual way to understand the platform's key streaming trends.







