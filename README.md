# The Cost of Connectivity: Social Media and Sleep Analysis

This repository investigates the relationship between social media usage patterns and sleep metrics (quality and duration) among individuals in Singapore. The project utilizes R for exploratory data analysis, interactive visualizations, and statistical simulations to evaluate how digital habits impact physical recovery.

## Key Technical Objectives
* **Behavioral Correlation:** Quantifying the impact of social media duration on sleep quality and total hours of rest.
* **Sampling Theory & CLT:** Demonstrating the Central Limit Theorem (CLT) by generating distribution of sample means from non-normal population data.
* **Interactive Visualization:** Utilizing `plotly` to create multidimensional views of behavioral data across different demographic segments.

## Technology Stack
* **Language:** R
* **Libraries:** tidyverse, plotly, janitor, sampling, RColorBrewer
* **Data Source:** National University of Singapore (via Kaggle)

## Analysis Summary

### 1. Social Media vs. Sleep Latency
The analysis explores the trade-off between digital engagement and rest. 
* **Sleep Quality:** Visualized the distribution of perceived sleep quality against daily social media minutes.
* **Relationship Trends:** Identified that as social media usage increases, there is a measurable shift in both the consistency and duration of sleep.

### 2. Central Limit Theorem (CLT) Simulation
A significant portion of this study is dedicated to proving the CLT using the social media usage variable.
* **Population Dynamics:** The raw usage data is non-normally distributed. 
* **Simulation:** By performing repeated sampling with varying sizes ($n=10, 20, 30, 40$), the analysis visualizes the convergence toward a normal distribution, illustrating the reliability of sample means in inferential statistics.

### 3. Sampling Methodology Comparison
The project compares different sampling techniques to assess their effectiveness in representing the population:
* **Simple Random Sampling (SRS)**
* **Systematic Sampling**
* **Stratified Sampling** (segmented by age/usage groups)

## Repository Structure
```text
├── data/               # Raw dataset (Social_Media_and_Sleep_Statistics.csv)
├── R/                  # R Markdown scripts and code chunks
├── results/            # Final interactive report (CS544Final_Duran.html)
└── requirements.txt    # List of required R packages
