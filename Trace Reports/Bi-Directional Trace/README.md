# Bi-Directional Trace Report - 2 Up 2 Down Trace

## Description
This report constructs a single sheet excel trace report that can trace up to 2 levels both upstream and downstream from your exported source items. This report support merged cells for items with multiple relationships and will include test runs if encountered. Report only supplies generic fields of ID, Project ID, Item Name, and Item Status. 

For baseline context exports the report will ensure trace output is based upon relationship paths at the time of selected baseline creation. In addition, only test runs created prior or at the time of baseline created will be presented.

## Preview Image
If Two Levels parameter is checked at export:
![2up_2d_mergeCells](https://user-images.githubusercontent.com/99203913/189504820-f58f5a56-b15d-4c4f-9279-4c70aa8a00b2.png)

If default export (1 level up/down from the source):
![default_2up_2dn_mergeCells](https://user-images.githubusercontent.com/99203913/189504870-11e9272d-c1fe-4769-83a8-4f3df257a2e6.png)


## Installation Instructions
1. Go to the Admin section of Jama
1. Click the Reports tab
1. Click Add Report
1. Fill in the Add/Edit Report form as shown below.
1. Click Save

![reportInstallation2up2dn](https://user-images.githubusercontent.com/99203913/189504914-454592b8-8706-409b-bfbe-a59cc24fefb7.png)


## NOTES: 
- Your Organization field will have a different value.  
- Rename the report to anything you like


## Running the Report
1. Go to the Project section of Jama
1. Click into the context sensitive reports menu option via reading view "Export > View All Export Options"
1. Select the report name you specified when installing the report.
1  Determine report run parameters: Merge cells and or Two Levels Up/Down 
1. Click Run Report
