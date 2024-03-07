CeRNA Results File Description
1. miRNA_mRNA: Results of miRNA mRNA association analysis
RNA_1-RNA_2.cortest.xls: Table of miRNAs and mRNA targeting this miRNA in all samples
Obtain correlation analysis results;
RNA_1-RNA_2. corr. list: A list of miRNAs with negative correlation between expression levels and targeted mRNA identified in the above results
And its correlation analysis information.
2. miRNA_lncRNA: Results of association analysis between miRNA and lncRNA
Mature. Miranda targets transcript. pairs: Based on the miRNA predicted by miRanda software in all samples and its correlation with
A list of lncRNA IDs with targeted relationships; [For animals]
Mature. psRobot targets transcript. pairs: miRNAs predicted by psRobot software in all samples and their correlation with
A list of lncRNA IDs with targeted relationships; [For Plants]
RNA_1-RNA_2.cortest.xls: Table of miRNAs and lncRNAs with a targeting relationship to this miRNA in all samples
Obtain correlation analysis results;
RNA_1-RNA_2.corr.list: A list of miRNAs with negative correlation in expression levels and targeted lncRNAs identified from the above results
And its correlation analysis information;
3. miRNA_circRNA: Results of association analysis between miRNA and circRNA
RNA_1-RNA_2.cortest.xls: Table of miRNAs and circRNAs with a targeting relationship to this miRNA in all samples
Obtain correlation analysis results;
RNA_1-RNA_2.corr.list: A list of miRNAs with negative correlation in expression levels and targeted circRNAs identified from the above results
And its correlation analysis information;
4. lncRNA_miRNA_mRNA: LncRNA miRNA mRNA Association Network Results
LncRNA_miRNA_mRNA. cor.xls: miRNA, which has a targeting relationship with this miRNA and has a negative correlation with its expression level
MRNA, lncRNAs that have a targeting relationship with the miRNA and have a negative correlation in expression levels, and the correlation analysis results;
LncRNA_miRNA_mRNA. cor. gene. xls: miRNA, which has a targeting relationship with this miRNA and has a negative expression level
The mRNA of Guan, lncRNA with a targeting relationship and a negative correlation in expression level with this miRNA, is correlated at the gene level
Analysis results
LncRNA_miRNA_mRNA. cytosape. txt. top200. txt: miRNA, which has a targeting relationship with this miRNA and is expressed
MRNA or lncRNA with negative horizontal correlation, this file is the top 200 of lncRNA_miRNA_mRNA.cytosape.txt
Line; It is also the input file for network diagram drawing in this folder.
LncRNA miRNA mRNA association network obtained from lncRNA_miRNA_mRNA.cytosape.txt. top200.txt plot
Network diagram (PDF);
LncRNA_miRNA_mRNA. network.png: Utilizing R packet igraph based on
LncRNA miRNA mRNA association network obtained from lncRNA_miRNA_mRNA.cytosape.txt. top200.txt plot
Network Graph (PNG);
LncRNA_miRNA_mRNA. network. txt: miRNA, which has a targeting relationship with the miRNA and has a negative expression level
All ce network results of mRNA or lncRNA related to the target can be directly inputted into Cytoscape software to obtain ce
Network diagram.
LncRNA_miRNA_mRNA.annot.txt: This file is the lncRNA_miRNA_mRNA.network.txt network file
The annotation information can be directly imported into Cytoscape software to classify RNA types of nodes in the CE network.
GOenrich folder: lncRNA_miRNA_mRNA. cor. gene. xls file for all genes (column 5)
GO enrichment results
