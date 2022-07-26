# Baseline to Current Diff - One Column

### *Note: The Baseline diff reports work with Connect versions 8.68 or later.*

## Report Summary
The Baseline to Current Diff report compares a baselined versions and the current version of the same items, displaying the differences as redlined text in one column.

## Report Preview Image
![Baseline to Current Diff - 1 column](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Baseline%20Reports/Baseline%20Diff%20Reports/One%20Column%20Baseline%20Diff%20Reports%20-with%20pdf%20option/Baseline%20Diff%20One%20Column/BaselineToCurrentDiffOneColPreview.png)

### Installation Instructions

#### Word and HTML reports:
- Report Name: Baseline To Current Diff One Column
- Report Type: Velocity
- Report Formats: HTML and/or Word
- Report file to upload: baselineToCurrentDiff.vm
- Criteria:
  - *Type:* **Baseline parameter**, *Display:* **Baseline**, *Name:* **report_baseline**
  - *Type:* **Boolean**, *Display:* **Include Relationships**, *Name:* **includeRelationships**
  - *Type:* **Boolean**, *Display:* **Include Version Comments**, *Name:* **report_showComment**

![Baseline to Current Diff - 1 column](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Baseline%20Reports/Baseline%20Diff%20Reports/One%20Column%20Baseline%20Diff%20Reports%20-with%20pdf%20option/Baseline%20Diff%20One%20Column/BaselineToCurrentDiffOneColConfig.png)


#### PDF reports:
- Report Name: Baseline To Current Diff One Column - PDF
- Report Type: Velocity
- Report Formats: PDF
- Report file to upload: baselineToCurrentDiff-PDF.vm
- Criteria:
    - *Type:* **Baseline parameter**, *Display:* **Baseline**, *Name:* **report_baseline**
    - *Type:* **Boolean**, *Display:* **Include Relationships**, *Name:* **includeRelationships**
    - *Type:* **Boolean**, *Display:* **Include Version Comments**, *Name:* **report_showComment**
