# Data-Driven-Hotel-Analysis

## Overview
At Techionista Academy, our team of five embarked on a business case project aimed at gaining practical experience in preparation for careers as data engineers. This particular case, closely tied to the Microsoft PL300 exam, centered around the analysis of hotel reviews from the fictional website Techionista Holidays spanning the years 2015 to 2017. Our focus was on various aspects of the reviewers and hotels, including nationalities, traveler types, and hotel locations. This repository serves as a comprehensive repository of our work, analyzing a dataset consisting of a staggering 515,000 records pertaining to holiday trends.

Techionista Holidays' managers expressed a strong desire to gain deeper insights into the different types of travelers and their feedback. These valuable insights can play a pivotal role in enhancing Techionista's Holidays website and their capacity to cater to the evolving needs of their users.

## Objective
Our primary objective was to craft an all-encompassing interactive dashboard that offers valuable insights into different categories of travelers and their feedback. These insights would, in turn, be harnessed to enhance the Techionista Holidays website, ensuring a more tailored and effective user experience. The key features of our project include:

## Features

1. **Interactive Dashboard:** Our dashboard empowers users with a wide range of filtering options, allowing them to explore data by country, city, hotel, date, trip type, traveler category, and nationality.
2. **Visualizations:** We have leveraged various visualization techniques, including maps, word clouds, charts, and more, to deliver a compelling and informative experience for users.
3. **Pages:**
   - **Trip and Travelers Insights:** This section presents an in-depth analysis related to trips and travelers, shedding light on their preferences and behaviors.
   - **Review and Reviewer Analysis:** Here, we delve into the world of hotel reviews, dissecting both the reviews themselves and the reviewers to uncover valuable patterns and trends.
   - **Positive and Negative Comments:** In this segment, we offer a detailed breakdown and analysis of comments, categorizing them as positive or negative and deriving meaningful insights.

Our role in this endeavor was to extract meaningful information from travelers' reviews about their experiences. This information aimed to provide valuable insights that can aid in enhancing the hotel's overall performance and customer satisfaction.

## Technologies Used
- **Azure Blob Storage:** Used as a storage solution for managing and storing data.
- **Power BI Desktop:** Utilized for data visualization and report creation.
- **Power BI Online:** The online service used for sharing and collaborating on Power BI reports and dashboards.
- **Power Query in Power BI:** Employed for data transformation and manipulation within Power BI.
- **DAX (Data Analysis Expressions):** Used for creating custom calculations and expressions in Power BI reports and models.

## Methodology: Data Transformation & Modeling

1. Connected to Azure Blob Storage in Power BI to access the dataset.
2. Promoted headers for improved data recognition.
3. Split the "Hotel Address" column into three segments: address, city, and country. Also, split the "Tags" column into six distinct columns.
4. Assigned clear names to the newly created columns.
5. Categorized trip types into business, leisure, and other, as well as categorized traveler types using conditional formatting.
6. Checked and adjusted headers as needed and verified and corrected data types.
7. Conducted data profiling, including analyzing column distribution, quality, and profiles, identifying and removing errors, replacing null values with "unknown," and ensuring data completeness.
8. Introduced a surrogate key (reviewer ID) to all rows for improved data management.
9. Created dimension tables for Negative and Positive reviews by duplicating the main dataset and removing irrelevant columns.
10. Filtered negative comments to exclude rows with "no Negative Comment."
11. Established one-to-many relationships between dimension and fact tables with bidirectional filters for enhanced data analysis.
    
Through these steps, we established a strong foundation for our analysis and reporting, enabling us to extract valuable insights from the hotel review dataset.

![Conditional Column: Type of traveler](https://github.com/suzydeurinck/Data-Driven-Hotel-Analysis/raw/fe91999aa66eb9add8be2bb9b66daf7dd9eaecb6/Added%20Conditional%20Column%20-%20Travelers%20Type.png)

![Conditional Column: Country](https://github.com/suzydeurinck/Data-Driven-Hotel-Analysis/raw/fe91999aa66eb9add8be2bb9b66daf7dd9eaecb6/Added%20Conditional%20Column%20-%20Country.png)


## Report Results

![Overview Page](https://github.com/suzydeurinck/Data-Driven-Hotel-Analysis/raw/main/PowerBI_overviewpage.jpg)

![Insights](https://github.com/suzydeurinck/Data-Driven-Hotel-Analysis/raw/main/PowerBI_insights.jpg)

![Review Analysis](https://github.com/suzydeurinck/Data-Driven-Hotel-Analysis/raw/main/PowerBI_reviewanalysis.jpg)

## Contributers
Elahe Sharifi, Javeria Umer, Vidisha Gedam, Lavanya Laxmi Uppara, Suzy Deurinck

## Contact
Feel free to reach out to me at suzydeurinck@gmail.com for any inquiries or collaborations.
