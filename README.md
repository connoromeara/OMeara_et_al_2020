# OMeara et al., 2020
# "Genetic landscape of T cells identifies synthetic lethality for T-ALL"

# Abstract
#### Interconnected networks of genes control cell identity and fitness. Perturbations of these genetic networks often give rise to unexpected phenotypes, uncovering genes regulating disease resistance and cancer sensitivity. Unlike cell culture models, genetic interaction analyses focused on live animals allow examination of cell type-specific responses and cell non-autonomous effects in the context of an overall change in an entire organism physiological state. This situation mirrors the challenges in clinical medicine, particularly with respect to evaluating undesired side effects of novel treatment strategies. Our large-scale forward genetic screens in zebrafish identified several dozens of genes whose mutations impaired the fitness of developing thymocytes, but spared a control cell type, growth hormone-expressing somatotrophs in the hypophysis. These genetic variants were subjected to an interaction screen, which additionally incorporated small molecule inhibitors, specifically mimicking the effects on the major pathways impaired by mutant genes. The resulting interaction network not only revealed cell type-specific networks regulating T cell development, but also led to the discovery of several pairs of small molecules exhibiting synthetically lethality for developing T cells. When tested in adult fish, these drug combinations demonstrated therapeutic utility in a zebrafish model of T cell acute lymphoblastic leukemia (T-ALL). Our findings illustrate how genetic interaction data obtained in the context of entire organisms can be exploited for targeted interference with specific cell types. 

# This Repository
#### The purpose of this repository is to supply raw data files and a detailed description of the analysis used to obtain data in Figure 1, 2 and 3 from O'Meara et al., 2020

# FIGURE 1 - PATHWAY ENRICHMENT.Rmd
#### FROM: A list of differentially expressed genes for each mutant line,
#### USE: ClusterProfiler to identify the enriched pathways for each mutant line, to
#### GET: Dotplots of enriched pathways and Heatmap of top differentially expressed genes for each enriched pathway.

# FIGURE 2 - TISSUE SPECIFIC EXPRESSION.Rmd
#### FROM: The mouse bioGPS microarray data, containing whole genome expression profiles for approximately 90 different tissues
#### USE: Expression of a gene relative to the mean expression across tissues, to
#### GET: A list of genes significantly expressed by each tissue, identifying gene expression signatures for each tissue.

# FIGURE 3 - GENETIC INTERACTION NETWORK.Rmd
#### FROM: A list of pairwise genetic interactions affecting rag1 relative to ghrh expression
#### USE: the Product/Multiplicative method to predict the expected phenotype and compare to observed phenotype, to
#### GET: A network of genes and interactions that positively/negatively affect T cell survival.
