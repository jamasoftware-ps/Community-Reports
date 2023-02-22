# Baseline to Baseline Diff - Three Column Report

### *Note: The Baseline diff reports work with Connect versions 8.68 or later.*

## Report Summary
The Baseline to Baseline Diff (Three Column) report compares the two baselined versions of the same items, displaying the differences as redlined text in one column. If the user selects Show Finished Text, the actual (unredlined) text will show as well.

## Report Preview Image
![Baseline to Baseline Diff - 3 column](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Baseline%20Reports/Baseline%20to%20Baseline%20Diff%20Report/BaselineToBaselineDiffThreeColPreview.png)


#### Word and HTML reports:
- Report Name: Baseline to Baseline Diff - 3 columns
- Report Type: Velocity
- Report Formats: HTML and/or Word
- Report file to upload: baselineToBaselineDiff_3column.vm
- Criteria:
  - *Type:* **Baseline parameter**, *Display:* **Baseline 1**, *Name:* **report_baseline1**
  - *Type:* **Baseline parameter**, *Display:* **Baseline 2**, *Name:* **report_baseline2**
  - *Type:* **Boolean**, *Display:* **Include Relationships**, *Name:* **includeRelationships**
  - *Type:* **Boolean**, *Display:* **Include Version Comments**, *Name:* **report_showComment**
  - *Type:* **Boolean**, *Display:* **Show Finished Text**, *Name:* **report_showFinText**
  - *Type:* **Boolean**, *Display:* **Exclude Status Field**, *Name:* **report_excludeStatus**

![Report Configuration](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Baseline%20Reports/Baseline%20to%20Baseline%20Diff%20Report/BaselineToBaselineDiffThreeColsConfig.png)
