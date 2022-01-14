# Review Details Per Item Report (Context Based)

## Details
This report can be exported on a collection of items of any type from the project tree constructing a single sheet excel export. The report will gather active reviews the item is included on, building a row of review details per item. 

The report will include the following fields per row: Item API ID, Item Type Key, Name, Review ID, Review Name, Review Version, Review Status, 
Close Date, # of Approvers, # of Items, Users who Approved the review, Users who Rejected the Review, # of Approvals, # of Rejections, and # of Comments per review.

By default the report will gather and build a row for every active review the item is on however a report parameter is included to filter the data by only the items most recent review. Should an item not have a review the report will only show the items API ID and name.

If the number of Approver users and review Approvals matches the "# Approvals" cell will be highlighted in green. If the review has any rejections the "# of Rejections" cell will be highlighted red. 




## Preview Images

### All Item Reviews
![All Item Reviews](https://github.com/JamaSoftware/Community-Reports/blob/master/Review%20Details%20Per%20Item%20Context%20Based/All_Item_Reviews.png)

### Only Most Recent Item Reviews
![Only Most Recent Item Reviews](https://github.com/JamaSoftware/Community-Reports/blob/master/Review%20Details%20Per%20Item%20Context%20Based/Most_Recent_Item_Reviews.png)

### Item with No Active Reviews
![Item with No Active Reviews](https://github.com/JamaSoftware/Community-Reports/blob/master/Review%20Details%20Per%20Item%20Context%20Based/Item_Without_Review.png)

## Installation Instructions
1. Go to the Admin section of Jama
1. Click the Reports tab
1. Click Add Report
1. Fill in the Add/Edit Report form as shown below.
1. Click Save
![Report Configuration](https://github.com/JamaSoftware/Community-Reports/blob/master/Review%20Details%20Per%20Item%20Context%20Based//Config.png)

## NOTES: 
- The report parameter display text is "Show Items Latest Review Only" and unique variable name for report code purposes (DO NOT CHANGE) is "reportLatestReview"
- Your Organization field will have a different value.  
- Rename the report to anyting you like
- Enable any report format that you'd like to use

## Running the Report
1. Find the data set you would like to run the report on in your project tree 
1. Click Export
1. Select the report name you specified when installing the report.
1. Click Run Report
