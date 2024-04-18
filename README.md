# Video Games Market Analysis
## ITC 6460 - Cloud Analytics - Northeastern University
### Group: Husky 2
**Contributors**: Katherine LaConte, Likhitha Varakala, Manmitha Pantangi, Shivam Sinha

This repository contains all resources and documentation for our final project on Video Games Market Analysis. Utilizing large-scale video game sales datasets, we've leveraged a range of AWS services to conduct comprehensive data cleaning, analysis, and predictive modeling.

## Project Overview
The project aims to provide an analytical perspective on the video game industry by examining sales trends, consumer preferences, and market dynamics. Through meticulous data cleaning and advanced data analytics performed in the AWS cloud environment, we've developed a holistic view of the industry's evolution over time.

## Data Sources
- **game_sales_data.csv**
- **vgsales.csv**

These datasets include information on game titles, platforms, release years, genres, and sales figures across multiple regions.

## AWS Services Used
- **AWS S3**: Centralized data storage ensuring durability and security.
- **AWS IAM**: Managed secure access to AWS resources.
- **AWS Glue**: Automated data cataloging and preparation.
- **Amazon SageMaker**: Developed and trained machine learning models for sales prediction.
- **AWS QuickSight**: Created interactive dashboards and visualizations for data reporting.

## Key Components
1. **Data Cleaning**: Standardized and merged datasets to create a unified source for analysis. Techniques included removing duplicates, imputing missing values, and converting data types.
2. **Data Analysis and Querying**: Utilized AWS Athena for executing complex SQL queries to uncover insights into genre popularity, critic scores, and regional sales performance.
3. **Predictive Modeling**:
   - **Preprocessing**: Handled missing data, encoded categorical variables, and normalized features.
   - **Model Architecture**: Designed a neural network for sales prediction with detailed architecture including input, hidden, and output layers.
   - **Model Training and Evaluation**: Trained the model using historical sales data, evaluated with mean squared error.
4. **Visualization and Dashboard**: Developed comprehensive QuickSight dashboards displaying critical metrics such as sales trends, top-performing games, and genre analysis.

## Results
The analysis revealed significant insights such as:
- "Super Mario Bros." as a top-selling game.
- Trends in game preferences across different regions.
- The impact of critical acclaim on sales.

These insights assist stakeholders in making informed decisions and strategizing based on evolving market trends.

## Conclusion
Our project demonstrates the effective use of cloud computing for handling and analyzing large-scale data, providing deep insights into the dynamic video game market. The findings from this project not only reflect past and present market scenarios but also help predict future trends.
