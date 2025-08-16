### Project: Defect Density and Code Quality Analysis 📊

This project is a data dashboard that tracks key metrics for software quality, with a focus on **Defect Density** (bugs per thousand lines of code). The goal is to provide actionable insights for a development team to improve their codebase's health and make data-driven decisions. The analysis is based on a simulated dataset of bug reports and codebase size over six months.

***

### Project Methodology

1.  **Data Simulation**: Two realistic datasets were created in Python using `pandas` and `numpy`:
    * `bugs_data.csv`: Contains records of 300 bugs with details like date found, module, team, and severity.
    * `loc_data.csv`: Tracks the lines of code (LOC) for each module monthly.
2.  **Dashboard Creation**: The raw data was processed and visualized using **Tableau Public** (or you can substitute with Python libraries like `pandas` and `plotly` if that's what you used). The tool was used to join the two datasets, create calculated fields for metrics like Defect Density, and build interactive charts.
3.  **Analysis and Storytelling**: The final step involved analyzing the visualizations to identify key trends, pinpoint problem areas, and provide strategic recommendations for improvement.

***

### Key Insights and Findings

Based on the analysis of the dashboard, here are the main takeaways:

* **Positive Quality Trend**: The overall defect density shows a **clear downward trend** from January to June 2025. This indicates that our current quality assurance processes and developer best practices are effective. 
* **Most Problematic Module**: The **Authentication** module consistently has the highest defect density. This part of the codebase is a prime candidate for a comprehensive code review or a refactoring effort to reduce its bug-to-code ratio.
* **Team Performance**: While all teams demonstrate a commitment to quality, **Team B** shows a slightly higher defect density compared to the others. This suggests they might benefit from a targeted training session on unit testing or more frequent code reviews.
* **Risk Profile**: The **Bug Distribution by Severity** chart reveals that the majority of bugs are of `Medium` and `High` severity. This is a crucial insight, as it highlights the need to prioritize fixing bugs with the highest potential impact on system stability and user experience. 

***

### Recommendations for Improvement

Based on these insights, I recommend the following actionable steps:

1.  **Refactoring Sprint**: Schedule a dedicated sprint to refactor and thoroughly test the **Authentication** module to reduce its high defect density.
2.  **Targeted Training**: Organize a workshop for **Team B** to share best practices in testing and quality assurance.
3.  **Continuous Monitoring**: Use this dashboard to continuously monitor quality metrics after each release to ensure that the positive trend continues and that new issues are identified early.

**View the live dashboard here:** https://public.tableau.com/views/DefectDensityandCodeQualityAnalysis/DefectDensityandCodeQualityAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
