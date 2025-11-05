# Medication Adherence Analysis for GLP-1 Drugs

## Overview
This project analyzes medication adherence patterns for GLP-1 (Glucagon-Like Peptide-1) drugs, providing insights into patient compliance, discontinuation rates, and demographic factors affecting adherence.

## Dashboard Features

### Key Metrics
- **Overall Adherence Rate**: 60.00%
- **Discontinuation Rate**: 40.00%
- **Average Treatment Duration**: 221.18 days

### Visualizations

#### Adherence Analysis
- **Adherence Rate by Gender**: Breakdown of medication compliance across male and female patients
- **Discontinuation Rate by Gender**: Gender-specific discontinuation patterns

#### Geographic Distribution
- **Provider and Region Map**: Interactive geographical visualization showing provider locations across Midwest, Northeast, South, and West regions

#### Demographic Insights
- **Discontinuation Rate by Age Group**: Analysis across different age demographics
- **Discontinuation Rate by Drug**: Comparison of adherence across different GLP-1 medications including:
  - Semaglutide
  - Tirzepatide
  - Dulaglutide
  - Liraglutide

## Data Structure

The analysis includes the following key data fields:
- Patient demographics (Age, Gender, AgeGroup)
- Medication information (Drug, Indication)
- Adherence metrics (Adherence Rate %, Discontinuation Rate %)
- Treatment duration (DurationDays, Average Duration)
- Provider and geographic data (Provider, Region)
- Dates (EndDate, StartDate)
- Flags (Disc_Flag, Discontinued)

## Technology Stack
- **Visualization Platform**: Microsoft Power BI
- **Data Source**: Patient medication records
- **Analysis Period**: March 19 - March 21, 2024

## Filters and Interactivity

The dashboard includes multiple filter options:
- Discontinuation Rate by AgeGroup
- Drug selection filter
- Page-level and report-level filters
- Interactive drill-down capabilities

## Use Cases

This analysis can be used to:
- Identify adherence trends across different patient populations
- Optimize intervention strategies for at-risk patient groups
- Compare effectiveness of different GLP-1 medications
- Support clinical decision-making and patient care improvements
- Inform resource allocation across geographic regions

## Getting Started

### Prerequisites
- Microsoft Power BI Desktop (for .pbix files)
- Access to the medication adherence dummy dataset. 

### Installation
1. Clone this repository
2. Open the Power BI file (.pbix) in Power BI Desktop
3. Refresh data connections if needed
4. Explore the interactive dashboard

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- New visualizations
- Enhanced analysis methodologies
- Bug fixes
- Documentation improvements

## Contact

LinkedIn: https://www.linkedin.com/in/deboleena-thakur-ms-hcda-073564117/
_______________________________________________________________________________________________________
Disclaimer: The data used in this project is dummy data and has no resemblance to real life EHR data.
