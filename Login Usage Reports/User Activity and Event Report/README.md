<h1>User Activity and Event Report</h1>
<h4>Description</h4>
<p>This report gathers User Login Activity and User Events for the same time frame, output to a two sheet Excel report. 

On the first sheet, “Login Activity”, the report builds a row per user, producing login stats for the time frame specified.

On the second sheet, “Event Activity”, the report builds a parent row per user, followed by child rows per “Event” triggered by the user for the same time. 
Events are primarily CRUD activities. (Login events are excluded intentionally on the “Event Activity” sheet, because they are accounted for on the first sheet).

Because “Event Activity” can be extensive, it is beneficial to filter the report by User Name (Full Name) when selecting large time parameters. 
Otherwise, if the report is not filtered by User Name, and a larger time parameter is selected, “Event Activity” can exceed the limitations of Excel - this also depends on how active users are. 
If the Report Runner would like to narrow in on particular “Event Activity” to reduce data returned, reach out to the report team or if you are a CSM or Consultant the [ eventEnumList ] and [ objectTypeEnumList ] can be modified on line 238.
</p>

<h2>Preview Image Sheet 1: "Login Activity</h2>
![LoginActivity png](https://user-images.githubusercontent.com/99203913/210121980-dced9958-6597-4ed0-b7cd-ae4e7d1a6a1f.png)


<h2>Preview Image Sheet 2: "Event Activity</h2>
![EventActivity png](https://user-images.githubusercontent.com/99203913/210121972-151a9908-2421-4f0a-9582-657447dc9d7d.png)


<h1>Installation Instructions</h1>
<ol>
  <li>Go to the Admin section of Jama</li>
  <li>Click the reports tab</li>
  <li>Click add report</li>
  <li>Fill in the Add/Edit Report form as shown below</li>
  <li>Click Save</li>
</ol>
<p>Helpful description to add at install: <em>Check one time parameter and the report will show data from the date the report is run. Outputs a two sheet Excel report with tabs: "Login Activity", "Event Activity". Filter by User Name, considering larger time parameters.</em></p>

![InstallReport png](https://user-images.githubusercontent.com/99203913/210122044-bf1b7c54-5380-4529-9879-7b72d8133387.png)

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
 
 <h1>Report Run Instructions<h1>
 <ol>
  <li>Log into the Organizations Instance</li>
  <li>On the top right nav of project dashboard select "Reports" dropdown</li>
  <li>Select the "User Activity and Event Report"</li>
  <li>Select a time parameter</li>
  <li>If filtering the report by user enter String value- first and last name (not case sensitive)</li>
 </ol>
 ![RunReport png](https://user-images.githubusercontent.com/99203913/210122167-8d57e90c-7183-4417-a27d-7eced223fa83.png)

 
  
