# Review Comments & Signatures 
Export approver signatures and review comments. Before running the report the user enters a review id, e.g. REV-38 to get the latest version signatures and all comments for the review. If the user would like to get signatures and comments up to and including a specific revision version, the user enters the review id and a specific version number, e.g V2.

Note: Currently a comment thread child is inheriting the revision version of the thread parent, which is output in the 'Review Version' of the Revision Item Comment table of this report. When the Velocity API method RevisionItemComment.revision.sequenceNumber is updated so that it returns the review version to which the comment was applied, and not the inherited value of the parent, we will remove this note, and the report will automatically reflect that update.

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

![readMeExampleOutput](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/d6f829aa-a9f1-47b6-a403-779ba545a180)


![readMeExampleOutput2](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/8ff9ff1a-03f1-485c-ac4a-e3a7225398d3)


## Installation Configuration

![installationConfiguration](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/b25ec19b-823d-4a95-8635-f4a14f82186c) 
###### Configuration Specifications
<ul> 
  <li>Report Type: Select Velocity</li>
  <li>Report Formats: Select PDF and/or Word</li>
  <ul>
  <li>*Note for export to .pdf or .doc- this template is not configured to have a ToC, ToF, or ToT</li>
  </ul>
  <li>Report File Name: Upload the velocity file</li>
  <li>Description: <i>Enter a review id, e.g. REV-38 to get the latest version signatures and all comments for the review. To get signatures and comments up to and including a specific revision, enter the review id and enter the version number, e.g V2.</i></li>
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
 
