# All Projects Report

## Description 
The All Projects Report is a context insensitive report that provides a Excel output list of all projects present on your Jama Connect instance. When ran the report will generate a Excel table output that provides the Project ID, Key, Name, Hyperlink, Manager, Created Date, and Project Hierarchy Path. The hierarchy path provides insight into which project folder containers each project may be organized into in which projects not contained by folders are listed as top level projects to the instance organization. 

The report additionally provides a boolean parameter that allows you to include inactive projects that may have been deleted and or archived. This will create an additional data column called Active/Inactive that provides the project state with cell coloring designation. 


## Preview

![Screenshot 2024-07-18 at 3 32 57 PM](https://github.com/user-attachments/assets/997b59f7-2824-4abf-ac28-a25cf3c2b85f)


## Installation Configuration

![Screenshot 2024-08-01 at 10 02 38 AM](https://github.com/user-attachments/assets/6d721fbe-fbc0-4f4e-b3a5-4d52a9fa6128)


### Project Permissions
In the event that you want the reports returned data limited by user permissions then please ensure you have the following option set in the configuration installation menu. This will allow the report to only retrieve project data from projects the current user running the report has access too, otherwise you can use the other option to allow all project data be retrieved reguardless of the user running the report.

![Screenshot 2024-08-05 at 2 50 39 PM](https://github.com/user-attachments/assets/c5f271c8-0d7f-4883-9c24-5c85406688b2)


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

