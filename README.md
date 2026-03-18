# Granger Causality Analysis of Average Hourly Wages and the U.S. Housing Price Index
- DS 4002 Group 5, Project 2
- Group Leader: Jonathan Sutkus
- Group Members: Jonathan Sutkus, Siwen Liao, Jonah Lee
- Mar 18, 2026

## Repository Contents
The goal of this project is to perform a Granger Causality analysis to determine whether average hourly wage in the United States can be a reliable predictor of the U.S. National Home Price Index (USNHPI). The DS-4002_Group5_Project2 repository contains the DATA folder (includes our dataset of interest as well as more information about the data located in the data appendix), the SCRIPTS folder (includes code for preprocessing/cleaning the dataset, running the Granger Causaility to show predictive power, and performing a hypothesis test to determine statistical significance), the OUTPUTS folder (contains screenshots or PDFs of our results from the Granger Causality and the hypothesis test), and the LICENSE.md and README.md files.

## Section 1: Software and Platform

### Software/Platform
This project was developed and run using: 
- Google Colab/Jupyter Notebook on a Mac

### Packages
The following Python packages are required:


## Section 2: Documentation Map
```text
DS-4002_Group5_Project1/
│
├── DATA/
│ ├── P2_Data.csv
│ ├── P2_Data_Appendix.csv
│
├── OUTPUT/
│ ├── 
│ ├── 
│ ├── 
│ ├── 
│ ├── 
│ ├── 
│ ├── 
│
├── SCRIPTS/
│ ├── 
│ ├── 
│ ├── 
│
├── LICENSE
└── README.md
```

### Folder Descriptions
- **DATA**: Contains our datatset and the data appendix that includes more information about our variables and observations.
  - Original dataset of 238 months (or observations) ranging from March of 2006 to December of 2025. 
  - Data Appendix looking into our unit of observation as well as describing all of the key variables we will be utilizing in our analysis alongside some exploratory visuals associated with some of our key variables. 
- **SCRIPTS**: Contains python scripts for data preprocessing/cleaning, the Granger Causality analysis, and hypothesis testing.
- **OUTPUT**: Contains screenshots of the sample coherence scores when finding the optimal k value to fit the LDA model, the evaluation metrics for the final model, and graphics for the hypothesis test. Contains PDFs of the hypothesis testing results, the topic-word probability distribution for the LDA model, the most common topics by sentiment (positive, negative, and neutral), and the topic distribution for positive and negative reviews.
- **LICENSE**: MIT license was selected based on recommendation from the DS 4002 Ml3 Rubric.
- **README.md**: Instructions, documentation, and respository overview. 

## Section 3: Instructions for Reproduction


## References

[1] Eric, “Introduction to Granger Causality,” Aptech Systems Blog, Oct. 4, 2021. [Online]. Available: https://www.aptech.com/blog/introduction-to-granger-causality/. [Accessed: Mar. 11, 2026].
[2] Grewal, A., Hepburn, K. J., Lear, S. A., Adshade, M., & Card, K. G. (2024). The impact of housing prices on residents’ health: A systematic review. BMC Public Health. Retrieved from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10983630/
[3] Louie, S., Mondragon, J., & Wieland, J. F. (2025). Supply constraints do not explain house price and quantity growth across U.S. cities (Federal Reserve Bank of San Francisco Working Paper No. 2025-06). Federal Reserve Bank of San Francisco. https://www.frbsf.org/wp-content/uploads/wp2025-06.pdf
[4] PhD Students in Data Science Batch 2023, Asian Institute of Management, “Chapter 4: Granger Causality Test,” Time Series Analysis Handbook, 2020. [Online]. Available: https://phdinds-aim.github.io/time_series_handbook/04_GrangerCausality/04_GrangerCausality.html. [Accessed: Mar. 9, 2026].
[5] ScienceDirect. (n.d.). Granger-causality. In ScienceDirect Topics. Elsevier. Retrieved February 25, 2026, from https://www.sciencedirect.com/topics/social-sciences/granger-causality
[6] U.S. Bureau of Labor Statistics. (n.d.). Average hourly earnings of all employees, total private (CES0500000003). Retrieved March 11, 2026, from FRED, Federal Reserve Bank of St. Louis: https://fred.stlouisfed.org/series/CES0500000003
[7] U.S. Federal Housing Finance Agency. (n.d.). S&P/Case-Shiller U.S. National Home Price Index (CSUSHPINSA). Retrieved March 11, 2026, from FRED, Federal Reserve Bank of St. Louis: https://fred.stlouisfed.org/series/CSUSHPINSA
