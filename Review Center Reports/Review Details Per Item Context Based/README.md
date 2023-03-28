# Review Details Per Item Report (Context Based)

## Description
This report when exported from either a container item or single item present in the project tree or baseline will retrieve review data from each exported items associated reviews. The report includes a simple checkbox parameter option label "Show Items Latest Review Only" that when true will only extract each exported items latest review data. Alternatively if false the report will extract every review each exported items is associated with. In the event that a exported item does not have any associated reviews the report will still include it by only showing the Item ID and Item Name but a blank cells for all other columns.

The report organizes itself into five primary parent categories of data: Exported Item Data, Review Data, Review Item Data, Approvers Data, and Reviewers Data. Each section contains it's own collection of category specific data columns to provide you with a expanded informational overview of your items review data. In order to allow for simple navigation back to your Jama Connect instance hyperlinks are provided for any of the data provided in the report. In addition for assistance with confirming assigned users progress, in the event that the number of approvals and or reviews of a particular item match the number of Approver and or Reviewer users that cell will be colored green. Alternatively if any user has applied a rejection status or has not reviewed an assigned item then that cell will be colored red. 


## Preview Images

### All Item Reviews
![All Item Reviews](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Review%20Center%20Reports/Review%20Details%20Per%20Item%20Context%20Based/All_Item_Reviews.png)

### Only Most Recent Item Reviews
![Only Most Recent Item Reviews](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Review%20Center%20Reports/Review%20Details%20Per%20Item%20Context%20Based/Most_Recent_Item_Reviews.png)


## Installation Instructions
1. Go to the Admin section of Jama
1. Click the Reports tab
1. Click Add Report
1. Fill in the Add/Edit Report form as shown below.
1. Click Save

![Report Configuration](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Review%20Center%20Reports/Review%20Details%20Per%20Item%20Context%20Based/Config.png)

### Report Criteria
Ensure that no typos, leading, or trailing spaces are present in the *Name* field for the reports installation criteria.

| Type          | Display                               | Name                       |
| ------------- | ------------------------------------- | -------------------------- |
| Boolean       | Show Items Latest Review Only         | reportLatestReview         |


## Running the Report
1. Find the data set you would like to run the report on in your project tree 
1. Click Export
1. Select the report name you specified when installing the report.
1. Click Run Report
