# E484K-epistasis-210910

Data and code used in the master's thesis of Jiabao (Lily) Zhong.

### Data
1. nextstrain_210910.svg.zip: screenshot of NextStrain SARS-CoV-2 subsample phylogenetic tree, downloaded on 09/10/2021 from [https://nextstrain.org/ncov/gisaid/global/all-time]
   -- figure 1
2. nextstrain_timetree_210910.nwk: NextStrain SARS-CoV-2 subsample phylogenetic tree (Newick format, branch length measured in years), downloaded on 09/10/2021 from [https://nextstrain.org/ncov/gisaid/global/all-time]
   -- loaded in E484K_210910.Rmd for analysis
3. nextstrain_210910.tsv: per-sample acknowledgements of NextStrain SARS-CoV-2 subsample, downloaded on 09/10/2021 from [https://nextstrain.org/ncov/gisaid/global/all-time]
   -- used to extract SARS-CoV-2 subsample accession IDs
4. nextstrain_id_210910.tsv: SARS-CoV-2 subsample accession IDs extracted from nextstrain_210910.tsv
   -- used to download SARS-CoV-2 subsample sequences from GISAID
5. nextstrain_210910.fasta.zip: SARS-CoV-2 subsample sequences from GISAID, downloaded on 03/20/2022 from [https://www.gisaid.org/]
   -- used to perform multiple sequence alignment and mutation calling by NextClade
6. nextstrain_patient_meta_210910.tsv: patient metadata of SARS-CoV-2 subsample, downloaded on 03/20/2022 from [https://www.gisaid.org/]
   -- loaded in E484K_210910.Rmd for analysis
7. nextstrain_time_location_210910.tsv: time and location of SARS-CoV-2 subsample, downloaded on 03/20/2022 from [https://www.gisaid.org/]
   -- backup
8. nextstrain_nextclade_aligned_210910.fasta.zip: multiple sequence aligned SARS-CoV-2 subsample, downloaded on 03/20/2022 from [https://clades.nextstrain.org/]
   -- backup
10. nextclade_210910.csv: mutation calling of SARS-CoV-2 subsample sequences by NextClade, downloaded on 03/20/2022 from [https://clades.nextstrain.org/]
   -- loaded in E484K_210910.Rmd for analysis

### Analysis
1. E484K_210910.Rmd: Data analysis were performed using R version 4.0.2 (2020-06-22)
