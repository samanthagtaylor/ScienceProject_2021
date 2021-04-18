# ScienceProject_2021
First, I downloaded the data from NCBI that contained the location the sample was taken, the date collected, sequence id, the protein, the length, as well as other information [1]. I saved this data as a csv file. I also downloaded the sequences as a fasta file. Because sequencing is not always perfect, I had to clean the data by removing sequences less than 1273 amino acids (Initial Wu han sequence (Control)), as well as, sequences with undistinguishable amino acids by removing sequences containing x. I joined the sequences to the csv file data, so I could work with them together. I also only included data from the 50 U.S. States. I am considering each sample a trial, so I had 6103 trials.  After I cleaned my data, I filtered by date (every 2 months) and counted up the variants with the python code. All my python code is in a GitHub repo, so all my data analysis can be reproduced by anyone. After each filtered date range, I copied the variants into an Excel spreadsheet. To analyze the effect of the number of variants on the fatality rate, I downloaded data from the CDC webpage and put it into the same Excel document as the variants [2]. I then used the formula in Excel to divide total number of deaths by the total cases for each state to get the fatality rate. I finally drew the graphs by state and then combine by the five different regions to draw my conclusions.

[1] https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/virus?SeqType_s=Protein&VirusLineage_ss=SARS-CoV-2,%20taxid:2697049&ProtNames_ss=surface%20glycoprotein

[2] https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36
