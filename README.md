![us](https://github.com/PratimaPrabhakar/Python-webscrapping-project/assets/155467894/5b78374c-dd7d-48dd-a650-fafe645f3810)

 **Analysis of largest companies of United States by revenue**

This project involves web scraping and data analysis using Python to gain insights into the largest companies in United states by revenue. The target site for data collection is List of largest companies in the United States by revenue - Wikipedia.

**Project Overview**

In this project, we will scrape data from wikipedia.org and perform data analysis to understand the largest companies currently in the United States by revenue as of 2023, according to the Fortune 500 tally of companies and Forbes. The analysis will involve visualizing top 5 companies by revenue and revenue growth, percentage of companies in top 10 industries, correlations between revenue and employees, and corelation heatmap to understand the relation between different variables.

**Getting Started**

To start working on this project, follow these steps:
1.	Clone this repository to your local machine.
2.	Run the web scraping script to collect data from wikipedia.org.
3.	Load the collected data into your preferred data analysis environment (e.g., Jupyter Notebook).
4.	Explore the dataset's columns, data types, and structure to understand the available information.
   
**Analysis and Insights**

The bar charts visually represent the top five companies based on their revenue and revenue growth, providing a clear snapshot of their comparative performance. In the "Top 5 Companies by Revenue" chart, each bar corresponds to a company, with the height of the bar indicating the respective revenue in USD millions. This visualization allows for a quick and easy comparison of revenue figures among the top performers.

![Bar_graphs_top5](https://github.com/PratimaPrabhakar/Python-webscrapping-project/assets/155467894/0a16d6be-178e-40b0-9832-f82250b7db6a)

![Bar_graph_by_revenue_growth](https://github.com/PratimaPrabhakar/Python-webscrapping-project/assets/155467894/105a8404-7aba-458c-8422-aee872b43d8e)

Similarly, in the "Top 5 Companies by Revenue Growth" chart, the bars represent companies ranked by their revenue growth percentages. The length of each bar reflects the growth rate, offering a visual comparison of how each company is positioned in terms of revenue expansion.

![Pie_chart_top10_comapnies_by_industry](https://github.com/PratimaPrabhakar/Python-webscrapping-project/assets/155467894/5d2bd18c-9a9d-453c-a13a-b079093676fe)

The pie chart illustrates the distribution of companies across the top 10 industries based on the provided dataset. Each slice of the pie represents a specific industry, and the size of each slice corresponds to the percentage of companies operating within that industry relative to the total. This visual representation offers a concise overview of the concentration of businesses in different sectors.

![Scatter_plot](https://github.com/PratimaPrabhakar/Python-webscrapping-project/assets/155467894/44b5876f-92c7-4aec-a78e-3342dcef9d97)

By examining the scatter plot, patterns or trends between revenue and employee count can be identified. The dispersion of points provides insights into whether there is a correlation or any discernible relationship between these two variables. Additionally, the inclusion of a line of best fit aids in visually estimating the overall trend in the data.

![Heat_map](https://github.com/PratimaPrabhakar/Python-webscrapping-project/assets/155467894/af42d5bc-8292-4169-b89a-14aea815e879)

 is a graphical representation of the correlation matrix that illustrates the relationships between different variables such as Revenue, Revenue Growth, and Employees in a dataset. 
This visualization is instrumental in identifying patterns and dependencies between different factors in the dataset

**Conclusion:**

In this project, we successfully extracted data from a sample website, structured it into a Data Frame, and performed a variety of analyses and visualizations. The primary objectives were to identify and explore the top companies by revenue, revenue growth, and the distribution of industries.
Overall, this project demonstrated the capability to extract, process, and visualize data effectively. These analytical insights are valuable for stakeholders, decision-makers, and researchers looking to understand and interpret patterns within the corporate landscape. The methodologies employed in this project can be adapted and extended for more extensive datasets and diverse analyses in the field of data science and business intelligence.
