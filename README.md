# Hitchhiker's Guide to PCA: <br/> Demystifying dimensionality reduction in R/Bioconductor

*Lauren Hsu, Aedin Culhane*


##  Description
This workshop will provide a beginner's guide to principal component analysis (PCA), the difference between singular value decomposition, different forms of PCA and fast PCA for single-cell data. We will describe how to detect artifacts and select the optimal number of components. It will focus on SVD and PCA applied to single-cell data.

Principal component analysis (PCA) is a key step in many bioinformatics pipelines. In this interactive session we will take a deep dive into the various implementations of singular value decomposition (SVD) and principal component analysis (PCA) to clarify the relationship between these methods, and to demonstrate the equivalencies and contrasts between these methods. We will also discuss interpretation of outputs, as well as some common pitfalls and sources of confusion in utilizing these methods.
 
### Pre-requisites
A basic understanding of R syntax would be helpful, but not required. No prior knowledge of PCA necessary.
 
### Workshop Participation
We invite audience members to engage with questions and examples from their own workflows. R notebooks will also be available in advance to run code interactively with the workshop.
 
### _R_ / _Bioconductor_ packages used
- stats (`prcomp`, `princomp`, `svd`)
- FactoMineR
- ade4
- irlba
- ggplot2
 
### Time outline
- Set-up + package installation (5 min)
- Introduction to matrix factorization and PCA [conceptual] (15 min)
- Interactive demonstration of methods (25 min)
- Potential pitfalls, interpreting outputs, and how to decide what’s right for your pipeline (15 min)
 
## Workshop goals and objectives
 
Upon completion of this workshop, we expect participants to have gained an understanding of how to apply PCA and other SVD-based methods in research.

### Learning goals
1. Understand how PCA works, the variations of PCA, and how it relates to SVD
2. Suggest appropriate use cases for these dimensionality reduction techniques
3. Select appropriate methods for use in bioinformatics pipelines
 
### Learning objectives
 
1. Describe the similarities and differences between the different implementations of PCA and SVD in R/Bioconductor
2. Perform PCA/SVD on real data
3. Creating plots to interpret PCA/SVD outputs, including diagnosis of problems like arch/horseshoe effect


 

