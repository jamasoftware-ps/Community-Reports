# Test Details Grouped by Test Cycle 
This is a context insensitive test results report that outputs data from the user selected test plan. This report can be output to PDF or Word format with the option to show a data visual Test Plan Summary and a Test Cycle Summary. The visuals for these summaries are different considering PDF or Word format. 

## Sections of this report: 
######  Test Plan Contents 
The Test Plan description. 
######  Test Plan Summary 
If the user selects the parameter 'Include Test Plan Summary' it outputs a summary of the Test Run statuses for the Test Plan.  
######  Test Group Summary 
If the user selects the parameter 'Include Test Cycle Summary' it outputs a summary of the Test Run statuses for each Test Cycle's test runs. 
######  Detailed Results
Each test run result across all cycles grouped by test cycle.

## Preview 

![cycleTestRun](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/0cd9db89-fc27-4634-a7d2-029c228a4e68)

### Summary Charts Export to PDF 

##### Test Plan Summary 

![testPlanSummaryPDF](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/5e89e7a9-249d-46ea-87a0-133cb83d4bef)

##### Test Cycle Summary 

![cycleExecutionDefects](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/6e0e66a5-5f27-41b4-aa7c-b96178928cd7)

![cycleTestRunStatuses](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/8a42fdaa-97a1-4ac6-9c92-827c09826328)

### Summary Tables Export to WORD

##### Test Plan Summary 

![testPlanSummaryWord](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/fbc042ca-c773-43f4-b422-4630e9398fbc)

##### Test Cycle Summary 

![wordCycleSummary2](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/3ed04d15-9992-456a-811c-d9d16e1b8a60)



# Installation Configuration 

![cycleConfiguration](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/3068ed94-be6f-43a4-9e2f-e8124bf8c7f6)

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
    <td>Include Test Cycle Summary</td>
    <td>testCycleSummary</td>
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
  <li>Log into the project with the test plan to export</li>
  <li>Go to 'Reports' in upper right navigation > Run Report</li>
  <li>Find 'Test_Details_Grouped_by_Test_Cycle' > Select parameters > Run </li>
</ol>
