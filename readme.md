# Preparation

***
Your computer should contain the following environments and dependencies.
### Environments
The following requirements are the conditions when the author run the code successfully.

```angular2html
JDK >= 1.8   
Python >= 3.7
```

### Data  
#### NodeDiversity
This folder contains the following files.  

+ PPI_NodeDiversity.txt  
  The content of this is node diversity of Protein-protein interaction(PPI) network.
+ SCN_NodeDiversity.txt  
  The content of this is node diversity of Symptoms Clinical Network(SCN).
+ NodeDiversity.java  
  Program for calculating node diversity.  
  The above two txt files are generated by this code.  
+ NodeDiversity.jar  
  Encapsulation of the above java code.
#### ppi  
This folder contains the following files.  
+ Protein-protein interaction network.csv  
The file is the PPI network structure.  
+ gene_div_deg.csv  
The file is loaded with the diversity and degree of genes in the PPI network, which is an intermediate result file.
#### SCN  
This folder contains the following folders.
+ Input  
This folder contains the input files needed for running SCN.py, mainly Source data for construct symptom clinical association network, the corresponding data of SCN and CUI, and the corresponding data of CUI and gene.
+ tmp  
This folder contains the intermediate results of SCN.py running.
+ Output  
  This folder stores the files output by the code. Mainly the results of molecular network diversity (including maximum gene node diversity and degree value) and phenotypic network diversity results corresponding to each symptom in SCN.

  # Usage
****
You should run the code in three steps
1. Run the function SCN_build() in SCN.py
2. Run the NodeDiversity/NodeDiversity.java
3. Run the SCN.py
