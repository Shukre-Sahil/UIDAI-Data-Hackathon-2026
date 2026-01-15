

## Project Overview

**Project Title**: Aadhaar Enrolment Data Analysis and Insights  
**Level**: Intermediate  
**Domain**: Data Analytics and Public Policy
**Year Covered**: 2025

This project analyzes anonymised Aadhaar enrolment data released by **UIDAI** as part of the **Government of India Data Hackathon 2026**. The project focuses on identifying demographic and geographic enrolment patterns and converting raw data into actionable insights that can support data driven decision making and administrative improvements.


## Objectives
1. Analyze Aadhaar enrolment patterns across states districts and age groups.
2. Identify enrolment intensity variations to highlight regional disparities.
3. Understand age group contribution to overall enrolment activity.
4. Develop actionable recommendations for enrolment planning and outreach.
5. Demonstrate data analysis skills using real world government datasets.


## Dataset Information

**Source UIDAI Aadhaar Enrolment Dataset**
**Type Anonymised aggregated data**
**Year 2025**


**Key Columns**
- date
- state
- district
- pincode
- age_0_5
- age_5_17
- age_18_greater
  
Multiple CSV files provided by UIDAI were merged during preprocessing.


## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook


## Project Structure

1 **Data Preparation**
- Merged multiple Aadhaar enrolment CSV files.
- Parsed and standardized date formats.
- Validated numerical fields.
- Created derived metrics such as total enrolment


2 **Data Analysis**

- Univariate Analysis
  -- Age group wise enrolment distribution.
  
- Bivariate Analysis
  -- State wise Aadhaar enrolment comparison.
  -- District wise enrolment intensity analysis.

- Trivariate Analysis
  -- Child versus adult enrolment ratio across states.
  -- Each analysis includes visualizations and written insights.


## Key Insights

- Aadhaar enrolment intensity varies significantly across districts.
- Early age enrolment dominates overall enrolment activity.
- High population states record the highest enrolment volumes.
- Child enrolment ratios differ across states indicating regional gaps.


 ## Solution Framework and Recommendations

- District level resource allocation based on enrolment intensity.
- Strengthening child Aadhaar enrolment through school and health center initiatives.
- Age group aware enrolment strategies.
- Data driven monitoring indicators for administrative planning.


## Limitations

- Dataset covers a single year limiting temporal trend analysis.
- Aggregated data restricts individual level inference.
- Population adjusted enrolment metrics were not available.


## Future Scope

- Extend analysis to multi year enrolment data.
- Integrate demographic and biometric update datasets.
- Build interactive dashboards for real time monitoring.
- Introduce population normalized enrolment indicators


## Repository Structure

- `UIDAI_Aadhaar_Enrolment_Analysis.ipynb` is a Jupyter Notebook containing complete analysis.

- `api_data_aadhar_enrolment_0_500000.zip` is zipped file containing Aadhaar enrolment datasets.

- `ProjectReport - UIDAI_9403.pdf` is the Final project report PDF.

- `README.md` Project documentation


## How to set up this locally

**Clone this repository using the link below**
- ` git clone https://github.com/Shukre-Sahil/UIDAI-Data-Hackathon-2026.git `
- Download and extract the dataset.
- Run the `UIDAI_Aadhaar_Enrolment_Analysis.ipynb` in Jupyter Notebook or VS code.

## Author - Sahil Shukre

This project showcases Data analysis (using Python) skills essential for database management and generating meaningful insights. 

Thank you for your interest in this project!





