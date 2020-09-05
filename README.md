# ExternalWorks
 <!-- /* Font Definitions */ @font-face {font-family:"Cambria Math"; panose-1:2 4 5 3 5 4 6 3 2 4;} @font-face {font-family:Calibri; panose-1:2 15 5 2 2 2 4 3 2 4;} @font-face {font-family:Verdana; panose-1:2 11 6 4 3 5 4 4 2 4;} /* Style Definitions */ p.MsoNormal, li.MsoNormal, div.MsoNormal {margin-top:0in; margin-right:0in; margin-bottom:8.0pt; margin-left:0in; line-height:107%; font-size:11.0pt; font-family:"Calibri",sans-serif;} a:link, span.MsoHyperlink {color:blue; text-decoration:underline;} .MsoChpDefault {font-family:"Calibri",sans-serif;} .MsoPapDefault {margin-bottom:8.0pt; line-height:107%;} @page WordSection1 {size:8.5in 11.0in; margin:1.0in 1.0in 1.0in 1.0in;} div.WordSection1 {page:WordSection1;} -->     **OBJECTIVE**

 Discriminating key regulators of pre and post menopausal ER +ve breast cancer in relation to obesity

 **DATASET**

 <https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE24185>

 [Gene transcription signature of obesity in breast cancer](https://www.ncbi.nlm.nih.gov/pubmed/21750966)

 Total number of Samples: 103

 Considered only ER +ve breast cancer in pre and post-menopausal women

 BMI > 25:: Normal BMI <=25 Obese

 **Distribution of Considered samples**

 ![](method_snapshot_files/image001.png)



 Median Age Overall - 49

 Median Age Post - 57

 Median Age Pre - 42

  **COMPARISON**

 **Post**

 Normal BMI vs OBESE BMI **:** 775 DEGs with FC ≥ ±1.5

 **Pre**

 **Normal BMI vs OBESE BMI :** 486 DEGs with FC ≥ ±1.5

  ![](method_snapshot_files/image002.png)

  Post DEGs : 775 :: 626 Unique Genes

 Pre DEGs : 486 :: 337 Unique Genes

 Common DEGs : 149, where regulation of 87 genes were contradictory in pre and pos conditions



 **Selection Criteria:**

 1. From common DEGs :: Genes which have different regulation in pre and post menopausal data. For example, “IL8” detected as down regulated in Pre and upregulated in post will be considered as a “candidate gene”

 2. Prioritize Post unique DEGs (626 Unique Genes) via network analysis and functional similarity

 3. Prioritize Pre unique DEGs (337 Unique Genes) via network analysis and functional similarity

  **Filtering the genes**

 1. Functional enrichment analysis: Select pathways related to obesity and breast cancer

 2. Filter the genes by tissue specificity: Breast and adipocyte tissue

 3. Compare mutational status with COSMIC database or GWAS

 4. Compare with TCGA or metabric data*

 5. Report the drug-target interactions of finally reported genes
