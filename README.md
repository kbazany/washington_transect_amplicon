# washington_transect_amplicon
16S and ITS amplicon sequencing data over a naturally occurring climate gradient over the Cascade Mountains in Washington State. Bioinformatics, statistics, and visualizations.

1. Processing amplicon sequencing sequences
2. Combining sequencing runs and generating ASV tables

* Files are in order, though 1.1-1.4 are interchangeable as are 2.1-2.2 and can be done out of order within.

This will contain code for...
  • Analyzing amplicon sequence data and creating ASV and OTU tables using the DADA2 plugin and R
  • Rarefying and normalizing tables
  • Performing alpha- and beta- diversity analyses
    - glms and PERMANOVAs
    - boxplots, line graphs, NMDS ordinations, CCA plots
  • Performing enrichment analyses
    - relative abundance, ANCOM-BC
    - ternary plots
  • Co-occurence analyses
    - SparCC co-occurence
    - Network analysis from gephi network results


# **Project Summary** 

The following code describes the sequence processing steps used to analyze **v4** data generated for the **washington elevation gradient** project. Data comes from DNA extracted from soils and surface sterilized roots. Samples were collected from Washington transect in **late summer 2023**. 

**Key**

**Plant Compartment**

1. **Rhizosphere Soil** == rhizo
2. **Root Endosphere** == root

**Amplicon**

1. **Bacteria** == o16S
2. **Fungi** == oITS

**Site**

1. CR1
2. CR1.5
3. CR2
4. CR3
5. CR4
6. TR4
7. TR3.5
8. TR3
9. TR2.5
10. TR2
11. TR1
  * .5 sites were added after the initial site selection and have less soil sampling data. They were excluded from some analyses related to soil chemistry. 
  * .5 sites have complete amplicon sequencing data.
  * CR refers to Cowlitz River sites on the western slopes of the Cascades.
  * TR refers to the Tieton River sites on the eastern slopes of the Cascades.
  * sites are listed in order of west to east.
  * CR4 is the highest elevation site.

*Soil Data* 

Standard Analytical Chemistry Methods

*Climate and Weather Data*

Pulled from DAYMET 

*Tree Phenotype Data*

Collected with LICOR6000

### Kathryn Bazany
### Oak Ridge National Lab
