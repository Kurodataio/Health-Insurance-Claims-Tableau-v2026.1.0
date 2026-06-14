# Health-Insurance-Claims-Tableau-v2026.1.0
Health Insurance Claims Analysis with Tableau Desktop v2026.1.0, analyzing demographic and behavioral risk factors (Age, BMI, Smoking status) impacting medical insurance charges.


## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis & Visualizations](#analysis--visualizations)  
- [Conclusion](#conclusion)  
- [Credits & Acknowledgements](#credits)  
- [License](#license)  

---

## Overview
- The dataset was chosen to assess health insurance claims using Tableau Desktop v2026.1.0
- The Exploratory Data Analysis mirrors the Jupyter Notebook EDA

---

## Dataset
- The dataset is Medical Cost Personal Datasets from Kaggle
- This dataset was also used in the Jupyter notebook repo
- Size of the dataset is 1338 rows and 7 columns

Dataset: insurance.csv

---

<h2>Technologies Used</h2>

<ul>
  <li><strong>Tools:</strong> Tableau Desktop v2026.1.0, VS Code, Git, GitHub</li>
 
</ul>


<P>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code"/>  
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</p>
<p>
  <img src="https://img.shields.io/badge/MIT%20License-000000?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="MIT License">
</p>


---

## Installation

Step-by-step instructions to set up the project locally:

```bash

# Clone the repository
git clone https://github.com/Kurodataio/Health-Insurance-Claims-Tableau-v2026.1.0.git

# Navigate to the project folder
cd Health-Insurance-Claims-Tableau-v2026.1.0

# Launch Tableau Desktop
Tableau Desktop 


```

## Usage

Instructions for using the project:

1. Open the tableau file (`Medical Cost Personal.twb`)  
2. Visualizations and results will be generated automatically  

---

## Analysis & Visualizations 
- **The Smoking Premium:** Smokers face significantly higher claims costs overall compared to non-smokers, regardless of age
- **The High-Risk Threshold:** A critical cost spike occurs for individuals with a BMI exceeding 30 who also smoke. 
- **Regional Consistency:** Average BMI remains relatively uniform across regions, hovering between 29 and 32.

---

## Dashboard Preview
- Insurance Claims Dashboard Preview
![Insurance Claims Dashboard Preview](Insurance_Claims_Dashboard_Preview.png)
- Insurance Claims Dashboard Preview - Southeast Region
![Insurance Claims Dashboard Preview - Southeast Region](Insurance_Claims_Dashboard-southeast-region_Preview.png)

---

<!-- ## Interactive Live Dashboard
- **[Click here to view and interact with the Live Dashboard on Tableau Public](YOUR_TABLEAU_PUBLIC_LINK_HERE)**

--- -->

## Technical Features Demonstrated
- Interactive dashboard action filtering (Filter by region or smoking status).
- Custom Box-and-Whisker distribution analysis.
- 100% Stacked bar chart implementations utilizing quick table calculations.
- Data cleansing, type structuring, and metric aggregation management.

---

## Conclusion 

- Smoking is the biggest risk feature for high claims cost. This single driver puts an individual into a higher cost bracket regardless of age or BMI.
- Obesity (BMI $\ge$ 30) acts as a compounding multiplier when associated with smoking. 
- **Smoking and BMI combined are associated with the highest claims cost**
- The Southeast region has the highest levels of smoking and obesity (high BMI) rates. Remediation could be targeted at this region as a priority.
- The southeast region has the highest claims cost, which is associated with the highest number of smokers and obese people.
- Further data and analysis is required to validated the surge in claims cost associated with smoking and BMI.
  - What are the actual illnesses associated with high BMI and smoking?
  - Are medical protocols and procedures initiated based on BMI and smoking signals or the actual presence of disease?

---

## Acknowledgements & Credits

- **Dataset Source:** [Kaggle → Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
- **Google Gemini** [Link](https://gemini.google.com/app)  

---

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/)

---
