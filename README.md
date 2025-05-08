# Investigating-the-compensatory-changes-promoting-survival-in-DNAJC9-knock-out-cells
**Introduction:**

DNAJC9 is a heat shock chaperone and histone-binding protein involved in protein folding and chromatin organization.
It has emerging links to cancer, but its precise role in tumour biology is still unclear.
We analyzed the impact of DNAJC9 knockout using GO enrichment, protein interaction networks, and comparisons to published datasets (Hammond et al., 2021; Balachandra et al., 2024).
Results suggest disruption of cancer-related pathways, supporting the need for further investigation into DNAJC9’s therapeutic potential

**Aim:**

To investigate the functional role of DNAJC9 in cancer-related biological processes by analyzing the molecular consequences of DNAJC9 knockout (KO) compared to wild-type (WT) cells.

**Objective:**

Perform functional annotation and GO enrichment analysis.
Identify key biological processes and molecular functions.
Construct protein-protein interaction networks.
Use InteractiveVenn .
Compare findings to published datasets.

**Materials and Methods:**

From Excel sheet of WT vs KO chromatin volcano, selecting all the positive UniProt canonical IDs from column F and create a new Excel sheet. Paste all the negative IDs in another column and make another column for all the proteins. 

![image](https://github.com/user-attachments/assets/063b72c5-c420-42a9-a705-7b286db542d6)

                  Fig 1 - An excel sheet of WT vs KO chromatin volcano

![image](https://github.com/user-attachments/assets/2bc179e2-08b5-419c-b289-24286dabcde2)

                         Fig 2 - David's analysis

-Uploaded gene list to DAVID.

-Performed Functional Annotation Clustering to group genes by biological meaning.

-Conducted Gene Ontology (GO) analysis to identify enriched Biological Processes (BP), Molecular Functions (MF), and Cellular Components (CC).

-Selected top clusters and GO terms based on enrichment scores and p-value for biological interpretation. 

![image](https://github.com/user-attachments/assets/22c534d7-799b-48fa-ad96-4e6b46169945)

                      Fig 3 - GO Analysis enrichment scores and p-values

-Uploaded selected protein IDs into the STRING database.

-Mapped protein-protein interactions to visualize biological relationships and network connectivity.

![image](https://github.com/user-attachments/assets/2d98d8c5-a374-479d-84a4-7b65831f9d83)

                                Fig 4 - STRING analysis.

**Results**

![image](https://github.com/user-attachments/assets/885ad6c4-6219-4a1d-8014-c6889ba0be38)

         Fig 5 - DNAJC9 Knock-Out clones created via CRISPR-Cas9 deletion

![image](https://github.com/user-attachments/assets/62094847-ffb4-4c81-8403-266a51ccd862)![image](https://github.com/user-attachments/assets/9264d6ef-bf6a-483f-b494-bbe8dd304fd2)

          Fig 6: STRING Analysis – Biological relationships and Network connectivity.

![image](https://github.com/user-attachments/assets/0f14b721-b332-4187-a627-ac7b05b134af)

        Fig 7: Significant changes in soluble histone interactomes + siDNAJC9

                      Highlights changes in key histone chaperones

![image](https://github.com/user-attachments/assets/292dc9ca-d1af-4925-bf39-f3c0ae5c8896)

Fig 8: Significant changes in all soluble histone interactomes + siDNAJC9 compared to WT vs DNAJC9 KO proteomics

![image](https://github.com/user-attachments/assets/f0e76c06-e422-472a-a1c3-7bb0900c9924)

Fig 9: Histone-dependent and J mutant-trapped interactors of DNAJC9 show significant Changes in their chromatin association in DNAJC9 KO cells

![image](https://github.com/user-attachments/assets/9b68240e-1d27-456c-b70d-cbac8ed37a14)![image](https://github.com/user-attachments/assets/459fa024-9db3-4fc3-a3aa-2c3f00f8d776)

Fig 10: Increased chromatin association of histone chaperones (e.g., TONSL, MCM2, FACT, CENPA, CHAF1B) in DNAJC9 KO and J-domain mutant cells.

**Conclusions and Future Work**

-DNAJC9 KO alters chromatin protein interactions and histone chaperone networks.

-GO, STRING, and Cytoscape analyses reveal compensatory upregulation of chromatin regulators and complex interaction networks.

**Future Work**

Investigating the compensatory changes promoting survival in DNAJC9 knock-out cells

**References**

-Hammond et al., 2021

-Balachandra et al., 2024














