🗼 AirBnB Paris Listings Analysis Project
Project Overview

This project analyzes AirBnB listings data for Paris using Python, Pandas, and Matplotlib.

The workflow includes:

Data importing and cleaning
Data profiling and quality assurance (QA)
Data aggregation and transformation
Exploratory data analysis (EDA)
Visualization of pricing trends and host activity
Insights about the impact of Paris AirBnB regulations

The project was completed using Python in the Anaconda environment with Jupyter Notebook.

📂 Dataset Files

The project uses the following datasets:

Listings.csv
Listings_data_dictionary.csv
Reviews.csv
Reviews_data_dictionary.csv
🛠 Technologies Used
Python
Pandas
Matplotlib
Jupyter Notebook
Anaconda
📦 Python Libraries
import pandas as pd
import matplotlib.pyplot as plt
⚙️ Project Objectives
Objective 1: Profile & QA the Data

Tasks completed:

Imported the AirBnB listings dataset
Fixed CSV encoding issues
Converted date columns to datetime format
Filtered listings for Paris only
Selected relevant columns:
host_since
neighbourhood
city
accommodates
price
Performed QA checks:
Missing values
Minimum values
Maximum values
Average values
Objective 2: Prepare Data for Visualization

Created the following DataFrames:

1. paris_listings_neighbourhood

Grouped Paris listings by neighbourhood and calculated:

Average listing price
2. paris_listings_accommodations

Filtered the most expensive neighbourhood and analyzed:

Average price by number of accommodates
3. paris_listings_over_time

Grouped listings by host year and calculated:

Average price over time
Number of new hosts per year
Objective 3: Visualize the Data

Created the following visualizations:

📊 Horizontal Bar Charts
Average price by neighbourhood
Average price by accommodates in the most expensive neighbourhood
📈 Line Charts
Number of new hosts over time
Average listing price over time
🎁 Bonus Visualization
Dual-axis chart showing:
New hosts
Average prices
🚀 How to Run the Project
Step 1

Install Anaconda:

Download and install Anaconda
Open Jupyter Notebook or Spyder
Step 2

Place the dataset files in the project folder.

Example:

Project Folder/
│
├── Listings.csv
├── Reviews.csv
├── notebook.ipynb
└── README.md
Step 3

Install required libraries if needed:

pip install pandas matplotlib
Step 4

Run the notebook cells sequentially.

🔧 Common Issue Fix
UnicodeDecodeError

If the CSV fails to load:

listings = pd.read_csv("Listings.csv", encoding='latin1')

Alternative encodings:

encoding='cp1252'

or

encoding='ISO-8859-1'
📌 Key Findings
1. Paris Neighborhood Pricing

Some neighborhoods in Paris have significantly higher AirBnB prices than others. Luxury and tourist-heavy locations dominate the highest pricing tiers.

2. Accommodations Impact Pricing

Listings that accommodate more guests generally have higher average prices. Larger apartments and premium rentals contribute strongly to revenue.

3. 2015 Regulations Impact

Analysis suggests that:

Growth in new hosts slowed after regulatory changes
Average listing prices continued increasing
Reduced supply may have contributed to higher prices
🏆 Final Project Question
Which neighborhood in Paris has the highest average AirBnB listing price?

The answer is stored in:

most_expensive_neighbourhood
📷 Example Visualizations

Visual outputs include:

Neighbourhood pricing comparison
Accommodations pricing analysis
Host growth over time
Price trends over time
Combined dual-axis analysis
📚 Learning Outcomes

This project demonstrates practical skills in:

Data cleaning
Data wrangling
Exploratory Data Analysis (EDA)
Data visualization
Business insight generation
Real-world CSV handling
Time-series trend analysis
✨ Conclusion

This project transforms raw AirBnB listing data into meaningful business insights about Paris rental trends, pricing behavior, and regulatory impacts.

From messy CSV files to polished visual analytics, the workflow showcases a complete beginner-to-intermediate data analytics pipeline using Python.

Paris becomes less of a city map and more of a living economic heatmap glowing with data 📊🗼

I created a complete professional README file for your AirBnB Paris Analysis project 📘✨

It includes:

Project overview
Objectives
Dataset details
Technologies used
Visualization summary
Findings & insights
Unicode error fix
Run instructions
Final conclusions

Perfect for:

GitHub projects
College submissions
Portfolio showcasing
Internship presentations 🚀
