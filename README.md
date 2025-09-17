# Palmora-Group-HR-Analysis-DSA-Capstone-project-

## Project Topic: Palmora Group HR Analysis

### Project Overview 
This project aims to identify key areas within the Palmora group business that could give rise to gender related issues by analysing the company’s HR data and coming up with recommendations for the management’s attention.

### Data Source
The primary source of data used here is Palmoria Group emp-data.csv and Palmoria Group Bonus Rules.xlsx and this data was shared by the data analysis facilitator to all students for the project assessment.

Palmoria Group emp-data.csv : [Download Here](https://github.com/user-attachments/files/22387216/Palmoria.Group.emp-data.csv)

Palmoria Group Bonus Rules.xlsx : [Download Here](https://github.com/user-attachments/files/22387259/Palmoria.Group.Bonus.Rules.xlsx)

### Pointers taken note of during analysis

- The gender distribution in the organization? Distil to regions and departments
- Insights on performance ratings based on gender
- Analysis of the company’s salary structure to identify if there is a gender pay gap and identification of the department and regions that should be the focus of management
- A recent regulation was adopted which requires manufacturing companies to pay employees a minimum of $90,000
    - Identifying if Palmoria meet this requirement?
    - Pay distribution of employees grouped by a band of $10,000. For example:
    - Employees that fall into a band of $10,000 – $20,000, $20,000 – $30,000, etc.?
    - Visualize by regions
 
**Other case questions**

The organization also asked to help out with allocating the annual bonus pay to employees based on the performance rating using another data set that contains rules for making bonus
payments and the following calculations were made:

- The amount to be paid as a bonus to individual employees.
- Calculate the total amount to be paid to individual employees (salary inclusive of bonus).
- Total amount to be paid out per region and company-wide.

**Required steps that were taken**

- Generally, there are two genders in the organization. However, some employees refused to disclose their gender. I assigned a generic gender status to these employees.
- Some employees are without a salary because they are no longer with the company. I took those employees out.
- Some departments are indicated as “NULL”. I took them out too.
- I merged the two data sets together using both department and performance rating as co-keys.
- Added a custom column to determine annual bonus using this formula : [Salary] * [Bonus Rules.Value]
- Added another custom column to determine New salary using this formula : [Salary] + [Annual bonus]
- Added a conditional column for Rating sort.
- Added another conditional column for Minimum salary requirement : If Salary is 90,000 then "Paid below standard" else "Paid above standard".
- Added a conditional column for salary band.

### Visualization and Reporting

**Dashboard creation**

[Download here]








