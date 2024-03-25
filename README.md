<a name="readme-top"></a>

<div align="center">
   <h1><b>Analysing Funding in the Indian Startup Ecosystem</b></h1>
</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [Introduction ](#introduction-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
  - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

# Introduction <a name="about-project"></a>

The success of a start-up is heavily reliant on ideas, innovation, and execution. However, these alone may not be sufficient. It the financial backing or “funding” from investors that enables or allows start-ups and other entrepreneurial projects with great aspirations to dream big, achieve wealth, and make a significant impacts. In this project, I will be investigating the funding that start-ups in India received from investors from the year 2018 to 2021. The dataset provided includes separate csv files for each year’s funding data. These files contain details about the start-ups, the funding they received, and the investors informations.

The purpose of this project is to try and venture into the Indian start-up ecosystem. As the data expert of the team, I am to investigate the ecosystem and propose the best course of action.

### Column names and description:

- Company/Brand: Name of the company/start-up

- Founded: Year start-up was founded

- Sector: Sector of service

- What it does: Description about Company

- Founders: Founders of the Company

- Investor: Investors

- City: Location of the Company

- Year: Year of Funding

- Amount($): Raised fund

- Stage: Round of funding reached

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="">Microsoft SQL Server</a></li>
  </ul>
</details>

<details>
<summary>Language</summary>
  <ul>
    <li><a href="">Python</a></li>
    <li><a href="">Jupyter Notebook</a></li>
  </ul>
</details>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- Features -->

## Key Features <a name="key-features"></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

Business Understanding
This is the initial phase where I define the business problem, objectives, and outcomes. I also identified the key stakeholders and understand their expectations.

2. Data Understanding
This phase involves the following steps:

Importation: Acquiring the necessary data for the project.
Data Loading: Loading the data into a suitable format for analysis.
Action Plan: Creating a plan for how to approach the data analysis.
Hypothesis: Formulating hypotheses that I will test during the analysis.
Business Questions: Identifying the key questions that the business needs answers to.
3. Data Preprocessing
This phase involves preparing the data for analysis. This could include data cleaning, data transformation, and data integration.

4. Data Cleaning
This phase involves identifying and correcting errors in the data, dealing with missing values, and removing duplicates.

5. Hypothesis Testing
This phase involves testing the hypotheses that were formulated during the data understanding phase. This could involve statistical tests to determine if there is a significant relationship between variables.

6. Exploratory Data Analysis (EDA)
This phase involves exploring the data to understand its characteristics and patterns. This could involve visualizing the data, calculating descriptive statistics, and identifying correlations.

7. Analysis of Business Questions
This phase involves using the insights gained from the EDA and hypothesis testing to answer the business questions identified earlier. This could involve building predictive trends, segmenting the data, or conducting further statistical tests.


<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python


### Setup

Clone this repository to your desired folder:


```sh
  cd my-folder
  git clone https://github.com/MoIdris/A-Data-Analytics-Project.git
```

Change into the cloned repository

```sh
  cd A-Data-Analytics-Project
  
```

Create a virtual environment

```sh

python -m venv env

```

Activate the virtual environment

```sh
    env/Scripts/activate
```



### Install

Here, you need to recursively install all the necessary packages to be imported in your notebook 

```sh
   pip install python-dotenv
   pip install pyodbc
   pip install numpy
   pip install pandas
   pip install seaborn
   pip install scipy
   pip install jupyterlab
```


### Usage

To view this analysis, visit the page (https://github.com/MoIdris/A-Data-Analytics-Project)

To download the notebook, execute the following steps:


- Navigate to the GitHub page (https://github.com/MoIdris/A-Data-Analytics-Project).
- Click on the notebook file name to open it.
- Once the file is open, you will see a Raw button on the top right of the file content. Click on this Raw button.
- The notebook content will be displayed in raw JSON format. Right-click anywhere on the page and select Save As or press Ctrl+S to save the file.
- In the Save dialog box, make sure to add the .ipynb extension to the file name if it’s not already there. For example, if the file name is notebook, change it to notebook.ipynb.
- Choose the location where you want to save the file and click Save.
- Now, you can open this .ipynb file using Jupyter Notebook on your local machine.
- **Please note** that the file might be saved as a .txt file by default, so ensure that you change the extension to .ipynb when saving

## Data Cleaning

The data used in this analysis was sourced from three different sources, github, sql server and onedrive, a connection was created with a connection string defined in the '.env' file

1. Data Collection: Gathering raw data from online database.

2. Data Integration: Consolidating data from different sources into a unified dataset.

3. Missing Value Handling: Identifying and dealing with missing values through imputation or removal.

4. Outlier Detection: Detecting and handling outliers that could skew the analysis results.

5. Normalization and Standardization: Ensuring consistency and comparability of data by normalizing or standardizing where necessary.

6. Data Validation: Verifying the integrity of the cleaned dataset to ensure accuracy in subsequent analyses.

## Data Representation

The cleaned data was represented in structured formats suitable for analysis. This included organizing data into tables and saving the unified dataset as a single '.csv' file. Visualization techniques such as charts, graphs, and maps were also employed to present key findings effectively.

## Analysis Methods

Various analytical methods and techniques were utilized to extract insights from the data:

1. Descriptive Statistics: Summarizing key metrics such as mean, median, mode, and standard deviation to describe the central tendency and dispersion of variables.
2. Time-Series Analysis: Examining trends and patterns over time to understand the evolution of the startup ecosystem.
3. Correlation Analysis: Investigating relationships between different variables, such as funding amount and startup success rate.
4. Segmentation Analysis: Grouping startups based on common characteristics (e.g., sector, funding stage) and analyzing each segment separately.
5. Predictive Modeling: Building predictive models to forecast future trends or identify factors influencing startup performance.

## Final Findings

Based on the analysis conducted, several key findings emerged:

1. Sectoral Trends: Identification of sectors experiencing rapid growth and emerging as key drivers of the Indian startup ecosystem.
2. Funding Patterns: Insights into the sources and distribution of funding across different stages of startup development.
3. Geographical Insights: Understanding regional variations in startup activity and investment flows within India.
4. Success Factors: Identification of factors correlated with startup success, including funding amount, team composition, and market positioning.
5. Challenges and Opportunities: Highlighting challenges faced by startups and opportunities for intervention and support from stakeholders.


<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

🕵🏽‍♀️ **Mohammed Idris**

- GitHub: [GitHub Profile](https://github.com/MoIdris)
- Twitter: [Twitter Handle](https://twitter.com/IdrisBaaba)
- LinkedIn: [LinkedIn Profile](www.linkedin.com/in/idris-ibn-mohammed)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>


- **Develop a model for this project**
  
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank all my team member for their coorperation, commitment and support. My greatest appreciation goes to Viollete and Rahael for their immense guidance and support. Thank you to all the free available resource made available online

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



