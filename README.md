# AmbitionBox Data Analysis & Web Scraping
## Project Overview
This project involves web scraping data from AmbitionBox, a platform providing company reviews, salary insights, and interview experiences. The goal is to analyze and visualize career-related data to help job seekers make informed decisions.

## Problem Statement
Job seekers often lack access to transparent and reliable insights about workplace culture, salaries, and career progression. This project extracts and analyzes AmbitionBox data to compare companies, research career paths, and provide data-driven insights.

## Objectives
✅ Compare companies based on employee reviews, ratings, and salaries.
✅ Analyze career growth opportunities in different industries.
✅ Offer data-driven insights to assist job seekers.
✅ Utilize real employee experiences for transparency.

## Tools & Technologies Used
- Python (for Web Scraping & Data Analysis)
- BeautifulSoup & Requests (for extracting data)
- Pandas & NumPy (for data cleaning & manipulation)
- Matplotlib & Seaborn (for data visualization)
- Jupyter Notebook (for analysis & visualization)
## Dataset & Cleaning Process
The dataset includes the following fields:
🔹 Company Name
🔹 Industry Type
🔹 Rating
🔹 Locations
🔹 Average Salaries
🔹 Total Interviews
🔹 Total Jobs
🔹 Total Positive Reviews

## Cleaning Steps:
✔ Removed duplicate entries
✔ Converted ratings & salaries to appropriate numeric formats
✔ Handled missing values in Total Jobs and Industry Type
✔ Ensured data consistency and accuracy before analysis

## Key Visualizations & Insights
📌 Company Ratings Distribution: Most ratings fall between 3.5 - 4.2.
📌 Top 20 Companies by Positive Reviews: TCS, Accenture, and Wipro have the highest transparency.
📌 Rating vs Salary Scatter Plot: No strong correlation; salary doesn’t always align with company rating.
📌 Industry-Wise Average Salaries: IT Services, Software Product, and Financial Services are top-paying sectors.
📌 Correlation Matrix: Total Reviews & Total Jobs have a strong positive correlation.
📌 Industry-Wise Rating Distribution: Defence & Aerospace and Oil & Gas have consistently high ratings.

## Project Structure
 - bash
📂 AmbitionBox-Analysis  
│── 📄 README.md              # Project documentation  
│── 📂 Data  
│   ├── Raw_Ambition_Box.csv  # Raw extracted data  
│   ├── Cleaned_Ambition_Box.csv # Processed & cleaned dataset  
│── 📂 Notebooks  
│   ├── Web_Scraping.ipynb    # Data extraction from AmbitionBox  
│   ├── EDA.ipynb             # Exploratory Data Analysis  
│   ├── Visualization.ipynb   # Data visualization & insights  
│── 📄 Project_ambition_Box_web_scrap.ipynb  # Complete workflow  
│── 📄 Final.ipynb             # Final notebook with all steps combined  


### How to Run the Project?
1️⃣ Clone the repository:

sh

git clone https://github.com/yourusername/AmbitionBox-Analysis.git
cd AmbitionBox-Analysis

2️⃣ Install dependencies:

sh

pip install -r requirements.txt

3️⃣ Run the Jupyter notebooks for EDA & Visualization.

## Conclusion
🔹 IT Services & Consulting is the highest-paying industry.
🔹 No strong correlation exists between company ratings and salaries.
🔹 TCS, Accenture, and Wipro have the highest transparency with employee feedback.

## Contributors
👨‍💻 Mennuli Kiran Bala Krishna
👨‍💻 Yadam K Sidda Chetan Reddy

## License
📜 MIT License

