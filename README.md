# **Cyclistic Case Study**

## **Overview**  
This repository contains a **data analysis case study** focused on **customer usage patterns** and strategies to convert **casual riders into members**. The analysis utilizes **SQL** for data cleaning, aggregation, and exploration, and **R** for analysis, visualization, and generating insights.  

The case study demonstrates the end-to-end process of **cleaning, analyzing, and visualizing data** to derive actionable business recommendations.  

---

## **Table of Contents**  
1. [Description](#description)  
2. [Technologies Used](#technologies-used)  
3. [Installation Instructions](#installation-instructions)  
4. [How to Run the Analysis](#how-to-run-the-analysis)  
5. [Case Study Output](#case-study-output)  
6. [License](#license)  
7. [Acknowledgments](#acknowledgments)  

---

## **Description**  
This analysis explores customer usage trends to identify strategies for increasing **member subscriptions**.  

🚴 **Cyclistic** is a fictional company based on real-world data from **Divvy**, a Chicago-based bike-share program.  

📌 The **Director of Marketing** believes that increasing annual memberships is crucial for the company's long-term success. Since **annual members generate higher revenue than casual riders**, this study aims to uncover key insights and provide **three actionable recommendations** to encourage casual riders to become members.  

📊 The dataset includes **12 months of ride history** (Nov 2023 – Oct 2024), comprising millions of ride records. The data, provided by **Motivate International Inc.**, is publicly available under a data-sharing agreement: [Divvy Data](https://divvy-tripdata.s3.amazonaws.com/index.html).  

⚠️ **Note:** This dataset does not contain personally identifiable information (PII).  

---

## **Technologies Used**  
- **SQL** – Data cleaning, transformation, and aggregation.  
- **R** – Statistical analysis and data visualization.  
- **RMarkdown** – Report generation and final HTML output.  
- **ggplot2** – Data visualization in R.  

---

## **Installation Instructions**  
To set up this project, follow these steps:  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/gcebolla/Cyclistic-Case-Study.git
   ```
2. **Install necessary R packages (if not already installed):**  
   ```r
   install.packages(c("dplyr", "ggplot2", "tidyverse"))
   ```
3. **Download the dataset:**  
   - Obtain **Cyclistic_12.csv** from the provided link.  
   - Place it in the appropriate folder within the repository.  

---

## **How to Run the Analysis**  
1. Open the repository folder in **RStudio**.  
2. Open the **Cyclistic.Rmd** file.  
3. Knit the RMarkdown file to generate the HTML output:  
   - Click the **Knit** button in RStudio.  
   - Or run the following command in R:  
     ```r
     rmarkdown::render("Cyclistic.Rmd")
     ```
4. This will generate **Cyclistic_Output.html**, containing the analysis results and visualizations.  

---

## **Case Study Output**  
You can view the case study **online** at:  
📄 [View Case Study Output](https://gcebolla.github.io/Cyclistic-Case-Study/Cyclistic_Output.html) *(GitHub Pages link – to be added once set up)*  

---

## **License**  
This repository is licensed under **Creative Commons Zero v1.0 Universal**.  
See the [LICENSE](LICENSE) file for more details.  

---

## **Acknowledgments**  
- **Data Provider:** Cyclistic Bike-Share (Divvy).  
- **Tools Used:** R, ggplot2, SQL, RMarkdown.  
- **Special Thanks:** To the creators of open-source tools and libraries that made this analysis possible. 
