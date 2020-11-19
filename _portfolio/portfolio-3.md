---
title: "A Look at State Medicaid and Opioid Oversoses in the Midwest"
excerpt: "Analysis conducted in R Programming"
collection: portfolio
---

The Situation 

Millions of Americans suffer from unmanaged pain and are often prescribed opioids to treat their conditions. However, the dangers of prescription misuse, opioid use disorder, and overdose have been a growing problem throughout the United States for decades. We will analyze the number of opioids, synthetic opioids, and methadone overdose deaths in 2018 to find out which midwestern states have the highest (lowest) number of deaths due to opioids overdose.  In addition, we hope to further examine the state with the largest number of opioid related deaths, discovering how funding and Medicaid expenses contribute (or attempt to curb) to the growing epidemic.  

 Source Data 

The number of drug overdose deaths data is publicly available from Center for Disease Control and Prevention website (https://www.cdc.gov/nchs/nvss/vsrr/drug-overdose-data.htm), in the form of one Excel spreadsheet. This spreadsheet includes basic variables such as state, year, month, drug name, the actual number of deaths, and the predicted number of deaths. Other variables that we are not interested in were eliminated from the datasets. We read this “csv” file into data frames, cleaned, and extracted relevant data for analysis. To analyze state funding, we extracted data from (http://statehealthcompare.shadac.org/Data). This information enabled us to draw on financial statistics between the Midwestern states.  Similar to the data on drug overdose deaths, the data on Medicaid funding was loaded into R as a “csv” file and merged using a for loop.   Additionally, Medicaid prescription drug claims data was used to analyze Medicaid’s role (or lack thereof) in the opioid crisis (https://www.medicaid.gov/medicaid/prescription-drugs/state-drug-utilization-data/index.html).  
