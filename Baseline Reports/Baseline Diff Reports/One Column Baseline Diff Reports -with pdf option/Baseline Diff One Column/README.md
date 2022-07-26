# Baseline to Baseline Diff - One Column

### *Note: The Baseline diff reports work with Connect versions 8.68 or later.*

## Report Summary
The Baseline to Baseline Diff report compares the two baselined versions of the same items, displaying the differences as redlined text in one column.

## Report Preview Image
![Baseline to Baseline Diff - 1 column](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Baseline%20Reports/Baseline%20Diff%20Reports/One%20Column%20Baseline%20Diff%20Reports%20-with%20pdf%20option/Baseline%20Diff%20One%20Column/BaselineToBaselineDiffOneColPreview.png)

### Installation Instructions

#### Word and HTML reports:
- Report Name: Baseline Diff One Column
- Report Type: Velocity
- Report Formats: HTML and/or Word
- Report file to upload: baselineDiff.vm
- Criteria:
  - *Type:* **Baseline parameter**, *Display:* **Baseline 1**, *Name:* **report_baseline1**
  - *Type:* **Baseline parameter**, *Display:* **Baseline 2**, *Name:* **report_baseline2**
  - *Type:* **Boolean**, *Display:* **Include Relationships**, *Name:* **includeRelationships**
  - *Type:* **Boolean**, *Display:* **Include Version Comments**, *Name:* **report_showComment**

![Baseline to Baseline Diff - 1 column](https://github.com/jamasoftware-ps/Community-Reports/blob/master/Baseline%20Reports/Baseline%20Diff%20Reports/One%20Column%20Baseline%20Diff%20Reports%20-with%20pdf%20option/Baseline%20Diff%20One%20Column/BaselineToBaselineDiffOneColConfig.png)


#### PDF reports:
- Report Name: Baseline Diff One Column - PDF
- Report Type: Velocity
- Report Formats: PDF
- Report file to upload: baselineDiff-PDF.vm
- Criteria:
    - *Type:* **Baseline parameter**, *Display:* **Baseline 1**, *Name:* **report_baseline1**
    - *Type:* **Baseline parameter**, *Display:* **Baseline 2**, *Name:* **report_baseline2**
    - *Type:* **Boolean**, *Display:* **Include Relationships**, *Name:* **includeRelationships**
    - *Type:* **Boolean**, *Display:* **Include Version Comments**, *Name:* **report_showComment**
