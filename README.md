🚇 Delhi Metro Data Analysis
Transforming messy transit data into meaningful insights

📌 Project Overview
This project focuses on analyzing Delhi Metro travel data to uncover patterns in passenger movement, station activity, and route demand.
Starting from semi-structured JSON files, the data was cleaned, transformed, and stored in a relational database to enable efficient querying and analysis.

🎯 Objectives
Identify stations with the highest number of departures
Analyze passenger demand across routes
Understand revenue and ticket usage trends
Discover the most frequently used metro routes
Build a clean and structured dataset for analysis

🧹 Data Processing & Cleaning
Raw data is rarely analysis-ready — this project involved:
Standardizing station names (removing inconsistencies and formatting issues)
Handling missing and null values
Converting JSON data into structured CSV format
Ensuring data type consistency for database storage

🛠️ Tech Stack
Python – Data processing and transformation
Pandas – Data cleaning and manipulation
MySQL – Data storage and querying
Jupyter Notebook – Analysis and exploration

📂 Project Structure
source_data/        # Raw JSON files  
cleaned_data/       # Cleaned CSV files  
notebooks/          # Jupyter notebooks with analysis  
requirements.txt    # Project dependencies  
README.md           # Project documentation 

📊 Key Insights
Certain stations consistently show high departure volumes, indicating major transit hubs
Passenger flow reveals clear patterns in route popularity
Ticket usage trends provide insights into commuter behavior
Clean and structured data significantly improves analytical accuracy

⚙️ Workflow
Load raw JSON data using Pandas
Perform data cleaning and preprocessing
Convert cleaned data into CSV format
Load data into MySQL database
Execute SQL queries for analysis and insights

😤 Challenges & Learnings
Handling semi-structured JSON data required careful parsing
Data cleaning was a critical and time-intensive step
Writing optimized SQL queries improved performance and understanding of relational data

🏁 Conclusion
This project demonstrates the importance of data cleaning and structured storage in real-world analytics. By transforming raw metro data into actionable insights, it highlights how data-driven approaches can improve understanding of urban transportation systems.

✨ Personal Note
This project started with messy data and a lot of confusion…
but ended with clean insights and much better SQL skills 😌

