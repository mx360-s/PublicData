# The Data Dictionary #

>This is a *unified set of data* and is intended to be the primary resource for providing and analyzing demographic and situational information.

It is built on some gems:

 - Table of variables
 - Table of calculated variables
 - Form Title, Milestone Form
 - Form metadata:
	- Variable Name: Indicates the variable number or name assigned to each variable in the data collection.
	- Variable column position: Indicates the initial position and width of the variable
	- Variable Name: Indicates a brief description of the variable (up to 40 characters) that can be used to identify the variable.
	- Missing Data Code: Indicates the missing data values ​​and labels. Some analysis programs require certain types of data to be excluded from the analysis and designated as "Missing Data". Users can use these "Missing Information" codes as needed.
	- Code Value: Indicates the code values ​​that appear in the variable data.
	- Value label: Indicates the text definitions of the codes.
 - Directory of datasets
 - Datasets

The source tables are built in excel (yes excel) and presented in simple XML over XSLT and XSD. This is a bit of order, not a big deal. I am on the shoulders of giants:

 - https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/GMBGYH
 - https://www.datafiles.samhsa.gov/get-help/codebooks/what-codebook
 - https://dss.princeton.edu/online_help/analysis/codebook.htm
