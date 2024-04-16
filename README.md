Comparative Analysis of Anti-Cancer Drug Regimens for Squamous Cell Carcinoma

![pharmaceutical-industry](https://github.com/IsmaelG8/Pymaceuticals/assets/128990362/33ef82bf-1327-4ce1-81e4-9d9609b868b9)

Project Overview:

I undertook a comprehensive data analysis project at Pymaceuticals, Inc., focusing on evaluating the efficacy of various anti-cancer drug regimens, including the company’s drug of interest, Capomulin, in treating squamous cell carcinoma (SCC). The analysis involved advanced data manipulation and visualization techniques to provide insights that will guide future drug development and strategies.

Objective:

The primary objective of this project was to analyze the performance of different drug regimens on SCC tumor development over 45 days, utilizing data from 249 mice. The analysis aimed to identify the most effective treatments, thereby assisting Pymaceuticals in optimizing their research and development investments.

Technical Execution:

Data Preparation:

Merged the mouse_metadata and study_results DataFrames to create a comprehensive dataset.
Ensured data integrity by removing duplicates and confirming the number of unique mice IDs after cleanup.
Generate Summary Statistics:

Produced a DataFrame of summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.
Visualization:

Created bar charts using both Pandas and Matplotlib to show the number of data points for each drug regimen.
Generated pie charts to illustrate the distribution of female versus male mice.
Advanced Statistical Analysis:

Calculated quartiles and interquartile ranges to identify potential outliers in tumor volumes for the most promising treatment regimens.
Displayed these statistics using box plots to visualize distribution and outliers.
Focused Drug Analysis:

Selected a single mouse treated with Capomulin to create a line plot of tumor volume over time, highlighting the drug’s effectiveness.
Created a scatter plot to examine the relationship between mouse weight and average tumor volume under the Capomulin regimen.
Correlation and Regression Analysis:

Calculated the correlation coefficient and developed a linear regression model to explore the relationship between mouse weight and tumor volume for mice treated with Capomulin, enhancing understanding of factors influencing treatment efficacy.
Outcomes:

The analysis successfully identified Capomulin as a highly effective treatment regimen among those tested, demonstrating significant potential in reducing tumor sizes. Statistical and visual analyses confirmed Capomulin’s superior performance, supporting its prioritization in further clinical trials.

Summary:

The project highlighted Capomulin’s efficacy in a controlled study environment, with implications for its future development as a leading anti-cancer drug by Pymaceuticals, Inc. The findings suggest further exploration of dosage and combination therapy trials to maximize its therapeutic benefits.

Future Recommendations:

For subsequent analyses, I recommend incorporating more diverse datasets involving human trials to validate these findings. Additionally, exploring genetic markers that influence treatment response could offer personalized medicine approaches, potentially revolutionizing cancer treatment strategies.
