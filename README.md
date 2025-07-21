**🎬 Netflix Titles Dataset (2015) — Exploratory Data Analysis & Feature Engineering**   

This project focuses on performing  Exploratory Data Analysis (EDA) and  Feature Engineering on the Netflix 2015 Titles Dataset.   

The goal is to clean, explore, and prepare the data for future tasks like modeling.  


📌 **Project Goals:**

🧼 Clean and preprocess real-world categorical and numeric data
📊 Perform exploratory analysis to understand content trends 
🧠 Engineer smart, model-friendly features from existing columns  



**🔍 EDA Summary:**  

Visualized the distribution of movies vs. TV shows  

Explored numerical and categorical columns  

Handled missing values in director, cast, country, release_year  

Identified outliers in release_year and removed them using IQR   



**🧠 Feature Engineering Summary:**  

In the feature engineering phase, multiple new variables were created to enrich the dataset and capture deeper insights from existing information.   

These features were designed to support downstream tasks like machine learning modeling, dashboarding, or recommendation systems.   

Key transformations included:  

Temporal Features: Extracted year_added, month_added, and day_added from the date_added column to capture seasonal trends and timing patterns.   

Age-Based Features: Created years_since_release to measure how old a title is, and a binary flag is_recent_release to identify titles released after 2019.  

Text-Derived Features: Measured title_word_count and description_len to quantify content complexity and metadata richness.  

Genre & Country Complexity: Introduced num_genres (count of genres per title) and is_multi_country (flag for multi-country productions). 

Release Timing Lag: Computed days_to_netflix to capture how quickly content became available on Netflix after its release.   



🛠️**Tech Stack**

Python: pandas, NumPy, matplotlib, seaborn, scikit-learn  

VS Code: for running scripts  

Git: for version contro
