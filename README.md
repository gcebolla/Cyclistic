# **Cyclistic Case Study**

## **Overview**  
This repository contains a data analysis case study focused on customer usage patterns and strategies to convert casual riders into members. The analysis utilizes **SQL** for data cleaning, aggregation, and exploration, and **R** for analysis, visualization, and generating insights.  

This is the capstone project for the **Google Data Analytics Certificate**, showcasing skills in SQL, R, data visualization, and business problem-solving.

It demonstrates the end-to-end process of cleaning, analyzing, and visualizing data to derive actionable business recommendations.

---

## **Table of Contents**  
1. [Description](#description)  
2. [Technologies Used](#technologies-used)  
3. [How to Run the Analysis](#how-to-run-the-analysis)   
4. [Final Report & Insights](#final-report--insights)  
5. [License](#license)  
6. [Acknowledgments](#acknowledgments)  

---

## **Description**  
This analysis explores customer usage trends to identify strategies for increasing member subscriptions.  

- **Cyclistic** is a fictional company based on real-world data from **Divvy**, a Chicago-based bike-share company.  

- The Director of Marketing believes that increasing annual memberships is crucial for the company's long-term success. Since annual members generate higher revenue than casual riders, this study aims to uncover key insights and provide three actionable recommendations to encourage casual riders to become members.  

- The dataset includes 12 months of ride history (Nov 2023 – Oct 2024), comprising millions of ride records. The data is publicly available under a data-sharing agreement: [Divvy Data](https://divvy-tripdata.s3.amazonaws.com/index.html).

- **Note:** This dataset does not contain personally identifiable information (PII).  

---

## **Technologies Used** 
- **RMarkdown** – Report generation and final HTML output. 
- **SQL (Google BigQuery)** – Data cleaning, transformation, and aggregation.  
- **R** – Statistical analysis and data visualization. 
- **ggplot2** – Data visualization in R.  

---

## **How to Run the Analysis**  
1. Clone the repository: 
   ```bash
   git clone https://github.com/gcebolla/Cyclistic.git
   ```
2. Navigate to the cloned repository folder and open [cyclistic.Rmd](https://github.com/gcebolla/Cyclistic/blob/main/cyclistic.Rmd) in **RStudio**.
3. Knit the RMarkdown file to generate the HTML output:  
   - Click the **Knit** button in RStudio.  
   - Or run the following command in R:  
     ```r
     rmarkdown::render("cyclistic.Rmd")
     ```
 4. This will generate [cyclistic.html](https://github.com/gcebolla/Cyclistic/blob/main/cyclistic.html), containing the analysis results and visualizations.

---

## **Final Report & Insights**
You can view the case study online at:  
- [View Final Report & Insights](https://gcebolla.github.io/Cyclistic/cyclistic.html)
- Alternatively, you can download and open [cyclistic.html](https://github.com/gcebolla/Cyclistic/blob/main/cyclistic.html) in a browser.
---

## **License**  
- **Data License:** The dataset is provided by **Motivate International Inc.**, under this [license.](https://divvybikes.com/data-license-agreement).
- **Project License:** This repository is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
See the [LICENSE](LICENSE) file for more details.  

---

## **Acknowledgments**  
- **Data Provider:** Motivate International Inc. (Divvy).  
- **Tools Used:** R, ggplot2, SQL, RMarkdown.  
- **Special Thanks:** To the creators of open-source tools and libraries that made this analysis possible.
