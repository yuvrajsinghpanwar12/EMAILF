This project performs Exploratory Data Analysis (EDA) on an airline delay dataset to identify patterns, causes of delays, and performance differences across airlines and airports. The analysis focuses on understanding the major contributors to flight delays and preparing the dataset for further analytics or database storage.

🔧 Technologies Used

Python

Pandas for data cleaning and analysis

Matplotlib and Seaborn for data visualization

MySQL for storing processed data

SQLAlchemy for database connectivity

📂 Project Workflow
1️⃣ Data Loading

Imported airline delay dataset using Pandas.

Explored dataset structure including shape and column details.

2️⃣ Data Cleaning

Identified missing values in the dataset.

Applied preprocessing strategies:

Numeric columns: filled with mean values.

Categorical columns: filled with mode values.

3️⃣ Exploratory Data Analysis

Performed multiple analyses to identify delay patterns:

Average delay by airline carrier

Average delay by airport

Distribution of delays caused by factors such as:

Carrier delay

Weather delay

NAS (National Airspace System) delay

Security delay

Late aircraft delay

4️⃣ Data Visualization

Created bar charts to analyze the total delay minutes by different delay causes, helping identify the most significant contributors to airline delays.

5️⃣ Database Integration

Established a connection to a MySQL database.

Exported the cleaned dataset into a database table for further querying and analysis.

📈 Key Insights

Identified airlines with the highest average arrival delays.

Analyzed airport-wise delay performance.

Determined the primary reasons for flight delays based on aggregated delay minutes.

🎯 Outcome

This project demonstrates skills in:

Data cleaning and preprocessing

Exploratory data analysis

Data visualization

Database integration using Python
