# Review Comments & Signatures 
Export approver signatures and review comments. Before running the report the user enters a review id, e.g. REV-38 to get all comments for the review. If the user would like to get comments up to and including a specific revision version, the user enters the review id and a specific version number, e.g V2.

Note: Currently a comment thread child inherits the revision version of the thread parent - this is a reflection of the current UI in which a user can see the comment thread parent revision version while the thread children do not display a revision version. A comment's revision version is output in the 'Review Version' column of comment tables in this report. There is currently a feature request for each comment to display the review version to which the comment was applied, and not the inherited value of the parent, which would be reflected in Velocity reporting. 

## Report Sections:
###### Approvers & Reviewers
<ul>
<li>Outputs a table for approvers and a status of their progress on the revision (<i>Not Finished, Finished or Needs Work</i>).</li>
<li>Outputs a table for reviewers and a status of their progress on the revision (<i>Not Finished or Finished</i>).</li>
</ul>

###### Approvers Signatures
<ul>
<li>Outputs approver signatures for the latest revision on the review or the user input revision version.</li>
</ul>

###### Review Comment Summary
<ul>
<li>Outputs 'Total Review Comments' count for comments at the review level.</li>
<li>Outputs 'Total Revision Item Comments' count for comments at the revision item level.</li>
</ul>

###### Review Comments
<ul>
<li>Outputs all the comments at the review level.</li>
</ul>

###### Revision Item Comments 
<ul>
<li>Foreach revision item outputs the revision item description and comments. If no comments on the revision item will show "No comments present on revision item”</li>
</ul>


## Preview

![exampleOutputReport1](https://github.com/user-attachments/assets/3fc94225-a116-4180-8ddb-a87dcd41c1bb)

![exampleOutputReport](https://github.com/user-attachments/assets/0d60cdfd-76af-4251-bd13-e733c4afca62)


## Installation Configuration

![configuration](https://github.com/user-attachments/assets/d4412147-aeb0-43cc-962d-0ff3be9b4036)

###### Configuration Specifications
<ul> 
  <li>Report Type: Select Velocity</li>
  <li>Report Formats: Select PDF and/or Word</li>
  <ul>
  <li>*Note for export to .pdf or .doc- this template is not configured to have a ToC, ToF, or ToT</li>
  </ul>
  <li>Report File Name: Upload the velocity file</li>
  <li>Description: <i>Enter a review id, e.g. REV-38 to get all comments for the review. To get comments up to and including a specific revision, enter the REV-id and the version, e.g V2. Revision Item descriptions can be included via the provided Include Descriptions parameter.</i></li>
  <li>Organization: select</li>
  <li>Criteria: see below criteria to configure</li>
  <li>Save</li>
</ul>

<h6>Criteria</h6>
<table>
  <tr>
    <th>Type</th>
    <th>Display</th>
    <th>Name</th>
  </tr>
  <tr>
    <td>String</td>
    <td>Review Id, e.g. REV-id</td>
    <td>reportReviewId</td>
  </tr>
  <tr>
    <td>String</td>
    <td>Revision version, e.g. Vx</td>
    <td>reportRevisionV</td>
  </tr>
  <tr>
    <td>Boolean</td>
    <td>Include Description</td>
    <td>reportDescription</td>
  </tr>
</table>


## Report Run Instructions 
<ol>
  <li>Log into any project</li>
  <li>Go to 'Reports' in upper right navigation > Run Report</li>
  <li>Find 'Review_Comments_&_Signatures'</li>
  <li>Enter the Rev-id string parameter</li>
  <li>If specific revision enter version number Vx string parameter</li>
  <li>Run</li>
</ol>
 
