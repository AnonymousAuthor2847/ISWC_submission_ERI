# Embedding Resemblence Indicator

This repository holds all code for our work described in "..." as submitted to ISWC 2021.

It includes the following code:
- parser for NDRF data from xml to owl
- edge list generator from owl for NDRF data
- similarity measure, & J for comparing two embeddings, impact measure, when given $\hat{\mu}$
- Python Jupiter notebook for generation of synthetic ontology versions, based on edgelist
- config files for libKGE
- R analysis notebook, which includes the calculation of ERI (uncleaned)

We do not include the code for the learning with BioNev and libKGE, which was used for the embedding learning in our evalution ERI.

It also includes the following data:
- Link prediction results for PPI and DDA, from BioNEV
- Similarity results
- calculated embeddings
