# Test Details Grouped by Test Cycle 
This is a context insensitive test results report that outputs data from the user selected test plan. This report can output to PDF or Word format with the option to show a data visual Test Plan Summary and Test Cycle Summary. The visuals for these summaries are different considering PDF or Word format. 

## Sections of this report: 
######  Test Plan Contents 
The Test Plan description. 
######  Test Plan Summary 
If the user selects the parameter 'Include Test Plan Summary' it outputs a summary of the Test Run statuses for the Test Plan.  
######  Test Group Summary 
If the user selects the parameter 'Include Test Cycle Summary' it outputs a summary of the Test Run statuses for each Test Cycle. 
######  Detailed Results
Each Test Run result across all Test Cycles grouped by Test Cycle. Select 'Include Test Run Steps' to output steps foreach Test Run.

## Preview 
##### 'Include Test Run Steps'

![testCycleTestRun](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/10028c8f-509a-4d7a-81fd-cea4ee4e1651)

##### Default without Test Run Steps

![defaultTestRunNoSteps2](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/bbf997d7-f097-4588-860c-299dcd1aba35)


### Summary Charts Export to PDF 

##### Test Plan Summary 

![testPlanSummaryPDF](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/ce0a3595-2cd4-48cb-b39a-e0e82308195c)


##### Test Cycle Summary 

![pdfCycleSummary](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/f09b87c0-525e-45e9-95a3-58480349017b)

![cycleStatuses](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/9024925a-1d12-481e-9bad-abc75d72d4c6)


### Summary Tables Export to WORD

##### Test Plan Summary 

![testPlanSummaryWord](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/ad461a48-1689-42eb-93a0-14cf25a379ba)

##### Test Cycle Summary 

![wordCycleSummary2](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/dc04874f-442d-403f-97a8-c9212548b6a2)


# Installation Configuration 

![cycleConfiguration](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/ead565ab-5239-4e75-b740-2e1c30878057)


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
  <li>Log into the project with the test plan to export</li>
  <li>Go to 'Reports' in upper right navigation > Run Report</li>
  <li>Find 'Test_Details_Grouped_by_Test_Cycle' > Select parameters > Run </li>
</ol>
