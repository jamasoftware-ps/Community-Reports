# Sync Comparison Reports 

## Report Summary

This report is used to compare two items or projects on the Jama instance in order to determine Sync comparison results for a collection of generic fields. This report allows users to gather sync results from full projects, same or cross project containers, and or same or cross project single items. 

The report will display each item based on the selected Source location to its corresponding Sync Target item showing a collection of generic data fields followed by the items Sync Results. Alongside the inclusion of missing items between the selected source and target locations from both side for additional coverage of data.  

### Report Data Fields

* Default Fields
    * Product ID
    * Project Name
    * Global ID
    * Header Value
    * Name
    * Description (in plain text)
    * Status
    * Tags
* Optional Fields
    * Upstream and Downstream Related Items
    * Attachments

### Sync Results Details

The Sync Results section begins with column 'Jama Instance Sync Status' which is Sync Status value stored on the Jama instance between the source and target item. This value is calculated and determined by specifically selected fields on our Jama instance. 

This is then followed by the 'Report Field Comparison Sync Status' column that is determined by the overall sync results from each successive sync result per included field column. These following sync result columns are included for additional coverage of field data comparison results between the source and target items but may not contribute to your Jama instances defined Sync Status value.  


## Preview Image

![PreviewImage1](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/preview1.png)

![PreviewImage2](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/preview2.png)


## Project Level Sync Comparison Instructions

1. Determine your Sync Target Project ID by either finding it in the Admin view or the project address bar URL.
    * ![ProjectIdExtraction1](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/ProjectIDExtraction1of3.png)
    * ![ProjectIdExtraction2](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/ProjectIDExtraction2of3.png)
    * ![ProjectIdExtraction3](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/ProjectIDExtraction3of3.png)
2. Open the project level list view.
    * ![ProjectLevelListView](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/ProjectLevelListView.png)
3. Open the context sensitive reports menu from the *Export* button in the list view screen.
4. Select the report name you specified when installing the report.
5. Ensure that the *Project Sync Comparison* parameter is checked. 
6. Supply your Sync Target Project ID in the *Cross Project* string parameter.
7. Select any other report parameters you want applied.
8. Select run report.


## Same Project Container or Single Item Sync Comparison Instructions

1. Determine the container item and or single item you wish to export as your *Source* sync export location.
2. View the synced items to your selected *Source* sync export location using the following "View Synced Items" option.
    * ![CrossProjectIDExtract1](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/CrossProjectIDExtract1.png)
3. Open the context sensitive reports menu from the *Export* button in the list view screen.
4. Select the report name you specified when installing the report.
5. Select your boolean parameter options.
6. Select the *Same Project* location parameter option and select your *Target* sync comparision item from the list of synced items in step 2. 
7. Ensure the *Cross Project* string parameter is empty.
8. Select run report.


## Cross Project Container or Single Item Sync Sync Comparison  Instructions

1. Determine the container item and or single item you wish to export as your *Source* sync export location.
2. Determine your *Target* sync comparison item API ID using the following steps below.
    * Open synced items menu from your *Source* sync export location.
    * ![CrossProjectIDExtract1](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/CrossProjectIDExtract1.png)
    * Select the "Compare" option for your desired *Target* sync comparison item.
    * ![CrossProjectIDExtract2](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/CrossProjectIDExtract2.png)
    * Select the "Configure View" option in the top right of this menu.
    * ![CrossProjectIDExtract3](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/CrossProjectIDExtract3.png)
    * Move the "API ID" field to the "Visable Fields" box.
    * ![CrossProjectIDExtract4](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/CrossProjectIDExtract4.png)
    * View the API ID of the equivalent synced item container to the exported Source item and use said API ID to input into the “Cross Project” String parameter. 
    * ![CrossProjectIDExtract5](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/CrossProjectIDExtract5.png)
3. Open the context sensitive reports menu from the *Export* button in the list view screen.
4. Select the report name you specified when installing the report.
5. Select your boolean parameter options.
6. Input your determined *Target* sync comparision API ID from step 2 into the *Cross Project* string parameter.
7. Ensure the *Same Project* location parameter is empty.
8. Select run report.


## Report Parameter Error Handling
This report employs error handling in the following cases in which the generate report will display a error message that may include additional information for proper parameter inputs.

1. You are exporting from the project level without the *Project Sync Comparison* parameter is checked.
2. You have supplied a invalid Project ID as your Sync Target in the Cross Project String parameter when exporting a project level sync report with the *Project Sync Comparison* parameter checked.
3. You have supplied both the Same Project Location parameter or the Cross Project String parameter.
4. You have not supplied a Sync Target location using either the Same Project Location parameter or the Cross Project String parameter.
5. You have supplied a invalid Same Project Sync Target item that is not a sync item to your selected Source location.
6. You have supplied a invalid Cross Project API ID that is not a sync item to your selected Source location.
7. Your selected Source Location does not have any synced items associated with it.


## Installation Instructions
1. Go to the Admin section of Jama.
2. Click the Reports tab.
3. Click Add Report.
4. Add *Sync Comparison Report.vm* from this repository folder.
5. Fill in the Add/Edit Report form as shown below.
6. Ensure that no typos, leading, or trailing spaces are present in the *Name* field for the reports installation criteria.
7. Click Save.

![Config1](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Sync%20Reports/Sync%20Comparison%20Report/config1.png)


### Report Criteria
Ensure that no typos, leading, or trailing spaces are present in the *Name* field for the reports installation criteria.

| Type          | Display                               | Name                       |
| ------------- | ------------------------------------- | -------------------------- |
| Location      | Same Project Sync Target              | report1SPTargetId          |
| String        | Cross Project Sync Target API ID      | report2CPTargetId          |
| Boolean       | Project Sync Comparison               | report3Project             |
| Boolean       | Include Relationships                 | report4IncludeRels         |
| Boolean       | Include Attachments                   | report5IncludeAttachments  |
| Boolean       | Include Only Items With Differences   | report6OnlyDiffItems       |

