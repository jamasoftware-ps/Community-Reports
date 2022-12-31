<h1>User Activity and Event Report</h1>
<h4>Description</h4>
<p>This report gathers User Login Activity and User Events for the same time frame, output to a two sheet Excel report. 

On the first sheet, “Login Activity”, the report builds a row per user, producing login stats for the time frame specified.

On the second sheet, “Event Activity”, the report builds a parent row per user, followed by child rows per “Event” triggered by the user for the same time. 
Events are primarily CRUD activities. (Login events are excluded intentionally on the “Event Activity” sheet, because they are accounted for on the first sheet).

Because “Event Activity” can be extensive, it is beneficial to filter the report by User Name (Full Name) when selecting large time parameters. 
Otherwise, if the report is not filtered by User Name, and the larger time parameters are selected, “Event Activity” can exceed the limitations of Excel - this also depends on how active users are. 
If the Report Runner would like to narrow in on particular “Event Activity” to reduce data returned, reach out to the report team or if you are a CSM or Consultant the [ eventEnumList ] and [ objectTypeEnumList ] can be modified on line 238.
</p>

<h4>Preview Image Sheet 1 "Login Activity</h4>
![Screenshot (1865)](https://user-images.githubusercontent.com/99203913/210119493-ecb1d685-c2b7-4f0b-855e-3a7f12fde750.png)

<h4>Preview Image Sheet 2 "Event Activity</h4>
![Screenshot (1867)](https://user-images.githubusercontent.com/99203913/210119503-2a88c06f-3d5e-4dda-9cdb-7bcd2639cb56.png)

<h4>Installation Instructions</h4>
<ul>
  <li>Go to the Admin section of Jama</li>
  <li>Click the reports tab</li>
  <li>Click add report</li>
  <li>Fill in the Add/Edit Report form as shown below</li>
  <li>Click Save</li>
</ul>
<p>Helpful description to add at install: <em>Check one time parameter and the report will pull data for the selected amount of time from the the date the report is run. Outputs a two sheet Excel report with tabs: "Login Activity", "Event Activity"</em></p>
![Screenshot (1864)](https://user-images.githubusercontent.com/99203913/210119576-5bbb96bb-3a3a-4683-af53-5a434f3973dc.png)
<p>Report parameters:</p>
<ul>
  <li>Boolean, One Week, reportA_oneWeek</li>
  <li>Boolean, Two Weeks, reportB_twoWeeks</li>
  <li>Boolean, One Month, reportC_oneMonth</li>
  <li>Boolean, Three Months, reportD_threeMonths</li>
  <li>Boolean, Six Months, reportE_sixMonths</li>
  <li>Boolean, One Year, reportF_oneYear</li>
  <li>String Parameter, User Filter (Full Name), reportG_userFilter</li>
 </ul>
  
  
  
