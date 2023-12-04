# Viral Shedding in Influenza Virus Infections Study Data

Codes for generating results in the paper "Viral Shedding and Clinical Illness in Naturally Acquired Influenza Virus Infections" published in the Journal of Infectious Diseases in 2010. Link: https://academic.oup.com/jid/article/201/10/1509/992720?login=true

## Overview

In this study, we highlighted the importance of understanding viral shedding in influenza infections and provided valuable insights into the relationship between viral shedding and clinical illness, shedding light on the transmission dynamics and severity of influenza virus infections.

## Data

In the data folder we have provided three datasets:

- `hchar_h.csv`  contains information on the household members who participated in the study, including their age, sex, and vaccination status.

- `adherence_m.csv` contains information on the adherence of the study participants to the recommended influenza prevention measures.

- `clinicdat_h.csv` includes information on the clinical symptoms and outcomes of the study participants, including the dates of symptom onset, laboratory test results, and hospitalization status.
  
## Scripts

The vshed_scripts as the following structure:

- `JID_dataframe.r` creates a dataframe used for further analysis and visualization of the transmission dynamics of respiratory viruses in households.
- `Figure_1.r` generates Figure 1 showing patterns of viral shedding and symptoms and signs in naturally acquired influenza A and B virus infections by day relative to acute respiratory illness (ARI) onset (day 0).
- `Figure_2.r` generates Figure 2 showing association between replicating (by median tissue culture infectious dose [TCID50]) and molecular (by reverse-transcription polymerase chain reaction) influenza A viral shedding by day since ARI onset for children (plus signs) and adults (circles).
- `Table_1.r` shows the comparison of characteristics of 59 secondary influenza virus infections with 76 excluded infections.
- `WinBUGS.zip` includes the code and instruction to reproduce Figure 3, which shows the association between replicating and molecular influenza B viral shedding by day since ARI onset for children (plus signs) and adults (circles). Linear regression lines are plotted where there are ⩾3 points. 
- `Appendix_Figure_1.r` creates Appendix Figure 1 comparing viral load in nasopharyngeal turbinate swabs (NTS) with quantitative culture.
- `Appendix_Figure_2.r` creates Appendix Figure 2 of viral load in NTS against body temperature for subjects infected with Influenza A virus.
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
