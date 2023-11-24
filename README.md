# Influenza Virus Infection Study Data

This repository contains data and analysis code for the study titled "Viral Shedding and Clinical Illness in Naturally Acquired Influenza Virus Infections" published in the _Journal of Infectious Diseases_ in 2010. Link: https://academic.oup.com/jid/article/201/10/1509/992720?login=true
## Overview

In this study, we highlights the importance of understanding viral shedding in influenza infections. we provides valuable insights into the relationship between viral shedding and clinical illness, shedding light on the transmission dynamics and severity of influenza virus infections.

## Data
 
- `home_pcr.csv` contains  information about households followed up and their family members. It includes variables such as household ID (hhID), member ID, and visit information.
- `adherence_m.csv` provides information on adherence to preventive measures.
- `symptomday_d.csv` contains information about symptom onset and duration.

  
## Script

The script is written in R and includes various operations on the data, including defining lab-confirmed infection, defining acute respiratory illness (ARI), and determining ARI onset. The output includes a data frame on the 44 subjects analyzed in the study, including their ARI onset and q_culture results. The vshed_scripts directory has the following structure:

- JID_dataframe.r contains an R script for handling the JID (Journal of Infectious Diseases) dataframe.
- Figure_1.r generates patterns of viral shedding and symptoms and signs in naturally acquired influenza A and B virus infections by day relative to acute respiratory illness (ARI) onset (day 0).
- Figure_2.r shows association between replicating (by median tissue culture infectious dose [TCID50]) and molecular (by reverse-transcription polymerase chain reaction) influenza A viral shedding by day since acute respiratory illness (ARI) onset for children (plus signs) and adults (circles).
- Table_1.r shows the comparison of Characteristics of 59 Secondary Influenza Virus Infections with 76 Excluded Infections.
- WinBUGS.zip includes the code and instruction to reproduce Figure 3.
- Appendix_Figure_1.r creates a plot comparing viral load in nasopharyngeal turbinate swabs (NTS) with quantitative culture.
- Appendix_Figure_2.r creates graphs to analyze the relationship between viral load and body temperature and performs linear regression analysis on the data.
- Appendix_Table_1.r contains an R script to analyze data related to appointment attendance in a study.

## Usage

To use this data and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `script` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Lau LL, Cowling BJ, Fang VJ, Chan KH, Lau EH, Lipsitch M, Cheng CK, Houck PM, Uyeki TM, Peiris JS, Leung GM. Viral shedding and clinical illness in naturally acquired influenza virus infections. J Infect Dis. 2010 May 15;201(10):1509-16. doi: 10.1086/652241. PMID: 20377412; PMCID: PMC3060408.
