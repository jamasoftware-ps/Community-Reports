# All Projects Report

## Description 
The All Projects Report is a context insensitive report that provides a Excel output list of all projects present on your Jama Connect instance. When ran the report will generate a Excel table output that provides the Project ID, Key, Name, Hyperlink, Manager, Created Date, and Project Hierarchy Path. The hierarchy path provides insight into which project folder containers each project may be organized into in which projects not contained by folders are listed as top level projects to the instance organization. 

The report additionally provides a boolean parameter that allows you to include inactive projects that may have been deleted and or archived. This will create an additional data column called Active/Inactive that provides the project state with cell coloring designation. 


## Preview



## Installation Configuration




###### Configuration Specifications
<ul>
<li>Report Type: Select Velocity</li>
<li>Report Formats: Select your preference</li>
<li>Report File Name: Upload the velocity file</li>
<li>Organization: select</li>
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
    <td>Include Inactive Projects</td>
    <td>reportIncInactive</td>
  </tr>
</table>


## Running the Report
1. Open your Jama Connect instance
2. Open any project.
3. Using the report drop down menu found on top right of the Jama Connect navigation bar select Reports > Run Report to open the context insensitive reports menu
4. Select the All Projects Report
5. Select report parameter options if using
6. Run 


