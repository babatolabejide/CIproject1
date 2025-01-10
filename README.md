# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)
# Retail Sales Data Analysis

**Project Goal** Analyze retail sales data to identify trends, insights, and the impact of promotional markdowns on sales, and provide visually appealing sales reports.

## Dataset Content
The dataset contains historical sales data for 45 stores in various regions, capturing the performance of different departments within those stores. The data is segmented into three main Excel sheets:

**1. Stores:**
* Store Type: The type of store (e.g., A, B, C).
* Size: The size of the store in square feet.

**2. Features:**
* Date: The date of the entry.
* Store: Store identifier.
* Temperature: Average temperature in the region.
* Fuel Price: Cost of fuel in the region.
* CPI: Consumer Price Index.
* Unemployment: Unemployment rate.
* IsHoliday: Boolean indicating if the week includes a holiday.

**3. Sales:**
* Store: Store identifier.
* Dept: Department identifier.
* Date: The date of the sales entry.
* Weekly_Sales: Sales amount for the given week.



## Business Requirements
To ensure that the Retail Sales Data Analysis project meets the business objectives and adds value, the following business requirements are defined:

**1. Trend and Seasonal Analysis:**
* Objective: Identify and understand sales trends and seasonal patterns across different stores and departments.
* Business Value: Helps in strategic planning and stocking decisions by anticipating high and low sales periods.

**2. Promotional Effectiveness:**
* Objective: Analyze the impact of promotional markdowns on sales, particularly during holiday periods.
* Business Value: Assists in optimizing promotional strategies to maximize sales and profitability.

**3. Comparative Performance:**
* Objective: Compare sales performance across various stores and regions, factoring in store types and sizes.
* Business Value: Aids in identifying high and low-performing stores to inform resource allocation and targeted interventions.

**4. Descriptive Insights:**
* Objective: Provide basic descriptive statistics, such as average sales per store and department.
* Business Value: Gives a snapshot of current performance, allowing for quick assessments and decisions.

**5. Forecasting and Predictive Analysis:**
* Objective: Predict future sales based on historical data and identified trends.
* Business Value: Supports inventory management and helps in aligning supply with anticipated demand.

**6. Data-Driven Decision Support:**
* Objective: Create comprehensive and visually appealing sales reports and dashboards.
* Business Value: Enhances decision-making processes by providing clear, actionable insights.
## Hypothesis and Validation
* Hypothesis 1: Promotional markdowns significantly increase sales during holiday periods compared to non-holiday periods.
Validation Approach:
Data Segmentation: Split the sales data into holiday and non-holiday periods.
Statistical Tests: Use t-tests or ANOVA to compare sales between these periods.
Visualization: Create plots comparing sales trends during holiday and non-holiday weeks, focusing on periods with promotional markdowns.
* Hypothesis 2: Larger stores have higher average sales than smaller stores.
Validation Approach:
Data Analysis: Calculate average sales per store and categorize them by store size.
Statistical Tests: Use correlation analysis and regression models to examine the relationship between store size and sales.
Visualization: Plot average sales against store size to visualize the trend.
* Hypothesis 3: Stores in regions with higher unemployment rates have lower sales.
Validation Approach:
Data Analysis: Aggregate sales data by region and associate them with unemployment rates.
Statistical Tests: Use correlation analysis to explore the relationship between unemployment rates and sales.
Visualization: Create scatter plots to visualize sales against unemployment rates.
* Hypothesis 4: Sales of certain departments are more sensitive to temperature changes than others.
Validation Approach:
Data Segmentation: Divide sales data by departments and associate them with temperature data.
Statistical Tests: Use regression analysis to examine the impact of temperature on sales for different departments.
Visualization: Plot sales trends for temperature-sensitive departments against temperature variations.
* Hypothesis 5: Stores with frequent promotions have higher customer retention and repeat sales.
Validation Approach:
Data Analysis: Track customer purchase patterns over time for stores with frequent promotions.
Statistical Tests: Use survival analysis or time series analysis to examine customer retention and repeat sales.
Visualization: Create retention curves and repeat sales trends for stores with and without frequent promotions.
* Hypothesis 6: Fuel prices have an impact on consumer spending in retail stores.
Validation Approach:
Data Analysis: Correlate sales data with fuel price data over time.
Statistical Tests: Use regression models to explore the impact of fuel prices on sales.
Visualization: Plot sales trends against fuel price variations to identify patterns.
* Hypothesis 7: Sales are higher in stores located in urban areas compared to rural areas.
Validation Approach:
Data Segmentation: Categorize stores as urban or rural based on their location.
Statistical Tests: Compare average sales between urban and rural stores using t-tests or ANOVA.
Visualization: Create bar charts or box plots to compare sales between urban and rural stores. 

## Project Plan
**High-Level Steps for Analysis**
Here's a high-level overview of the steps taken in the retail sales data analysis project:
* Step 1: Project Planning and Setup
Define project objectives and scope.
Set up a GitHub repository and project Kanban board.
Outline user stories and map them to project goals.
* Step 2: Data Collection
Extract data from provided sources (Stores, Features, Sales Excel sheets).
Ensure data is loaded into a suitable format for processing.
* Step 3: Data Cleaning and Transformation
Handle missing values and correct any inconsistencies.
Create new features (e.g., sales differences between holiday and non-holiday weeks).
Standardize data formats for consistency.
* Step 4: Exploratory Data Analysis (EDA)
Generate descriptive statistics.
Visualize data distributions and identify initial trends.
Perform initial segmentation of the data (e.g., by store type, region).
* Step 5: Hypothesis Formulation and Validation
Formulate hypotheses based on business requirements.
Use statistical tests and visualizations to validate hypotheses.
* Step 6: Data Analysis and Visualization
Conduct in-depth analysis on key metrics (e.g., sales trends, promotional impacts).
Create detailed visualizations to support findings.
* Step 7: Interpretation of Results
Summarize findings from the data analysis.
Interpret results in the context of business objectives.
Provide actionable insights and recommendations.
* Step 8: Reporting and Presentation
Compile results and visualizations into a comprehensive report.
Present findings to stakeholders, highlighting key insights and recommendations.

**Data Management Throughout the Process**
* Collection: Data was extracted from Excel sheets and loaded into data frames.
* Processing: Data was cleaned and transformed, including handling missing values, correcting inconsistencies, and creating new features.
* Analysis: Exploratory data analysis (EDA) was conducted to understand data distributions, identify trends, and perform initial segmentation.
* Interpretation: Analytical results were interpreted in the context of business objectives, providing actionable insights and recommendations.

**Research Methodologies Used and Their Justification**
* Descriptive Statistics: Used to provide basic insights into the data (e.g., average sales per store and department). This methodology was chosen for its simplicity and effectiveness in summarizing data.
* Exploratory Data Analysis (EDA): Employed to identify patterns, trends, and anomalies in the data. EDA is essential for gaining an initial understanding of the dataset.
* Statistical Tests: Applied to validate hypotheses (e.g., t-tests, ANOVA, regression analysis). These tests were chosen for their ability to provide robust and reliable results.
* Visualization: Used to present data in an easily interpretable and visually appealing manner. Visualization helps in communicating insights effectively to stakeholders.
* Correlation and Regression Analysis: Utilized to understand relationships between variables (e.g., the impact of temperature on sales). These methodologies provide quantitative measures of association and causation.

## Business Requirements and Corresponding Visualizations

**Trend and Seasonal Analysis**

* Visualization: Line graphs and time series plots.
* Rationale: Line graphs and time series plots effectively display sales trends over time, highlighting seasonal patterns and fluctuations. They allow easy comparison of sales across different time periods, helping in strategic planning.

**Promotional Effectiveness**

* Visualization: Bar charts, heatmaps, and box plots.
* Rationale: Bar charts and heatmaps can illustrate the impact of promotional markdowns on sales during holiday and non-holiday periods. Box plots can show the distribution of sales during these periods, helping in assessing the effectiveness of promotions.

**Comparative Performance**

* Visualization: Bar charts, heatmaps, and scatter plots.
* Rationale: Bar charts and heatmaps can compare sales performance across different stores and regions, while scatter plots can illustrate relationships between store characteristics (like size and type) and sales. This aids in identifying high and low-performing stores.

**Descriptive Insights**

* Visualization: Summary tables and bar charts.
* Rationale: Summary tables provide quick, at-a-glance insights into key metrics like average sales per store and department. Bar charts can further break down these metrics, making it easy to understand and communicate basic descriptive statistics.

**Forecasting and Predictive Analysis**

* Visualization: Forecast plots and regression lines.
* Rationale: Forecast plots and regression lines help in visualizing predicted future sales based on historical data. They provide a visual representation of expected trends, aiding in inventory management and aligning supply with anticipated demand.

**Data-Driven Decision Support**

* Visualization: Interactive dashboards and comprehensive reports.
* Rationale: Interactive dashboards and reports allow stakeholders to explore the data in depth, making it easier to identify actionable insights. These visualizations support clear communication and data-driven decision-making.

**Impact of Economic Factors (e.g., Unemployment, Fuel Prices)**

* Visualization: Scatter plots and correlation matrices.
* Rationale: Scatter plots and correlation matrices can illustrate the relationships between economic factors (like unemployment rates and fuel prices) and sales. This helps in understanding external influences on sales performance.

## Analysis techniques used
Data analysis methods employed in the project, along with their limitations and alternative approaches:

**Descriptive Statistics:**

* Purpose: To provide basic insights into the data (e.g., average sales per store, department).
* Limitations: Limited to summary information and doesn't explore relationships between variables.
* Alternative: Exploratory Data Analysis (EDA) to uncover patterns and relationships in greater detail.

**Exploratory Data Analysis (EDA):**

* Purpose: To identify patterns, trends, and anomalies in the data.
* Limitations: EDA is mainly exploratory and may not confirm hypotheses.
* Alternative: Hypothesis testing for confirmatory analysis.

**Correlation Analysis:**

* Purpose: To identify relationships between variables (e.g., temperature and sales).
* Limitations: Correlation does not imply causation.
* Alternative: Regression analysis to model relationships and predict outcomes.

**Regression Analysis:**

* Purpose: To examine the impact of one or more independent variables on a dependent variable (e.g., sales).
* Limitations: Assumes linear relationships and may not capture complex interactions.
* Alternative: Non-linear models, such as decision trees or neural networks, to capture complex relationships.

**Hypothesis Testing:**

* Purpose: To validate assumptions and hypotheses using statistical tests (e.g., t-tests, ANOVA).
* Limitations: Requires a large sample size for reliable results.
* Alternative: Bayesian analysis for smaller sample sizes or more nuanced hypothesis testing.

**Visualization:**

* Purpose: To present data in an easily interpretable and visually appealing manner.
* Limitations: Visualizations may oversimplify data and overlook details.
* Alternative: Interactive dashboards for deeper exploration and detailed insights.

**Structuring Data Analysis Techniques**

The data analysis techniques were structured in a systematic manner to ensure comprehensive analysis and clear interpretation of results:

* Initial Descriptive Statistics: Provided a basic understanding of the dataset and highlighted key metrics.
* EDA: Explored data distributions, identified patterns, and guided subsequent analysis steps.
* Hypothesis Formulation: Based on business requirements, specific hypotheses were formulated.
* Correlation and Regression Analysis: Investigated relationships between variables and tested hypotheses.
* Hypothesis Testing: Confirmed or refuted assumptions using statistical methods.
* Visualization: Summarized findings and presented insights in a clear and actionable format.

**Data Limitations:**

* Missing Values: Some data points were missing or incomplete.
* Limited Historical Data: Historical data, especially around holidays and promotions, was limited.
* Data Quality: Inconsistencies in data formatting and quality.

**Alternative Approaches:**

* Imputation: Handled missing values through imputation techniques (e.g., mean, median imputation).
* Feature Engineering: Created new features to address data gaps (e.g., sales differences between holiday and non-holiday weeks).
* Standardization: Ensured data consistency through standardization and cleaning processes.

**Using Generative AI Tools**

* Brainstorming: Used AI tools to generate and refine project ideas, ensuring a wide range of potential approaches.
* Design Thinking: Leveraged AI to simulate user feedback and design iterations, leading to user-centric solutions.
* Code Generation: Utilized AI to generate and optimize code snippets, enhancing efficiency and reducing development time.
* Error Detection: Leveraged AI for code review and error detection, ensuring robust and reliable code.

## Ethical considerations
* Anonymization: Ensured that any personally identifiable information (PII) was anonymized or removed.
* Compliance: Adhered to data protection regulations such as GDPR, ensuring that data handling practices were compliant with legal requirements.
* Data Usage Permissions: Verified that data usage permissions were in place, ensuring that the dataset was used appropriately and legally.
* Transparency: Maintained transparency in methodology and results, allowing stakeholders to understand and question the findings.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Main Data Analysis Libraries
Pandas 

Purpose: Data manipulation and analysis.

Matplotlib

Purpose: Creating static, interactive, and animated visualizations.

Seaborn

Purpose: Statistical data visualization built on top of Matplotlib.

Numpy

Purpose: Support for large, multi-dimensional arrays and matrices, along with mathematical functions to operate on these arrays.


## Credits 

In this project, the content, code snippets, and guidance were primarily sourced from the following tools and platforms:

ChatGPT (by OpenAI)

Provided detailed explanations, code examples, and assistance in developing the ETL pipeline, data analysis, and visualization scripts.
Assisted in refining project ideas, structuring the analysis, and generating insights from the data.

Copilot 

Offered code suggestions and auto-completions while writing Python scripts, enhancing the efficiency of coding and ensuring best practices were followed.
Helped in generating template code structures for data loading, transformation, and visualization.

Learning Management System (LMS) from Code Institute

Served as a foundational resource for the theoretical concepts applied in the project.
Provided learning materials and project guidelines that informed the structure and implementation of the data analysis process.
These sources were instrumental in the development of the project, ensuring that best practices in data analysis and visualization were followed while maintaining originality in the project implementation.


## Acknowledgements 
I would like to extend my heartfelt gratitude to Vasilica Pavaloi and Niel McEwen for their invaluable guidance and support throughout this project. Their expertise and encouragement have been instrumental in my learning journey.
I would also like to thank my classmates for their collaboration and insightful feedback, which greatly contributed to the successful completion of this project.
