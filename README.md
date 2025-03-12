# ICD10_categories
Disease, medicine and procedure categories using ATC and ICD-10 based SKS-codes

Files contain regular expression patterns for each category. In addition, each file may contain:

**Name:** name of category

**Label:** Description of category

**DIAG:** List of ATC/SKS codes

**Regex:** Regular expression string for identifying the ATC/SKS codes

**Weight:** weight of the category if used in a score of disease burden

The files are can be used with the code from the [Danish_LPR_datamanagement_python]([https://pages.github.com/](https://github.com/janbvalentin/Danish_LPR_datamanagement_python)) repository, to categorise individuals in the Danish National Registers. 


## Files:
**proc_regex.xlsx** contains procedure SKS-codes for relevant treatments of inflammatory bowel disease (IBD). Names and labels are in Danish



**atc_regex.xlsx** contains ATC codes for treatment of Astma, Diabetes and IBD.



**diag_regex.xlsx** contains ICD-10 codes for various diseases. Note; for the Danish National Patient registries all ICD-10 codes are coded with a D as prefix, which is included in the regular expressions. Names and labels are in Danish.



**nmi_atc_regex.xlsx** contains ATC codes for the categories of the the Nordic Multimorbidity Index (NMI).



**nmi_diag_regex.xlsx** contains ICD-10 codes for the categories of the the Nordic Multimorbidity Index (NMI). Note; for the Danish National Patient registries all ICD-10 codes are coded with a D as prefix, which is included in the regular expressions.


