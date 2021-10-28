# TFR GENE SET
<img align="left" src="https://github.com/alosdiallo/TFR_Model/blob/main/github_docs/B_cell_t_cell.png" width="400" height="350">
   Applications of machine learning in immunology and medicine have seen an increase in the past decade {Eraslan, 2019 #915}{, 2020 #916}. These advances have been driven in part by the availability of sizable genomic datasets such as The Genotype-Tissue Expression(GTEX), The Cancer Genome Atlas (TCGA) and Immunological Genome Project (IMMGEN) {McLendon, 2008 #928}{Consortium, 2013 #910}{Heng, 2008 #917}. The ability to leverage these data sets by machine learning has also become more prevalent in immunology with the application of tools such as ImmuneML, and CIBERSORT {Pavlović, 2021 #914}{Newman, 2019 #929}. With these tools and genome wide datasets, researchers have been able to publish custom gene sets for use in gene set enrichment analysis to allow other researchers to leverage this knowledge for their own experiments {Subramanian, 2005 #923}{Segal, 2004 #924}. In this work we are proposing a custom gene set developed to help researchers understand a specific cell type in the immune system, specifically TFR cell gene expression.  This gene set will provide tool for researching immune responses especially where it relates to allergy response and cancer.
<br/>

   The immune system presents a complex organization, spread throughout the organism and largely rely on cell-cell communication to achieve protection from infection, tumor suppression, and to maintain a balanced interaction with the microbiota. Antigen recognition is a key feature of the immune system, based on the interaction between B and T cells, which express antigen-specific receptors called BCR and TCR, respectively. The interaction between B and T cells leads to phenotypic changes that correlate with their function. These cells’ activation state, differentiation, and effector function rely on their gene expression changes. Furthermore, factors including genetic factors, drugs and ageing can alter gene expression profiles. These gene expression changes can be assessed by high-throughput sequencing analyses.
<br/>
   Immune responses are finely controlled by the regulatory components of the immune system, such as regulatory T cells (Tregs). They are characterized by the expression of the transcription factor, Foxp3 and can suppress effector T cells through surface molecules and cytokine secretion. {Sakaguchi, 2008, Regulatory T cells and immune tolerance}. A particular subset of regulatory T cells are T follicular regulatory cells (Tfr). These cells have regulatory functions and gain access to the B cell follicle within lymphoid organs where they play important roles in modulating germinal center reactions {Sage, 2020, The multifaceted functions of follicular regulatory T cells;Chung, 2011, Follicular regulatory T cells expressing Foxp3 and Bcl-6 suppress germinal center reactions;Linterman, 2011, Foxp3+ follicular regulatory T cells control the germinal center response;Wollenberg, 2011, Regulation of the germinal center reaction by Foxp3+ follicular regulatory T cells}. Germinal centers are microanatomical structures where B cells undergo somatic hypermutation and BCR affinity maturation through multiple rounds of interactions with T follicular helper cells (Tfh) {Jacob, 1991, Intraclonal generation of antibody mutants in germinal centres;Berek, 1991, Maturation of the immune response in germinal centers;Jacobson, 1974, Effect of thymus cell injections on germinal center formation in lymphoid tissues of nude (thymusless) mice;Han, 1995, Cellular interaction in germinal centers. Roles of CD40 ligand and B7-2 in established germinal centers}. The regulatory role of Tfr cells optimizes the immune response, enabling the generation of high affinity antibodies while preventing the generation of autoreactive antibodies that could be pathogenic {Clement, 2019, Follicular regulatory T cells control humoral and allergic immunity by restraining early B cell responses;Gonzalez-Figueroa, 2021, Follicular regulatory T cells produce neuritin to regulate B cells;Wu, 2016, Follicular regulatory T cells repress cytokine production by follicular helper T cells and optimize IgG responses in mice;Fu, 2018, Deficiency in T follicular regulatory cells promotes autoimmunity;Lu, 2021, CD4+ follicular regulatory T cells optimize the influenza virus-specific B cell response}. In order to differentiate Tfr cells from other T cell subsets, a gene set from Tfr cells should be able to separate them from Treg and Tfh cells which presents a challenge since their gene expression patterns overlap to some extent in their regulatory component and their follicular phenotype component, respectively.  
<br/>
   Being able to paint a clear picture of the gene expression landscape for individual types of immune cells can help give researchers tools needed to better understand these cells’ phenotype and functions. Work such as the Immunological Genome Project work towards this goal {Heng, 2008 #917}. Over the past decade, the development of more sophisticated tools to aid immunologists coupled with decreased sequence costs have allowed researchers to more effectively develop strategies to examine various cell types in different contexts, such as lymphoid tissues and the tumor microenvironment {Maslova, 2020 #913}{Pavlović, 2021 #914}.  In addition, the use of statistical models in molecular biology can also often provide insight that is difficult or costly to obtain through in vitro experiments {Eraslan, 2019 #915}. Here we developed a Tfr custom gene set that has been generated using machine learning methods to help researchers examine the effects of Tfr gene expression, when conducting experimentation. This TFR  gene list is designed to be easily used for pathway analysis in the GSEA tool, along with other pathway analysis tools such as Panther, and Enrichr. This should help researchers better understand the roles of TFR cells in immune responses. 
   <br/>

[T follicular regulatory cells](https://pubmed.ncbi.nlm.nih.gov/27088919/)
<br/>
[The receptor PD-1 controls follicular regulatory T cells in the lymph nodes and blood](https://pubmed.ncbi.nlm.nih.gov/23242415/)
<br/>
[The multifaceted functions of follicular regulatory T cells](https://www.sciencedirect.com/science/article/abs/pii/S0952791520301084?via%3Dihub)

## Requirements 
To run the code you will need R version 4
A full list of packages needed can be found in the markdown file.<br/>
The gene set was tested on the GSEA app version 4.1.0


Authors
--------------------
	Alos Diallo - Department of Immunology, Harvard Medical School
	Cecilia B Cavazzoni - Transplantation Research Center, Renal Division, Brigham and Women's Hospital
  	Jiaoyuan E Sun - Department of Immunology, Harvard Medical School
  	Peter T Sage2 - Transplantation Research Center, Renal Division, Brigham and Women's Hospital
	
  	
Copyright © 2021 the President and Fellows of Harvard College.
 
<img align="left" src="https://github.com/alosdiallo/HMS_Immunology_RNASeq/blob/master/Blavatnikimmunology.jpg">
<img align="left" src="https://github.com/alosdiallo/TFR_Model/blob/main/github_docs/bwh-logo.svg" width="300" height="100"> <br/>



### [MIT License](https://github.com/alosdiallo/HiC_Network_Viz_tool/blob/master/Licence.txt)




