# Review Status By Set

## Description 
This report can be exported from any location in the project tree or from a baseline. 
The report groups items by what SET they belong to (If an item is exported that does not belong to a set, it will not be included in the report).
For each item in a SET group, the report checks for it's most recent review. 
If the item has been reviewed, the most recent review data for that item is aggregated with the total review stats for the SET Group.
SET groups are presented in the report in alphabetical order. 

### Table Specification 
| Column Label | Column Value Definition | 
| -------------| ------------------------|
| Path| The component path that contains the Set|
| Set Name | The name of the Set |
| Review Status | See "Review Status Definitions" below |
| Approved Items | See "Item Review Status Definitions" below |
| Partially Approved Items | See "Item Review Status Definitions" below | 
| Rejected Items | See "Item Review Status Definitions" below |
| Not Reviewed Items |  See "Item Review Status Definitions" below |
| Reviews | A row per review found in the SET |
| Review Moderators | If there is a moderator/s their name/s will show per review row |
| Review Start Date | Start date of review per review row |
| Review End Date | End date of review per review row |

### Report Definitions 
#### Item Review Status Definition 
| Status | Definition | 
| -------------| ------------------------|
| Approved| Current item version approved by all approvers in most recent review|
| Partially Approved | Current item version approved by some approvers in most recent review with no rejections |
| Rejected | Current item version rejected by any approver in most recent review |
| Not Reviewed | Current item version not approved or rejected by any approver in any review |

#### Review Status Definition 
| Status | Definition | 
| -------------| ------------------------|
| Not Reviewed| No items in the set have received feedback in a review|
| Partially Reviewed | Items in the set have received feedback in a review, but not all are approved |
| Approved | All items in the set have been approved by all approvers |

## Preview Images 

![ExampleReviewStatusBySet](https://user-images.githubusercontent.com/99203913/227651917-000481bf-5ae2-4f73-99fa-5b6615144bac.png)


![ReviewStatusBySet2](https://user-images.githubusercontent.com/99203913/227651930-aff68a34-0a02-47d4-b814-5cac50c5dd10.png)

## Installation Instructions 
1. Go to the Admin seciton of Jama 
2. Click the Reports Tab
3. Click Add Report 
4. Fill in the Add/Edit Report form as shown below
5. Click Save

![Screenshot (2491)](https://user-images.githubusercontent.com/99203913/227652242-dd1b24b4-fcd5-4a00-a726-47889c6a854a.png)

### NOTES 
* Your organization field will be a different value
* Rename the report anything you like

## Running the Report 
1. Go to your Project Tree and select any location or go to your Baseline Module and select a Baseline
2. Click Export 
3. Select the Report you just installed 
4. Click Run Report 
