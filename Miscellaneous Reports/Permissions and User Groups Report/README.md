###### Permissions and User Groups Velocity Report
Get the User and User Group permissions for one project, all projects, or a user selected item location. 

## Overview
This Velocity report generates a context-insensitive Excel `.xlsx` file with two sheets:

- **Sheet 1:** Lists permissions for the selected object/s (only one of these selections is optional per report run):
  - **This Project Only:** Active export project
  - **Include All Projects:** All active projects in the organization
  - **Item Location:** A single active item in the project tree

- **Sheet 2:** Lists unique user groups found on Sheet 1.

## Example Output 

![permissions-report-example-output](https://github.com/user-attachments/assets/e343bba6-bff4-4a58-adca-cf521a204b5b)

## Installation Configuration 


1. Upload the file `Permissions_and_User_Groups.vm`.
2. Select the report type: **Velocity**.
3. Choose the output format: **Excel (.xlsx)**.



![permissions-report-installation-configuration](https://github.com/user-attachments/assets/65bee8e6-4302-4231-9264-b7bc1ae9cba5)



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


