# Home-Inventory-Analytics---Excel

An interactive Goodreads Analytics Dashboard built in Tableau Public. This project analyzes book metadata, publication trends, language distribution, publishers, authors, ratings, and review statistics to uncover insights into global reading patterns and popular literature trends. The dashboard highlights key metrics such as average ratings, publication growth over time, most popular books, dominant publishers, and top language codes.

Tableau Dashboard Link : [https://public.tableau.com/app/profile/eldin.b.joseph/viz/HRAnalyticsDashboard_17238387531440/HRAnalyticsDashboard](https://public.tableau.com/views/goodreadsDashboard_17240674209860/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis & Visualizations](#analysis--visualizations)  
- [Conclusion](#conclusion)  
- [Credits](#credits)  
- [License](#license)  

---

## Overview

- **Motivation:** Finding a clean and structured dataset for books with meaningful metrics such as ratings, reviews, publication details, and author information is often difficult. This project was created to visualize Goodreads book data interactively and provide readers, analysts, and bibliophiles with insights into publishing trends, reader preferences, and book popularity.
- **Objective:** The main objective of this dashboard is to analyze Goodreads book data including publication trends, language distribution, ratings, publishers, and author statistics to support data-driven insights into reader behavior and literary trends.
- **Learning Outcomes:** WWhile building this project, I learned:
Tableau dashboard design and storytelling,
Data cleaning and preprocessing,
Creating interactive visualizations,
Analyzing publication and readership trends,
Working with Goodreads book metadata,
Presenting insights through business intelligence dashboards

---

## Dataset

Dataset Information

- Dataset Type: Goodreads Books Dataset 
- Records: 11,123 Records
- Dataset Source: [Goodreads Books Dataset](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks) 
- Features Included: Book Title
Authors
Publisher
Publication Date
Language Code
Average Rating
Ratings Count
Text Reviews Count
Number of Pages
- The dataset was cleaned and transformed before visualization:
Removed duplicate and null records
Standardized publication dates
Cleaned language code inconsistencies
Formatted multiple-author fields
Aggregated ratings and review metrics
Prepared publication year trends for dashboard analysis
- Dataset Background: The dataset was created to provide a clean and analysis-ready collection of books with meaningful numerical metrics. Existing public datasets often lacked proper cleaning, important attributes, or consolidated information. This dataset combines valuable Goodreads metadata into a single structured source suitable for analytics and recommendation systems.

- Important Notes: Data was scraped using the Goodreads API,
Goodreads API public developer access was retired after December 2020,
Multiple authors are separated using “/” delimiters,
Publisher and publication date fields were added in Version 2 of the dataset

---

<h2>Technologies Used</h2>

<ul>
  <li><strong>Tools & Platforms:</strong> Tableau Public, Microsoft Excel / CSV Dataset, Git, GitHub</li>
  <li><strong>Skills Applied:</strong> Data Cleaning, Data Visualization, Dashboard Design, Business Intelligence, Exploratory Data Analysis</li>
</ul>

<p>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau">
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel">
  <img src="https://img.shields.io/badge/CSV-FFB000?style=for-the-badge&logo=filezilla&logoColor=white" alt="CSV">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</p>

---

## Installation

To explore this project locally:

```bash

# Clone the repository
git clone https://github.com/eldinbr/Goodreads-Analytics-Dashboard.git

# Navigate into the project directory
cd Goodreads-Analytics-Dashboard



```

## Usage

Instructions for using the project:

1. Download or clone the repository 
2. Open the Tableau workbook file
3. Interact with filters and charts
4. Explore publication trends and book insights

The dashboard allows users to:
Filter books by title,
Analyze publication trends over time,
Compare top publishers by total books,
Explore language distribution of books,
Identify authors with the highest number of books,
Examine books with the highest ratings count,
Analyze reader engagement using reviews and ratings

---

## Analysis & Visualizations 

Key Insights

- English (eng) is the dominant language code in the dataset
- Book publications increased significantly after the 1990s
- Vintage and Penguin Books are among the top publishers
- Stephen King and P.G. Wodehouse are among the most represented authors
- Popular titles such as Twilight and The Hobbit have extremely high ratings counts
- Ratings and reviews provide strong indicators of reader engagement and popularity

Dashboard Components

- Books by Publication Date: 
Visualizes publishing activity trends across decades.
- Top 10 Language Codes: 
Highlights the most common languages represented in the dataset.
- Authors by Total Books: 
Shows authors with the largest number of published books in the dataset.
- Publishers by Total Books: 
Displays publishers contributing the highest number of titles.
- Titles by Rating Count: 
Identifies books with the highest reader engagement and popularity.

Business Value

- Understand global reading and publication trends
- Identify highly popular books and authors
- Explore language diversity in literature
- Support recommendation system exploration
- Analyze publisher dominance and reader engagement metrics

Preview

<img width="1384" height="805" alt="Screenshot 2026-05-07 at 6 08 04 PM" src="https://github.com/user-attachments/assets/c588165b-6e3e-45d8-8d43-d2dfed51cc58" />



---

## Conclusion 

The Goodreads Analytics Dashboard provides a comprehensive overview of publication patterns, author contributions, language diversity, and reader engagement trends using Goodreads book data. Through interactive visualizations, users can explore literary insights and discover patterns across thousands of books.

Recommendations

- Expand the dashboard with genre-based analysis
- Add recommendation engine functionality
- Include sentiment analysis from text reviews
- Introduce reader demographic insights if available
- Add trend forecasting for publication growth

---

## Credits

- **Collaborators:** Eldin 
- **Dataset:** [Goodreads Books Dataset](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks) 
- **Visualization Tool:** Tableau Public
- **Version Control:** GitHub 

---

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/) – feel free to use and modify it.  

---

<p align="center"><strong>Thanks for visiting! 🚀</strong></p>
