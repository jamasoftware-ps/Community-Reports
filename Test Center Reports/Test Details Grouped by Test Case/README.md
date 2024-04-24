# Test Details Grouped by Test Case 
This is a context insensitive test results report that outputs data from the user selected test plan. This report can be output to PDF or Word format with the option to show a data visual Test Plan Summary and Test Group Summary. The visuals for these summaries are different considering PDF or Word format. The time zone for the dates output is UTC. To modify time zone change the TZ identifier string on line 197 of the template.

## Sections of this report: 
######  Test Plan Contents 
The Test Plan description. 
######  Test Plan Summary 
If the user selects the parameter 'Include Test Plan Summary' it outputs a summary of the Test Run statuses for the Test Plan.  
######  Test Group Summary 
If the user selects the parameter 'Include Test Group Summary' it outputs a summary of the Test Run statuses for each Test Group's test cases. 
######  Detailed Results
Each Test Run result across all Test Cycles grouped by Test Case. Select 'Include Test Run Test Steps' to output steps for each Test Run.

## Preview 

##### 'Include Test Run Test Steps'

![detailedResultsCase_steps](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/320f31a0-d6ad-41d2-9fa2-344e2ec30f32)


##### Default without Test Run Test Steps 

![resultsNoSteps](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/f81f00b9-c3c1-48c6-ab7f-ad913aee6f68)

### Summary Charts Export to PDF 

##### Test Plan Summary 

![testPlanSummary_1](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/f4362e29-12ba-4843-a9d5-dbc2ed42ac5e)


##### Test Group Summary

![testGroupSummary_1](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/d9334f97-e876-4cec-863c-934c4515b5ee)

### Summary Tables Export to WORD

##### Test Plan Summary 

![testPlanSummary_2](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/a8461561-52f6-4b1f-bc8c-7933c3048618)

##### Test Group Summary

![testGroupSummary_2](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/7aaa34a2-cbd3-427a-9251-1ed4a30ba3d5)


# Installation Configuration 

![caseConfiguration](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/eda18b51-b265-430a-a067-dbfead304f3a)


<ul> 
  <li>Report Type: Select Velocity</li>
  <li>Report Formats: Select PDF and/or Word</li>
  <ul>
    <li>Note for export to .pdf or .doc- this template is not configured to have a ToF or ToT</li>
    <li>If export to .pdf select Include Table of ... 'Contents'</li>
  </ul>
  <li>Report File Name: Upload the velocity file</li>
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
    <td>Boolean</td>
    <td>Include Test Group Summary</td>
    <td>testGroupSummary</td>
  </tr>
  <tr>
    <td>Boolean</td>
    <td>Include Test Plan Summary</td>
    <td>testPlanSummary</td>
  </tr>
  <tr>
    <td>Boolean</td>
    <td>Include Test Run Test Steps</td>
    <td>includeTestRunSteps</td>
  </tr>
   <tr>
    <td>Test Plan</td>
    <td>Test Plan</td>
    <td>reportTestPlanId</td>
  </tr>
</table>

# Report Run Instructions 
<ol>
  <li>Log into a project with the Test Plan to export</li>
  <li>Go to 'Reports' in upper right navigation > Run Report</li>
  <li>Find 'Test_Details_Grouped_by_Test_Case' > Select parameters > Run </li>
</ol>
