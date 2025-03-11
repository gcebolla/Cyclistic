# Cyclistic Bike-Share Data Analysis

## Project Overview
This repository contains a **data analysis case study** on the **Cyclistic** bike-share program, focusing on **customer usage patterns** and providing recommendations to convert **casual riders to member riders**. The analysis uses **SQL** for data cleaning, aggregation, and exploration, and **R** for analysis, visualization, and generating insights.

The case study demonstrates the process of cleaning, analyzing, and visualizing data to derive actionable business recommendations.

---

## Table of Contents
1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Installation Instructions](#installation-instructions)
4. [How to Run the Analysis](#how-to-run-the-analysis)
5. [Case Study Output](#case-study-output)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)

---

## Project Description
In this project, I analyzed the **Cyclistic bike-share** data to explore patterns in customer usage and identify strategies to increase member subscriptions. **Cyclistic is a fictional company based on real-world data from Divvy, a Chicago-based bike-share program.**  

The Director of Marketing believes that increasing annual memberships is crucial for the company's future. Since **annual members are more profitable than casual riders**, this analysis aims to uncover key insights and provide **three actionable recommendations** to help convert casual riders into long-term members.  

The dataset includes **12 months of ride history** (Nov 2023 – Oct 2024) with millions of ride records. The data, provided by **Motivate International Inc.**, is publicly available under a data-sharing agreement: [Divvy Data](https://divvy-tripdata.s3.amazonaws.com/index.html).


---

## Technologies Used
- **SQL**: Used for data cleaning and aggregation from raw data files.
- **R**: Used for data analysis, statistical analysis, and data visualization.
  - **RMarkdown**: For generating the report and final HTML output.
- **ggplot2**: For creating visualizations in R.

---

## Installation Instructions
To get started with this project, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   
2. Install necessary R packages (if you don't have them already):
   ```R
   install.packages(c("dplyr", "ggplot2", "RMarkdown", "tidyverse"))

4. Download the required data (if necessary) and place it in the corresponding folder within the repository.

## How to Run the Analysis
1. Open the repository folder in RStudio.

2. Open the RMarkdown file (case_study.Rmd).

3. Knit the RMarkdown file to generate the HTML output of the case study.

- Click the Knit button in RStudio or run the following command in R:
  ```R
  rmarkdown::render("case_study.Rmd")
  
4. This will generate the case_study_output.html file, which includes the analysis results and visualizations.
   
## Case Study Output
You can view the case study **online** by visiting the following URL (GitHub Pages link will go here once set up):
[View Case Study Output](https://yourusername.github.io/your-repository-name/case_study_output.html)

---

## License
This repository is licensed under the **Creative Commons Zero v1.0 Universal**. See the [LICENSE](LICENSE) file for more details.

---

## Acknowledgments
- Data provided by **Cyclistic Bike-Share** program.
- Special thanks to the creators of the tools and libraries used in this analysis: **R**, **ggplot2**, **SQL**, and **RMarkdown**.
