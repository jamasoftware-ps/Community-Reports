# Test Details Grouped by Test Case 
This is a context insensitive test results report that outputs data from the user selected test plan. This report can be output to PDF or Word format, with the option to show a data visual Test Plan Summary and a Test Group Summary. The visuals for these summaries are different considering PDF or Word format. 

#### Sections of this report: 
######  Test Plan Contents 
The Test Plan description. 
######  Test Plan Summary 
If the user selects the parameter 'Include Test Plan Summary' it outputs a summary of the Test Run statuses for the Test Plan.  
######  Test Group Summary 
If the user selects the parameter 'Include Test Group Summary' it outputs a summary of the Test Run statuses for each Test Group's test cases. 
######  Detailed Results
Each test run result across all cycles grouped by matching test cases.

## Preview 

![wordTestCase](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/7654ac5f-b4bd-480d-9624-19630a04aa97)

### Summary Charts Export to PDF 

##### Test Plan Summary 

![testPlanSummaryPDF](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/9f4dacef-e636-4045-83b7-66a3d5844527)

##### Test Group Summary

![testGroupSummaryPDF2](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/391f2921-7b71-4ed0-a22d-b86b6702c727)

### Summary Tables Export to WORD

##### Test Plan Summary 

![testPlanSummaryWord](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/375018bd-7798-454a-88fe-e3dccfa8105b)

##### Test Group Summary

![wordTestGroup](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/616265ae-45f5-4200-b7f4-d03146f1b37c)

# Installation Configuration 

![caseConfiguration](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/de90672f-67e5-4e79-a730-81802931c79a)

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
    <td>Test Plan</td>
    <td>Test Plan</td>
    <td>reportTestPlanId</td>
  </tr>
</table>

# Report Run Instructions 
<ol>
  <li>Log into a project with the Test Plan to export</li>
  <li>Go to 'Reports' in upper right navigation > Run Report</li>
  <li>Find 'Test_Details_Grouped_by_Test_Case' > Select paramters > Run </li>
</ol>
