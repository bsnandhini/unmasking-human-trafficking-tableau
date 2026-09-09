# Unmasking Human Trafficking - Historical Data Analysis Using Tableau

## Project Overview

This project presents a historical data analysis of **human trafficking cases in India** using **Tableau**.

The analysis focuses on state-wise trafficking cases, trafficking purposes, victims, police case handling, court outcomes, and related population and crime-rate information.

Interactive Tableau visualizations and dashboards were created to explore patterns and provide a clear view of the available human trafficking data.


## Objectives

* Analyze human trafficking cases across States/UTs.
* Examine different purposes of human trafficking.
* Analyze victim and rescued-victim information by gender and age group.
* Study police case handling, chargesheeting, and final reports.
* Analyze court outcomes such as convictions and acquittals/discharges.
* Compare state-wise reported cases with population and IPC crime-rate information.
* Create interactive Tableau dashboards for data exploration.



## Dataset Description

The project uses multiple CSV datasets covering different aspects of human trafficking data.

| Dataset                         | Description                                                                              |
| ------------------------------- | ---------------------------------------------------------------------------------------- |
| `states.csv`                    | State/UT-wise reported cases, percentage share, projected population, and IPC crime rate |
| `human_trafficking_purpose.csv` | Human trafficking cases categorized by purpose                                           |
| `police.csv`                    | Police-handled cases, chargesheeting, final reports, and related rates                   |
| `culprits_disposal_2018.csv`    | Persons arrested, chargesheeted, convicted, and acquitted/discharged                     |
| `rescued.csv`                   | Rescued victims by gender and nationality                                                |
| `victims.csv`                   | Rescued victims by State/UT, gender, and age group                                       |
| `victims_trafficked.csv`        | Trafficked victims by State/UT, gender, and age group                                    |



## Tools & Technologies

* **Tableau**  - Data visualization and dashboard development
* **CSV** - Source datasets
* **Data Analysis** - Exploratory analysis and comparison of human trafficking data
* **Data Visualization** -  Charts, graphs, and interactive dashboards



##  Data Preparation

The datasets were prepared for Tableau analysis by working with the available State/UT, category, gender, age group, and numerical fields.

The data was organized into suitable datasets for analyzing:

* State-wise cases
* Trafficking purposes
* Victims and rescued victims
* Police case handling
* Culprit disposal
* Court outcomes
* Population and IPC crime-rate information


## Analysis & Visualizations

The project includes visualizations covering:

### Human Trafficking Purposes

* Forced Labour
* Sexual Exploitation for Prostitution
* Domestic Servitude
* Forced Marriage
* Petty Crimes
* Child Pornography
* Begging
* Removal of Organs
* Other Reasons

### Police & Court Analysis

* Total number of cases handled by police
* Cases chargesheeted by police
* Cases with final reports by police
* Chargesheeting rate
* Cases convicted by court
* Cases acquitted/discharged by court
* Cases in which trials were completed
* Conviction rate
* Culprits disposal in 2018

### Victim Analysis

* Victims trafficked
* Victims rescued
* Gender-wise victim analysis
* Age-group analysis
* Nationality information for rescued victims

### State-Level Analysis

* State-wise reported cases
* Percentage share of state
* Mid-year projected population
* Rate of cognizable crimes (IPC)

---

## Dashboard Screenshots

### Dashboard 1

![Dashboard 1](screenshots/01-dashboard-1.png)

### Dashboard 2

![Dashboard 2](screenshots/02-dashboard-2.png)

### Human Trafficking Statistics

![All Human Trafficking Statistics](screenshots/03-all-human-trafficking-statistics.png)

### Begging Statistics

![Begging Statistics](screenshots/04-begging-statistics.png)

### Culprits Disposal - 2018

![Culprits Disposal 2018](screenshots/05-culprits-disposal-2018.png)

### Police Cases - Chargesheeted, Rate & Final Reports

![Police Cases](screenshots/06-police-cases-charged-rate-final-reports-2018.png)

### Court Cases - Convicted, Acquitted & Completed Trials

![Court Cases](screenshots/07-court-cases-convicted-acquitted-completed-rate-2018.png)

### Child Pornography Statistics

![Child Pornography](screenshots/08-child-pornography-statistics.png)

### Domestic Servitude Statistics

![Domestic Servitude](screenshots/09-domestic-servitude-statistics.png)

### Forced Labour Statistics

![Forced Labour](screenshots/10-forced-labour-statistics.png)

### Forced Marriage Statistics

![Forced Marriage](screenshots/11-forced-marriage-statistics.png)

### IPC Analysis

![IPC](screenshots/12-ipc.png)

### Mid-Year Projected Population

![Mid-Year Projected Population](screenshots/13-mid-year-projected-population.png)

### Other Human Trafficking Reasons

![Other Reasons](screenshots/14-other-human-trafficking-reasons.png)

### Petty Crime Statistics

![Petty Crime](screenshots/15-petty-crime-statistics.png)

### Removal of Organs Statistics

![Removal of Organs](screenshots/16-removal-of-organs-statistics.png)

### Sexual Exploitation for Prostitution

![Sexual Exploitation](screenshots/17-sexual-exploitation-prostitution.png)

### State-Wise Cases Reported

![State-Wise Cases](screenshots/18-state-wise-cases-reported.png)

### Total Cases Handled by Police

![Total Cases Handled](screenshots/19-total-cases-handled-by-police.png)

### Victims Trafficked Count

![Victims Trafficked](screenshots/20-victims-trafficked-count.png)

### Victims Count

![Victims Count](screenshots/21-victims-count.png)

### Additional Analysis

![Additional Victim Analysis](screenshots/22-victims-rescued.png)

---

##  Key Insights

The dashboards enable exploration of:

* Differences in reported trafficking cases across States/UTs.
* Distribution of trafficking cases across different exploitation purposes.
* Gender and age-group patterns among victims.
* Police case handling and chargesheeting patterns.
* Court-level conviction and acquittal/discharge outcomes.
* Relationship between reported cases, projected population, and IPC crime rate.

> Detailed findings can be explored through the Tableau dashboards and visualizations included in this repository.

---

##  Project Structure

unmasking-human-trafficking-tableau/
│
├── README.md
├── data/
│   ├── culprits_disposal_2018.csv
│   ├── human_trafficking_purpose.csv
│   ├── police.csv
│   ├── rescued.csv
│   ├── states.csv
│   ├── victims.csv
│   └── victims_trafficked.csv
│
├── screenshots/
│   ├── 01-dashboard-1.png
│   ├── 02-dashboard-2.png
│   ├── 03-all-human-trafficking-statistics.png
│   ├── ...
│   └── 22-victims-rescued.png
│
└── tableau/
    └── states-data-analysis.twb


---

## How to Open the Tableau Workbook

1. Install Tableau Desktop.
2. Clone or download this repository.
3. Open the `tableau` folder.
4. Open `states-data-analysis.twb` using Tableau Desktop.
5. If Tableau asks for the data source location, connect the workbook to the CSV files available in the `data` folder.
6. Explore the worksheets, visualizations, and dashboards.

---

## Project Focus

**Human Trafficking Data Analysis | State-wise Analysis | Victim Analysis | Police & Court Analysis | Tableau Dashboards**
