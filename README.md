Customer Satisfaction Power BI Dashboard
Overview
This project involves creating an interactive Power BI dashboard to analyze customer satisfaction data. The dashboard helps visualize key metrics like response time, product quality, and customer satisfaction, with the ability to slice the data by regions. The goal is to provide a clear, interactive, and insightful report for business decision-makers to understand the factors influencing customer satisfaction.

Problem Statement
A business needs a tool to understand its customer satisfaction across different regions and identify key factors influencing it. The existing dataset contains information about customer satisfaction, response time, product quality, and region. There is a need for a visual and interactive tool that allows decision-makers to:

Assess overall customer satisfaction.
Compare customer satisfaction across regions.
Investigate how response time and product quality impact customer satisfaction.
Explore the relationship between customer satisfaction and other factors dynamically.
Tasks and Solutions
Task 1: Load and Prepare the Data
Problem: Import the synthetic customer satisfaction data into Power BI for analysis.

Solution:
Imported the dataset (customer_satisfaction_data.csv) from a specified local path using Power BI’s Get Data > Text/CSV feature.
Task 2: Create Overview Dashboard
Problem: Present the main customer satisfaction metrics on the first page.

Solution:
Added Card visuals to display:
Average Response Time
Average Product Quality
Average Customer Satisfaction
Added a Bar Chart to visualize Customer Satisfaction by Region.
Used a Slicer to filter the data by Region.
Task 3: Detailed Analysis Page
Problem: Provide detailed insights into how response time, product quality, and other factors affect customer satisfaction.

Solution:
Created a Scatter Plot to visualize the relationship between Response Time and Customer Satisfaction, with Product Quality influencing bubble size.
Added a Line Chart (if time data is available) to show trends in customer satisfaction over time.
Integrated the Key Influencers visual to identify key drivers of customer satisfaction.
Task 4: Add Navigation Between Pages
Problem: Allow users to navigate between the Overview and Detailed Analysis pages.

Solution:
Added Navigation Buttons for seamless transition:
"Go to Detailed Analysis" on the Overview page.
"Go to Overview" on the Detailed Analysis page.
Task 5: Slicers and Filters
Problem: Enable users to filter and drill down into specific regions or product categories.

Solution:
Added Slicers for filtering by Region.
Slicers were synchronized across both pages for consistent filtering.
Task 6: Use AI Tools for Insights
Problem: Enhance the dashboard with AI-driven insights into customer satisfaction.

Solution:
Incorporated the Key Influencers visual on the Detailed Analysis page to show the factors influencing customer satisfaction.
Added the Q&A Visual to let users ask questions like:
"What is the average satisfaction by region?"
"What is the relationship between product quality and satisfaction?"
Task 7: Aesthetic and Functional Design
Problem: Design the dashboard to be user-friendly, clear, and aesthetically pleasing.

Solution:
Used consistent color themes and aligned visuals for a professional look.
Added Dynamic Titles to make the dashboard more interactive.
Enabled Tooltips to provide additional context when hovering over data points.
Insights
Regional Insights:

The Bar Chart shows how customer satisfaction varies across different regions (North, South, East, West). This can help identify regions where customer satisfaction is low and may need further investigation.
Response Time and Satisfaction:

The Scatter Plot indicates the relationship between Response Time and Customer Satisfaction. If the plot shows that longer response times correlate with lower satisfaction, this could highlight areas for improvement in customer service.
Product Quality Impact:

The Key Influencers Visual reveals that Product Quality is a significant factor influencing Customer Satisfaction. This can guide the company in focusing on improving product quality to enhance customer satisfaction.
Trends Over Time:

If time data is available, the Line Chart can show trends in customer satisfaction over the past months or years, helping to track the effectiveness of changes made to improve service or products.
Predictive Analysis:

By using AI-driven insights (Key Influencers, Q&A Visual), users can ask natural language questions, which allows for a more intuitive exploration of the data. For example, understanding how customer satisfaction changes with different product qualities or response times can lead to better strategic decisions.
Future Enhancements
Time-Series Analysis:

Adding time data (e.g., date of customer interaction) to track customer satisfaction trends over time, which can provide insights into the impact of seasonal factors or changes in service strategies.
Advanced Predictive Analytics:

Integrating predictive models into Power BI using Python or R scripts to forecast customer satisfaction based on historical data.
Customer Segmentation:

Incorporating more advanced segmentation of customers (e.g., by age, purchase history) to identify how different segments perceive product quality and service.
More Slicers:

Adding more slicers (such as Customer Type, Product Categories) to allow deeper analysis of satisfaction levels for different customer groups.
How to Use the Dashboard
Navigating:

Click on the buttons ("Go to Detailed Analysis" / "Go to Overview") to switch between pages.
Filtering:

Use the Region slicer to filter the dashboard based on specific geographic areas.
Insights Exploration:

Use the Key Influencers and Q&A Visuals to gain more detailed insights into what factors are influencing customer satisfaction.
