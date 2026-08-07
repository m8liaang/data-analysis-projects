# Measles Cases Data Visualization Project
An exploratory data visualization project that used plotly.express to model measles cases in the United States and its most affected states (Florida, Virginia, Texas, Arizona, Utah, and South Carolina).

## Data Source
Users should obtain the dataset directly from the original source and comply with its applicable terms of use.

Data is from [JHU Measles Tracking Team Data Repository at Johns Hopkins University](https://github.com/CSSEGISandData/measles_data).

## Toolkit/Python Libraries Used
Pandas, plotly

## Analysis Performed
- Data cleaning and restructuring
- Data visualization (shown in img folder)

## Findings
The epidemic curves revealed that there were/are, in fact, measles outbreaks.

1. Outbreak curves are present in the most affected U.S. states (Florida, Virginia, Texas, Arizona, Utah, and South Carolina). South Carolina had the largest outbreak (with its peak being over 100 cases), while Texas had experienced two outbreaks.
2. South Carolina, Texas, and Utah are the three U.S. states with the most measles cases (first, second, and third in that order).
3. Many of the cases in the dataset were confirmed by laboratory testing and were local cases. There were more cases of measles seen in unvaccinated individuals than vaccinated ones.
4. 2026 saw a rise in measles cases throughout the United States. Three outbreaks have occurred since January 2025. 

## Project Structure
```text
measles_cases/
├── img/
|   └── cases/
│   │    ├── case_type.png
│   │    ├── case_US.png
│   │    └── cases_year.png
|   └── states/
│   │   ├── arizona.png
│   │   ├── florida.png
│   │   ├── south_carolina.png
│   │   ├── texas.png
│   │   ├── utah.png
│   │   └── virginia.png
│   └── most_affected_states.png
├── README.md
└── measles_cases.ipynb
```
