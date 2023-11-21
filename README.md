# Influenza Virus Infection Study Data

This repository contains the data and script used in a study on viral shedding and clinical illness in naturally acquired influenza virus infections. 
https://pubmed.ncbi.nlm.nih.gov/20377412/

## Data

The data used in this study is located in the `data` directory. It includes several CSV files that contain information on clinic visits, home visits, symptom scores, and demographic information. 

## Script

The script used to process and analyze the data is located in the `script` directory. The script is written in R and includes various operations on the data, including defining lab-confirmed infection, defining acute respiratory illness (ARI), and determining ARI onset. The output includes a data frame on the 44 subjects analyzed in the study, including their ARI onset and q_culture results. The vshed_scripts directory has the following structure:

Appendix_Figure_1.r: This file contains an R script for generating Appendix Figure 1.
Appendix_Figure_2.r: This file contains an R script for generating Appendix Figure 2.
Appendix_Table_1.r: This file contains an R script for generating Appendix Table 1.
Figure_1.r: This file contains an R script for generating Figure 1.
Figure_2.r: This file contains an R script for generating Figure 2.
JID_dataframe.r: This file contains an R script for handling the JID (Journal of Infectious Diseases) dataframe.
Table_1.r: This file contains an R script for generating Table 1.
WinBUGS.zip: This file is a compressed archive containing WinBUGS software.

## Usage

To use this data and script, clone the repository to your local machine and open the R script in RStudio or another R environment. Run the script to reproduce the data used in the study and analyze it as desired.

## Credits

This data and script were originally created by Lincoln Lau and Vicky Fang.
