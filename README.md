# Cost-Optimization-and-Resource-Efficiency-Analysis-for-NGO-s
This project presents a comprehensive data analysis conducted for a non-governmental organization (NGO) with the objective of improving cost efficiency and 
optimizing the allocation of donor funds. The study focuses on identifying inefficiencies in program spending, evaluating the alignment between costs and outcomes, 
and improving the transparency and effectiveness of fund utilization.

# Project Objective
The primary goal of this project is to support data-driven decision-making in NGO operations by:

- Analyzing high program costs and their justification relative to outcomes
- Identifying patterns of budget overuse or underuse across initiatives
- Evaluating the efficiency of donor fund allocation and its impact on program success
- Providing actionable insights to enhance financial planning, improve donor trust, and ensure sustainable operations

# Methodology Overview
The project employed a structured, insight-driven approach to analyze financial inefficiencies, improve cost control, and enhance the effective use of donor funds:

- Understanding Business Needs: Defined core financial issues, including high program costs, inconsistent budget performance, and inefficient allocation of donor contributions.
- Data Accessing: Imported and consolidated multiple datasets via Power Query, ensuring proper structure and validation through unique identifiers.
- Data Quality Review: Assess data integrity by identifying missing values, duplicates, errors & inconsistencies, and outliers that could affect analysis quality.
- Data Cleaning & Transformation: Applied Power Query to clean, standardize, and merge datasets, preparing the data for in-depth analysis and visualization.
- Analysis & Modeling: Explored patterns in spending and program performance to identify inefficiencies, budget discrepancies, and gaps in fund allocation.
- Data Visualization: Designed a focused set of visuals to communicate financial insights clearly:
- Cost-Benefit Analysis (Bubble Chart): Displays Program_ID, Number of Beneficiaries, and Cost per Beneficiary
- Variance Analysis (Clustered Column Chart): Illustrates overspent and underspent programs by Program_ID
- Fund Efficiency Analysis (Bubble Chart): Highlights Program_ID, Number of Beneficiaries, and Fund per Beneficiary
- Reporting & Communication: Delivered results through a clear visual report to support stakeholder understanding and data-driven decision-making.


# Tech Stack
Power BI

- For: - Data cleaning
       - Data Transformations
       - Data Modeling
       - Data Analysis
       - Visulaizations


# Description of the Dataset

Donor_and_Funding

- Donor_ID – Unique identifier for each donor
- Donor_Name – Name of the individual or organization providing funding
- Donation_Amount_USD – Total amount donated in USD
- Program_Funded_ID – ID of the program receiving the donation (links to Program table)
- Funding_Type – Type of donation (e.g., Recurring, One-time, Emergency)
- Program_Funded_Name – Name of the program funded by the donor

Finance_Data
- Program_ID – Unique identifier for each program
- Program_Name – Name of the program associated with the budget
- Budget_Allocated_USD – Total budget allocated to the program in USD
- Budget_Spent_USD – Actual amount spent by the program in USD
- Funding_Source – Source of funding (e.g., Government Grants, Corporate Sponsors, International Aid, Private Donations)

Programs_Data
- Program_ID – Unique identifier for each program
- Program_Name – Name of the program
- Sector – Program category (e.g., Health, Education, Livelihoods)
- Region – Geographic area where the program operates
- Start_Date – Date when the program begins
- End_Date – Date when the program is expected to end
- Number_of_Staff – Total number of staff assigned to the program
- Number_of_Volunteers – Total number of volunteers supporting the program
- Number_of_Beneficiaries – Number of individuals impacted by the program
- Program_Status – Current status of the program (e.g., Ongoing, Completed, Upcoming)
