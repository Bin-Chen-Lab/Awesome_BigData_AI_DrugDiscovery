# Introduction to Bioinformatics/Cheminformatics
(***) [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) by Robert Tibshirani.  
If you have a little statistical background, read this book first.

(***) [Machine Learning course at Coursera](coursera.org/learn/machine-learning) by Andrew Ng.  
A required course for any people who are interested in machine learning.

(***) [R & Bioconductor Manual](http://manuals.bioinformatics.ucr.edu/home/R_BioCondManual/).  
Ensure you have run the code before taking any bioinformatics project.

(***) [HT Sequence Analysis with R and Bioconductor](http://manuals.bioinformatics.ucr.edu/home/ht-seq).  
Ensure you have run the code before taking any NGS project.

(***) [ChemmineR: Cheminformatics Toolkit for R](http://www.bioconductor.org/packages/devel/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html).  
Suggest to run the code before taking any cheminformatics project.

(**) [Step by Step to practice deep learning](http://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html).   
PyTorch tutorial for deep learning.

(***) [HarvardX Biomedical Data Science Open Online Training](http://rafalab.github.io/pages/harvardx.html).   
comprehensive tutorial on data science with code from rafalab.

(***) [Statistics for biologists from StatQuest](https://statquest.org/video-index/).   
outstanding video tutorials by Josh Starmer.

(**) [Data Science Cheat Sheet](https://github.com/Bin-Chen-Lab/BigData_AI_DrugDiscovery/blob/master/data_science_cheatsheet.pdf).
A quick check list of basics in data science (credit to Maverick Lin)

(***) Single cell RNA-Seq analysis [osca](https://osca.bioconductor.org/introduction.html), [seurat](https://satijalab.org/seurat/vignettes.html). 
outstanding framework for scRNA-Seq analysis.

# Fundamental papers
**These papers I read at least 10 times, including supplementary materials! All of them are three stars!**

## Field review
(***) [Hallmarks of Cancer: The Next Generation](http://www.cell.com/abstract/S0092-8674%2811%2900127-9), by Robert A. Weinberg.  
Fundamental to understand cancer. 

(***) [Tumor Metastasis: Molecular Insights and Evolving Paradigms](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3261217/), by Robert A. Weinberg.  
Fundamental to understand cancer metastasis.

(***) [Cancer genome landscapes](http://science.sciencemag.org/content/339/6127/1546.long), by Bert Vogelstein.   
Fundamental to understand cancer genomics.

(***) [Cancer transcriptome profiling at the juncture of clinical translation](https://www.nature.com/articles/nrg.2017.96), by Arul M. Chinnaiyan.   
review on cancer transcriptomics.

(***) [Ewing sarcoma: historical perspectives, current state-of-the-art, and opportunities for targeted therapy in the future.](https://www.ncbi.nlm.nih.gov/pubmed/18525337).  
A typical review on the therapeutic discovery of one cancer.

(***) [Opportunities and challenges in phenotypic drug discovery: an industry perspective](https://www.nature.com/nrd/journal/v16/n8/abs/nrd.2017.111.html).  
Our drug discovery approach is one type of phenotypic screening.

(***) [Ten Years of Pathway Analysis: Current Approaches and Outstanding Challenges](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002375), by Purvesh Khatri.  
A very nice summary of method development in pathway analysis.

(***) [Deep learning](https://www.nature.com/nature/journal/v521/n7553/full/nature14539.html) by Yann LeCun,	Yoshua Bengio & Geoffrey Hinton.  
Deep learning review.

(***) [High-performance medicine: the convergence of human and artificial intelligence](https://www.nature.com/articles/s41591-018-0300-7) by Eric Topol.
Current progress and challenges in applying DL into biomedical research.

## Statistical method development
(***) [Significance analysis of microarrays applied to the ionizing radiation response](http://www.pnas.org/content/98/9/5116.full), by Robert Tibshirani.  
Development of SAM, a popular method to perform differential expression analysis using microarray data.  

(***) [limma: Linear Models for Microarray Data](https://link.springer.com/chapter/10.1007/0-387-29362-0_23).  
Development of LIMMA, another popular method to perform differential expression analysis using microarray data.

(***) [Differential expression analysis for sequence count data](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2010-11-10-r106), by Simon Anders.  
Development of DEseq, a popular method to perform differential expression analysis using RNA-SEQ data.  

(***) [Gene set enrichment analysis: a knowledge-based approach for interpreting genome-wide expression profiles](http://www.pnas.org/content/102/43/15545.long), by Jill P. Mesirov.  
Development of GSEA, the most popular gene set enrichment analysis method and the fundamental to understand our drug discovery method.

(***) [Adjusting batch effects in microarray expression data using Empirical Bayes methods](https://academic.oup.com/biostatistics/article/8/1/118/252073/Adjusting-batch-effects-in-microarray-expression).  
Development of Combat, a method to correct batch effects.

(***) [Emergence of Scaling in Random Networks](http://science.sciencemag.org/content/286/5439/509.full) by Albert-László Barabási.  
Discovery of scale-free networks.

(***) [Pathsim: Meta path-based top-k similarity search in heterogeneous information networks](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.220.2455) by Jiawei Han.  
A typical machine learning approach to mining heterogeneous networks.

(***) [MuSiC: Identifying mutational significance in cancer genomes](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3409272/), by Li Ding.  
Development of MuSic, a popular method to identify mutations.

## Informatics method development and application
(***) [The Connectivity Map: using gene-expression signatures to connect small molecules, genes, and disease.](http://science.sciencemag.org/content/313/5795/1929.long) by Justin Lamb.  
The first paper to describe our drug discovery approach.

(***) [Discovery and Preclinical Validation of Drug Indications Using Compendia of Public Gene Expression Data](http://stm.sciencemag.org/content/3/96/96ra77) from Atul's lab.  
The basic of our drug discovery work, and a great demonstration of writing a computational paper (from method development to experimental validation).

(***) [Relating protein pharmacology by ligand chemistry](http://www.nature.com/nbt/journal/v25/n2/full/nbt1284.html) by Michael J Keiser and Brian K Shoichet.  
The development of SEA, a method to predict drug-target interactions, and another great demonstration of writing a computational paper.

(***) [Characterization of drug-induced transcriptional modules: towards drug repositioning and functional understanding](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3658274/) by Peer Bork.  
start with data analysis and end with a few biological experiments.

(***) [Cross-Species Regulatory Network Analysis Identifies a Synergistic Interaction between FOXM1 and CENPF that Drives Prostate Cancer Malignancy](http://www.cell.com/cancer-cell/fulltext/S1535-6108(14)00125-1) by Andrea Califano.  
start with data analysis and end with a few biological experiments.

(***) [Elucidating compound mechanism of action by network perturbation analysis](http://www.sciencedirect.com/science/article/pii/S0092867415006996) by Andrea Califano.  
start with data analysis and end with a few biological experiments.

(***) [Discovery of drug mode of action and drug repositioning from transcriptional responses](http://www.pnas.org/content/107/33/14621.long).  
start with data analysis and end with a few biological experiments.

(***) [Imagenet classification with deep convolutional neural networks](http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf).  
Development of convolutional neural networks (CNN), the popular deep learning method.

## Computational analysis 
(***) [Drug-target network](https://www.nature.com/nbt/journal/v25/n10/full/nbt1338.html) by Barabási.  
Network analysis of drug-target interactions.

(***) [Comprehensive molecular portraits of human breast tumours](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3465532/) from TCGA.  
A typical genomic analysis paper from TCGA.

(***) [Mutational landscape and significance across 12 major cancer types.](http://dx.doi.org/10.1038/nature12634), by Li Ding.  
A phenomenal paper on pan-cancer genomic analysis.

(***) [Comprehensive Characterization of Molecular Differences in Cancer between Male and Female Patients](http://www.cell.com/cancer-cell/fulltext/S1535-6108(16)30111-8), by Han Liang.  
A phenomenal paper on pan-cancer genomic analysis.

(***) [Genetics of rheumatoid arthritis contributes to biology and drug discovery.](https://www.nature.com/nature/journal/v506/n7488/full/nature12873.html) by Robert M. Plenge.  
great work using genetics for drug discovery.

(***) [The Cancer Cell Line Encyclopedia enables predictive modelling of anticancer drug sensitivity](https://www.nature.com/nature/journal/v483/n7391/full/nature11003.html).  
phenomenal work using cell line data to discover biomarkers.

(***) [A comprehensive time-course–based multicohort analysis of sepsis and sterile inflammation reveals a robust diagnostic gene set](http://stm.sciencemag.org/content/7/287/287ra71.short) by Purvesh Khatri.  
Phenomenal work using public microarray data to discover biomarkers.

(***) [Prediction of biological targets for compounds using multiple-category Bayesian models trained on chemogenomics databases](http://pubs.acs.org/doi/10.1021/ci060003g) by Jeremy Jenkins.  
A typical machine learning paper in cheminformatics.

(***) [Do structurally similar molecules have similar biological activity](https://dx.doi.org/10.1021/jm020155c).  
A typical data analysis paper in cheminformatics.

## Deep-learning based drug discovery
(***) [Deep reinforcement learning for de novo drug design](http://advances.sciencemag.org/content/4/7/eaap7885) by Tropsha.  
Develop a model to generate targeted chemical libraries of novel compounds optimized for either a single desired property or multiple properties.

(***) [Convolutional Networks on Graphs for Learning Molecular Fingerprints](https://arxiv.org/abs/1509.09292) by Ryan Adams.
Designed DL based fingerprints inspired by ECFP

(***) [Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules](https://pubs.acs.org/doi/full/10.1021/acscentsci.7b00572)
Used Variational autoencoder to encode SMILES and optimize compounds from the latent space.

## Shape our future
(***) [Single-cell RNA-seq highlights intratumoral heterogeneity in primary glioblastoma](http://science.sciencemag.org/content/344/6190/1396).  
Application of single cell in a cancer study.

(***) [Single-cell transcriptomics uncovers distinct molecular signatures of stem cells in chronic myeloid leukemia](https://www.nature.com/nm/journal/v23/n6/full/nm.4336.html).  
Application of single cell analysis toward personalized cancer therapy.

(***) [Brown Adipogenic Reprogramming Induced by a Small Molecule](http://www.sciencedirect.com/science/article/pii/S2211124716317697) by Sheng Ding.  
Using small molecules to control cell development.

(***) [Correlating chemical sensitivity and basal gene expression reveals mechanism of action.](https://www.nature.com/nchembio/journal/v12/n2/full/nchembio.1986.html) from Stuart Schreiber.  
Usage of pharmacogenomics data to understand drug mechanisms.

(***) [A Next Generation Connectivity Map: L1000 Platform And The First 1,000,000 Profiles](https://www.biorxiv.org/content/early/2017/05/10/136168) from Todd R. Golub.  
LINCS, the dataset we primarily used for drug discovery.

(***) [Integrative clinical genomics of metastatic cancer](http://www.nature.com/nature/journal/v548/n7667/full/nature23306.html).  
We have lots of experience working on primary cancer, now it's time to place our interest to metastatic cancer, which the majority of patients die from.

(***) [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/pdf/1703.10593.pdf).  
Using deep learning GAN to realize domain knowledge translation.

# Outstanding tools and datasets for translational drug discovery

**use liver cancer as an example, can be applied to other cancers, only list outstanding tools/datasets for liver cancer drug discovery**
## Diseases/Patients
(***) [ClinicalTrials.gov](https://clinicaltrials.gov).  
Search drugs used in liver cancer clinical trials.

(**) [Cancer Today (Globocan): Data visualization tools that present current national estimates of cancer incidence, mortality, and prevalence](http://gco.iarc.fr/today/home).  
Search liver cancer incidence.

(*) [UK Biobank](http://www.ukbiobank.ac.uk/). [UK Biobank Engine](https://biobankengine.stanford.edu/).  
Search public clinical/molecular data for liver cancer and search genetic variants for liver cancer via Stanford Biobank Engine.

(**) [COSMIC](http://cancer.sanger.ac.uk/cosmic).  
Search somatic mutation for liver cancer.

## Target Discovery
(***) [cBioPortal](http://www.cbioportal.org/).  
Search molecular alterations for liver cancer from public datasets including TCGA.

(***) [GTEx](http://www.gtexportal.org).  
Search gene expression in normal liver tissues.

(***) [The Human Protein Atlas](https://www.proteinatlas.org/).  
Search protein expression and pathology for liver cancer.

(***) [Cancer Cell Line Encyclopedia](https://portals.broadinstitute.org/ccle).  
Search gene expression in liver cancer cell lines.

(*) [Project Achilles](https://portals.broadinstitute.org/achilles).  
Search essential genes in liver cancer cells.

(***) [DepMap](https://depmap.org/portal/).
create a comprehensive preclinical reference map connecting tumor features with tumor dependencies to accelerate the development of precision treatments.

(***) [GEO](https://www.ncbi.nlm.nih.gov/geo/).  
Search functional genomics data for liver cancer, requiring additional computational analysis to create a liver cancer signature.

(***) [Enrichr](http://amp.pharm.mssm.edu/Enrichr/).  
Search enriched TS/pathways/biological processes/cell types given a list of genes.

(***) [STRING DB](https://string-db.org/).  
Visualize protein-protein interactions.

## Drug Discovery
(***) [PubChem](https://pubchem.ncbi.nlm.nih.gov/).  
Everything needed to know about a compound/drug.

(**) [DrugBank](https://www.drugbank.ca/).  
Search drug-target-indication.

(**) [SEA](http://sea.bkslab.org/).  
Predict targets of a given compound.

(***) [LINCS](https://clue.io/).  
Predict drugs given a liver cancer signature.

(**) [ChemMine](http://chemmine.ucr.edu/).  
very useful for chemical structure enrichment analysis.

# NGS analysis
(***) [RNASEQ blog](http://www.rna-seqblog.com/).  
A great collection of RNA-SEQ analysis methods/applications.

(*) [RPKM, FPKM and TPM, clearly explained](http://www.rna-seqblog.com/rpkm-fpkm-and-tpm-clearly-explained/)

(*) [RNA-seq workflow: gene-level exploratory analysis and differential expression](http://www.bioconductor.org/help/workflows/rnaseqGene/)

# Python packages
(***) [anaconda](https://anaconda.org/)
Suggest using anaconda to manage python packages.

(***) [scikit: a popular python machine learning packages](http://scikit-learn.org/stable/).  

(**) [rdkit](http://www.rdkit.org/docs/index.html).  
free python library to process chemical structures.

(***) [PyTorch](http://pytorch.org/).  
Deep learning framework.

# R/Bioconductor packages
(**) [ggplot cheatsheet](http://zevross.com/blog/2014/08/04/beautiful-plotting-in-r-a-ggplot2-cheatsheet-3/). A must read to visualize data using R.  

(**) [ChemmineR: Cheminformatics Toolkit for R](http://www.bioconductor.org/packages/devel/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html)

(**) [biomaRt](http://bioconductor.org/packages/release/bioc/html/biomaRt.html).  
A great package to map IDs.

(***) [GEOquery](http://bioconductor.org/packages/release/bioc/html/GEOquery.html).  
Search and download data from GEO.

(**) [cgdsr](https://cran.r-project.org/web/packages/cgdsr/index.html). 
API to access cBioportal data.

(**) [pheatmap](https://cran.r-project.org/web/packages/pheatmap/index.html).  
Visualize heatmap.

(*) [Easy Way to Mix Multiple Graphs on The Same Page](http://www.sthda.com/english/articles/24-ggpubr-publication-ready-plots/81-ggplot2-easy-way-to-mix-multiple-graphs-on-the-same-page/).  









