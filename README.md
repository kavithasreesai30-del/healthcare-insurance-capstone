# Healthcare Insurance Cost Analysis

## Introduction

This project analyses healthcare insurance data to investigate how personal, lifestyle and geographic factors are associated with medical insurance charges.

The project uses Python data analytics techniques to clean, explore and visualise the dataset. The analysis investigates patterns in insurance charges and identifies the variables showing the strongest relationships with costs.

## Dataset Content

The dataset contains information about the relationship between personal health, demographic and geographic factors and medical insurance charges.

The dataset contains 1,338 records and seven variables:

* `age`
* `sex`
* `bmi`
* `children`
* `smoker`
* `region`
* `charges`

The dataset was cleaned during the project by checking for missing values, identifying and removing duplicate records, validating categorical values and reviewing numerical variables. After duplicate removal, 1,337 records remained.

A derived `bmi_category` variable was also created to support further analysis.

## Business Requirements

The project aims to provide useful insights into factors associated with healthcare insurance charges.

The business requirements are to:

1. Identify patterns in the distribution of insurance charges.
2. Investigate how personal and lifestyle factors are associated with insurance charges.
3. Compare insurance charges across demographic and geographic groups.
4. Identify numerical variables showing relationships with insurance charges.
5. Present findings through clear and appropriate visualisations.
6. Identify opportunities for future predictive analytics and AI applications.

## Hypothesis and How to Validate

### Hypothesis

Personal and lifestyle factors are associated with differences in healthcare insurance charges, with smoking status expected to show a particularly strong relationship.

### Validation

The hypothesis is investigated using:

* descriptive statistics;
* average insurance-charge comparisons;
* histograms;
* box plots;
* bar charts;
* correlation analysis;
* a correlation heatmap; and
* an interactive Plotly visualisation.

The analysis supports the hypothesis, particularly through the substantial difference in average charges between smokers and non-smokers. Age and BMI also show positive relationships with charges.

These findings represent associations within the dataset and do not establish causation.

## Project Plan

The project was completed through the following stages:

1. Understand the business problem and research questions.
2. Load and investigate the dataset.
3. Clean and validate the data.
4. Perform descriptive analysis.
5. Analyse individual variables and their relationship with insurance charges.
6. Create the derived BMI category feature.
7. Perform correlation analysis.
8. Create static and interactive visualisations.
9. Compare key findings and evaluate the hypothesis.
10. Identify healthcare applications and future AI opportunities.
11. Document the project and prepare the final repository.

## Rationale for Mapping Business Requirements to Data Visualisations

Different visualisation techniques were selected according to the type of question being investigated.

* **Histograms** were used to examine the distribution of insurance charges.
* **Bar charts** were used to compare average charges between groups.
* **Box plots** were used to compare the distribution and spread of charges across categories.
* **Correlation heatmaps** were used to examine linear relationships between numerical variables.
* **Scatter plots** were used to investigate relationships between numerical variables and insurance charges.
* **Plotly** was used to provide an interactive visualisation allowing the relationship between age, insurance charges and smoking status to be explored.

Using several visualisation techniques provides complementary evidence rather than relying on a single chart type.

## Analysis Techniques Used

In this project,I used a combination of data preparation, statistical analysis and visualisation techniques to investigate the research questions and extract business insights.

The main techniques included:

* data inspection and validation
* descriptive statistics
* checking for missing values
* duplicate detection and removal
* categorical value validation
* numerical value validation
* group-based average calculations
* derived feature creation using BMI categories
* correlation analysis
* investigation of relationships between numerical variables and insurance charges
* distribution analysis of insurance charges
* comparison of insurance charges across demographic, lifestyle and geographic groups
* use of Matplotlib for initial data visualisation
* use of Seaborn for statistical visualisation and correlation analysis
* use of Plotly for interactive visualisation
* interpretation of visualisations to identify patterns and business insights and
* evaluation of findings against the project hypothesis.

Using multiple visualisation approaches helped provide complementary evidence when investigating factors associated with insurance charges.


## Ethical Considerations

The dataset contains personal and health-related characteristics. Although this project uses an educational dataset rather than identifying real individuals, healthcare data should always be handled responsibly.

Any future predictive model should consider privacy, fairness, potential bias and responsible interpretation. Insurance predictions should not be treated as proof of individual risk or causation.

## Fixed Bugs

During development, technical issues were encountered with Python environments, package installation and Plotly rendering.

These included environment and package compatibility issues and difficulties displaying Plotly interactive visualisations in the notebook.

The issues were resolved by configuring the project environment, installing the required dependencies and testing the Plotly visualisation in the development environment.

## Development Roadmap

During the development of this project, several technical and analytical challenges were encountered. Working through these issues provided useful practical experience in Python, Pandas and data visualisation, including troubleshooting the project environment and resolving visualisation and package-related problems.

The project also highlighted areas for further development. Future learning will focus on strengthening statistical understanding and developing greater confidence in selecting appropriate variables and visualisation techniques for different analytical questions.

A further area for improvement is hypothesis development. Future projects will begin with clearer hypotheses and research questions before selecting the analysis and visualisations needed to investigate them.

For this project, future development could include building and evaluating a machine-learning model to predict insurance charges, comparing algorithms, investigating interactions between important variables and assessing model accuracy and fairness.

## Main Data Analysis Libraries

### Pandas

Pandas was used for loading, cleaning, transforming and analysing the dataset.

### NumPy

NumPy was used to support numerical analysis and data processing.

### Matplotlib

Matplotlib was used to create static visualisations including histograms and charts.

### Seaborn

Seaborn was used to create statistical visualisations including box plots, scatter plots and the correlation heatmap.

### Plotly

Plotly was used to create an interactive visualisation exploring age, insurance charges and smoking status.

## Conclusions

The analysis found that smoking status shows the largest difference in average insurance charges in this dataset.

Age has the strongest positive correlation with insurance charges among the numerical variables analysed, while BMI shows a weaker positive relationship. The number of children has a very weak correlation and does not show a clear consistent pattern.

Differences were also observed across sex and region, although these were smaller than the difference associated with smoking status.

Overall, the analysis demonstrates how data analytics can identify patterns in healthcare insurance costs and provide a foundation for future predictive modelling.

## Credits

### Content
The project was developed using course materials, Python documentation and online learning resources.

AI assistance, including ChatGPT, was used to support learning, explain Python concepts, troubleshoot technical issues and help structure documentation. Code was reviewed, tested and adapted for this project.

The original healthcare insurance dataset was obtained from Kaggle and is used for educational analysis.

The project structure and learning requirements were informed by the Code Institute LMS materials.

Python and library documentation were consulted during development.

### References

* Code Institute LMS material
* Plotly documentation
* Matplotlib documentation
* Seaborn documentation
* Pandas documentation
* NumPy documentation


### Acknowledgements

Thanks to the Code Institute tutors and cohort members for guidance and support during the project
