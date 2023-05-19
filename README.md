## Synthetic Hospital Discharge Data Project (synthetic-database-project)


### Summary
Our project leverages [Synthea<sup>TM</sup>](https://synthetichealth.github.io/synthea/), an open-source tool developed by the MITRE Corporation, to create synthetic hospital discharge data. Synthea<sup>TM</sup> uses research-based models to generate rich medical histories for synthetic patients.  We extract the hospital visits and create datasets that match the format of administrative data available to healthcare organizations. This synthetic data allows students and researchers to explore patient records without privacy concerns and develop analyses for hospitals to run on their own real data. Our goal is to make it easier for hospitals, public health officials, and researchers to collaborate and gain insights from administrative hospital data, while keeping patient information private.

### Status
**Version 1**
- Project Timeline: Dec 2022 - Feb 2023
- Team Members: Riley Kwong (@rileeki), Ann Epstein (@aepstein27), Lisa Snortheim (@lisasnortheim), Stefanie Eddy
- v1 of the database is in progress.  This is the first iteration and is really just a proof of concept.  The overall format is there, but many of the fields are left blank.

**Version 2**
- Project Timeline: TBD
- Team Members: TBD
- v2 of the database will flesh out more of the fields that are still empty in v1. The specific updates in v2 are TBD.

### Sample Data
Explore our synthetic hospital discharge data with our downloadable dataset. This dataset contains synthetic patient records in the format that California hospitals use to submit abstracted patient records to the California Department of Health Care Access and Information ([HCAI](https://hcai.ca.gov/data-and-reports/submit-data/patient-data/inpatient-reporting/
)).  
- **Download the dataset [here](data/sample_data.csv).**
- **Current Specs [here](https://hcai.ca.gov/wp-content/uploads/2022/12/IP-format-and-file-specs-jan-2023.pdf).**

### Summary Statistic Workbook
The Summary Statistic Workbook provides an overview of the synthetic hospital discharge data generated by our project. It includes aggregate statistics on patient demographics and fill rates for each field. **The workbook is available for download in Excel format [here](data/summary_workbook.xlsx).** (Coming soon!)

### General Information
- Want to learn more about the project's scope and objectives? Check out the [project charter](documentation/PROJECT_CHARTER.md).
- Want to run the program to create your own database? The [production guide](documentation/PRODUCTION_GUIDE.md) is coming soon...
- Ready to contribute? The [developer guide](documentation/DEVELOPER_GUIDE.md) is coming soon, too!
- Have questions or feedback? Join the discussion on our [GitHub Discussions](https://github.com/rileeki-org/synthetic-database-project/discussions) page.  Or, you can use the [GitHub issues page](https://github.com/rileeki-org/synthetic-database-project/issues) to report bugs and request new features.
- Looking for internal project management documents? Those are stored in [this Google Drive folder](https://drive.google.com/drive/folders/1W4jLmDP6Cl9c2Ocqv08kpu6Y8ToMK7Hy).

### Additional Resources
- Project management: https://github.com/orgs/rileeki-org/projects/1
- Synthea<sup>TM</sup>: https://synthetichealth.github.io/synthea/
- Wiki: https://github.com/rileeki-org/synthetic-database-project/wiki
- Slack channel (permissions required): [synthetic_discharges](https://rileeki.slack.com/archives/C04DCD1PYJE)
- AWS (permissions required): https://rileeki.signin.aws.amazon.com/console
- Note: .jar file is required in folder, but too large to add to our free GitHub account: https://github.com/synthetichealth/synthea/wiki/Basic-Setup-and-Running


