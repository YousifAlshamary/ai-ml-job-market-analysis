# AI/ML Job Market Analysis

## Overview

This project analyzes a sample of **10 Machine Learning and AI job postings** to identify the technologies, skills, experience requirements, education levels, work arrangements, and visa sponsorship patterns commonly requested by employers.

The project was built as a practical application of Python, REST APIs, Pandas, and exploratory data analysis.

## Objectives

The analysis answers questions such as:

- Which technologies appear most frequently in AI/ML job postings?
- Which skills are most commonly requested?
- How much minimum experience do these positions require?
- What education levels are most common?
- How common are hybrid and in-person positions?
- How frequently do these positions offer visa sponsorship?
- Which technologies are commonly associated with Python-based roles?

## Data Source

The job postings were collected using a REST API and processed using Python.

The dataset contains **10 AI/ML job postings** with structured information including:

- Job title
- Technologies
- Skills
- Education level
- Experience requirements
- Experience level
- Location type
- Visa sponsorship
- Job requirements

A sample of the processed dataset is included in the `data/` directory.

## Technologies Used

- Python
- Pandas
- REST APIs
- Jupyter Notebook
- NumPy
- Data Analysis
- Exploratory Data Analysis (EDA)

## Analysis Performed

### Technology Analysis

The most frequently mentioned technologies were:

| Technology | Percentage of Job Postings |
|---|---:|
| Python | 70% |
| Scikit-learn | 60% |
| PyTorch | 60% |
| TensorFlow | 60% |
| Pandas | 50% |
| NumPy | 50% |
| DVC | 40% |
| Tableau | 20% |
| Jupyter | 20% |
| Java | 20% |

### Skills Analysis

The most frequently requested skills included:

| Skill | Percentage of Job Postings |
|---|---:|
| Machine Learning | 70% |
| Data Engineering | 40% |
| Cloud Infrastructure | 40% |
| Weak Supervision | 20% |
| Communication | 20% |
| Active Learning | 20% |
| Algorithms | 20% |
| Data Analysis | 20% |
| Deep Learning | 20% |
| Data Structures | 20% |

### Experience Requirements

Among the **9 job postings with available minimum-experience data**:

- Average minimum experience: **4.1 years**
- Median minimum experience: **3 years**
- Minimum: **2 years**
- Maximum: **8 years**
- 55.6% required **3 years** of minimum experience

### Education Requirements

Across the 10 job postings:

- **80%** required a Bachelor's degree
- **20%** required a Master's degree

### Work Arrangement

- **80%** of positions were in-person
- **20%** were hybrid

### Visa Sponsorship

- **20%** of positions offered visa sponsorship
- **80%** did not offer visa sponsorship

The analysis also compared visa sponsorship against work arrangement using a Pandas cross-tabulation.

## Key Findings

The sample suggests that **Python is the dominant technology** across these AI/ML job postings, appearing in 70% of listings.

Machine learning frameworks such as **Scikit-learn, PyTorch, and TensorFlow** were also frequently mentioned, each appearing in 60% of the postings.

The results also indicate that employers in this sample commonly expect candidates to have practical knowledge across multiple areas, including machine learning, data engineering, cloud infrastructure, data analysis, and algorithms.

Most positions in the sample required a Bachelor's degree, while the average minimum experience requirement was approximately four years.

## Project Structure

```text
ai-ml-job-market-analysis/
│
├── data/
│   └── job_sample.csv
│
├── notebook/
│   └── ai_ml_job_market_analysis.ipynb
│
├── .gitignore
└── README.md
```

## How to Run

Clone the repository:

```bash
git clone https://github.com/YousifAlshamary/ai-ml-job-market-analysis.git
```

Install the required Python libraries:

```bash
pip install pandas requests numpy jupyter
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebook/ai_ml_job_market_analysis.ipynb
```

## Notes

This project uses a relatively small sample of 10 job postings and should therefore be viewed as a practice exploratory analysis rather than a statistically representative study of the entire AI/ML job market.

The project was created to practice working with REST APIs, structured data, data cleaning, Pandas, aggregation, and exploratory data analysis.

## Author

**Yousif Alshamary**

Mechatronics Engineer | Python | AI/ML | Generative AI
