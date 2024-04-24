# Test Details Grouped by Test Cycle 
This is a context insensitive test results report that outputs data from the user selected test plan. This report can output to PDF or Word format with the option to show a data visual Test Plan Summary and Test Cycle Summary. The visuals for these summaries are different considering PDF or Word format. The time zone for the dates output is UTC. To modify time zone change the TZ identifier string on line 192 of the template.

## Sections of this report: 
######  Test Plan Contents 
The Test Plan description. 
######  Test Plan Summary 
If the user selects the parameter 'Include Test Plan Summary' it outputs a summary of the Test Run statuses for the Test Plan.  
######  Test Group Summary 
If the user selects the parameter 'Include Test Cycle Summary' it outputs a summary of the Test Run statuses for each Test Cycle. 
######  Detailed Results
Each Test Run result across all Test Cycles grouped by Test Cycle. Select 'Include Test Run Test Steps' to output steps for each Test Run.

## Preview 
##### 'Include Test Run Steps'

![resultsStepsCycle](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/c5420020-bfec-47c6-8df9-e632b93f9dc5)


##### Default without Test Run Steps

![resultsNoSteps](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/51569ed0-90cd-4d43-9b12-bcfe58d217f9)


### Summary Charts Export to PDF 

##### Test Plan Summary 

![testPlanSummary_1](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/7339b80e-12be-46a7-b0fd-d4bbf2e0fb92)


##### Test Cycle Summary 

![executionDefectsCyclePDF](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/8638a6f1-46a1-4592-8e8a-02811ab70853)

![statusesCyclesPDF](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/f9579c0d-0291-4925-b5d0-866672acf83c)


### Summary Tables Export to WORD

##### Test Plan Summary 

![testPlanSummary_2](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/3a2e8f0e-22c6-4e6b-962c-8ff0fad0a588)


##### Test Cycle Summary 

![cycleSummaryWord](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/0eb5514b-00c6-4173-8ad0-a7ce4be69470)

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
