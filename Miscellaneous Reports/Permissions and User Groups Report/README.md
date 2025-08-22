# Permissions_and_User_Groups Velocity Report
Get the User and User Group permissions for one project, all projects, or a user selected item location. 

## Overview
This Velocity report generates a context-insensitive Excel `.xlsx` file with two sheets:

- **Sheet 1:** Lists permissions for the selected object/s (only one of these selections is optional per report run):
  - **This Project Only:** Active export project
  - **Include All Projects:** All active projects in the organization
  - **Item Location:** A single active item in the project tree

- **Sheet 2:** Lists unique user groups found on Sheet 1.

## Example Output 


## Installation Configuration 

1. Upload the file `Permissions_and_User_Groups.vm`.
2. Select the report type: **Velocity**.
3. Choose the output format: **Excel (.xlsx)**.




## Report Criteria

| Type    | Display              | Name                   |
|---------|----------------------|------------------------|
| Boolean | This Project Only    | report_A_Project       |
| Boolean | Include All Projects | report_B_AllProjects   |
| Location| Item Location        | report_C_ItemLocation  |


## Report Run Instructions

- From a project go to Reports > Run report 
- Choose 1 parameter per run. 
- The output Excel file will contain permissions and user group information as described.

---
**Note:** The report uses the Jama Software Velocity API and standard Velocity macros for data retrieval and formatting.