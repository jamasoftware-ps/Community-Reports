# User List Report 

The default report lists the active users of the organization and for each user their Username, Full Name, Email, Groups, and License Type. If 'Include Deactivated Users' the report will include any deactivated user if the user was deactivated within 6 months prior to the report being run and if the user is still in a deactivated state with the addition of an 'Active/Deactivated' column.

*If the user has logged in within 6 months prior to the report being run it will show license data for the user. If the user has not logged in within the last 6 months then it will show 'No license usage last 6 months'


### Preview 

Example Default (Active Users)

![defaultActiveUsers](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/6a7055cb-b597-495c-bd88-5332b4102ecc)


Example Include Deactivated Users 

![includeDeactivatedUsers](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/1f4c38d6-8c72-4343-98fa-bc16add61788)

# Installation Instructions 

![installationConfiguration](https://github.com/jamasoftware-ps/Community-Reports/assets/99203913/619c277c-8f0f-4c84-af97-60a9b4e666bd)

<ul> 
  <li>Report Type: Select Velocity</li>
  <li>Report Formats: Select your preferred format</li>
  <li>Report File Name: Upload the 'User_List.vm' file</li>
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
    <td>Include Deactivated Users</td>
    <td>reportDeactivated</td>
  </tr>
</table>

# Report Run Instructions 
<ol>
  <li>Log into any project</li>
  <li>Go to 'Reports' in upper right navigation > Run Report</li>
  <li>Find 'User_List_Report' > Run </li>
</ol>

