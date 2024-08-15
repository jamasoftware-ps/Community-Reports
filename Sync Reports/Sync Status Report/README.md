# Sync Status Report

## Description 
The Sync Status Report can be exported from your project tree and provides a table output that outlines each exported items associated sync item(s). Each output row provides helpful item data fields such as ID, Global ID, Name, Sync Item ID, Sync Item Project, and resulting Sync Status. Additionally, each exported source and associated sync item provides a direct Jama item hyperlink for quick navigation into your Jama instance. 

The report additionally provides three filtering parameter options to assist in controling your output results. Should you wish to only see either the In Sync or Out of Sync items for your exported source items two boolean checkbox parameters provide this selection. If you are interested in only seeing associated sync items that belong to a particular project you can supply a Project API ID value to the provided string parameter input. A project API ID value can be found in your Jama Admin > Project > Details > API-ID view. 


## Preview

![SyncStatusPreview](https://github.com/user-attachments/assets/3d97f04a-bcef-45ef-96c6-81fdc8bff7aa)


## Installation Configuration

![Screenshot 2024-07-18 at 12 54 46 PM](https://github.com/user-attachments/assets/2355d0ef-bf12-4091-b5a6-2c1a0d4ecd03)


###### Configuration Specifications
<ul>
<li>Report Type: Select Velocity</li>
<li>Report Formats: Select your preference</li>
<li>Report File Name: Upload the velocity file</li>
<li>Organization: select</li>
<li>Context Sensitive: check the box</li>
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
    <td>Only Show In Sync Items</td>
    <td>reportOnlyInSync</td>
  </tr>
  <tr>
    <td>Boolean</td>
    <td>Only Show Out of Sync Items</td>
    <td>reportOnlyOutOfSync</td>
  </tr>
  <tr>
    <td>String</td>
    <td>Sync Items Project ID Filter</td>
    <td>reportProjectIdFilter</td>
  </tr>
</table>


## Running the Report
1. Log into a project
2. Select sync source items in the project tree ( ensure list or reading or document view)
3. Export > View all export options > find 'Sync_Status_Report'
4. Select report output filtering parameter options if using
5. Run 

