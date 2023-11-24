# Influenza Virus Infection Study Data

Codes for generating results in the paper "Viral Shedding and Clinical Illness in Naturally Acquired Influenza Virus Infections" published in the Journal of Infectious Diseases in 2010. Link: https://academic.oup.com/jid/article/201/10/1509/992720?login=true
## Overview

In this study, we highlights the importance of understanding viral shedding in influenza infections and provides valuable insights into the relationship between viral shedding and clinical illness, shedding light on the transmission dynamics and severity of influenza virus infections.

## Data
In the data folder we have provided information on demographic characteristics (age, sex, race/ethnicity), clinical symptoms (fever, cough, sore throat, etc.), laboratory results (viral shedding patterns, virus type/subtype), and other relevant variables. 
  
## Script

The vshed_scripts as the following structure:

- `JID_dataframe.r` creates a dataframe 'plotdata' used for further analysis and visualization of the transmission dynamics of respiratory viruses in households.
- `Figure_1.r` generates patterns of viral shedding and symptoms and signs in naturally acquired influenza A and B virus infections by day relative to acute respiratory illness (ARI) onset (day 0).
- `Figure_2.r` shows association between replicating (by median tissue culture infectious dose [TCID50]) and molecular (by reverse-transcription polymerase chain reaction) influenza A viral shedding by day since acute respiratory illness (ARI) onset for children (plus signs) and adults (circles).
- `Table_1.r` shows the comparison of characteristics of 59 secondary influenza virus infections with 76 excluded infections.
- `WinBUGS.zip` includes the code and instruction to reproduce Figure 3.
- `Appendix_Figure_1.r` creates a plot comparing viral load in nasopharyngeal turbinate swabs (NTS) with quantitative culture.
- `Appendix_Figure_2.r` creates graphs to analyze the relationship between viral load and body temperature and performs linear regression analysis on the data.
- `Appendix_Table_1.r` contains an R script to analyze data related to appointment attendance in a study.

## Usage

To use this data and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `script` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Lau LL, Cowling BJ, Fang VJ, Chan KH, Lau EH, Lipsitch M, Cheng CK, Houck PM, Uyeki TM, Peiris JS, Leung GM. Viral shedding and clinical illness in naturally acquired influenza virus infections. J Infect Dis. 2010 May 15;201(10):1509-16. doi: 10.1086/652241. PMID: 20377412; PMCID: PMC3060408.
