# Influenza Virus Infection Study Data

This repository contains data and analysis code for the study titled "Viral Shedding and Clinical Illness in Naturally Acquired Influenza Virus Infections" published on PubMed. Link: https://pubmed.ncbi.nlm.nih.gov/20377412/

## Overview

In this study, we investigated the relationship between viral shedding and clinical illness in individuals with naturally acquired influenza virus infections. We aimed to understand the duration and pattern of viral shedding and its association with the severity of clinical symptoms.

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

To use this data and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `script` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Lau LL, Cowling BJ, Fang VJ, Chan KH, Lau EH, Lipsitch M, Cheng CK, Houck PM, Uyeki TM, Peiris JS, Leung GM. Viral shedding and clinical illness in naturally acquired influenza virus infections. J Infect Dis. 2010 May 15;201(10):1509-16. doi: 10.1086/652241. PMID: 20377412; PMCID: PMC3060408.
