# Sensory Spaces of English Perceptual Verbs
This repository contains the code and collocational data described in the paper 
"Exploring the Sensory Spaces of English Perceptual Verbs in Natural Language Data". Our study reports on a data-driven approach based on distributional-semantic word embeddings and clustering models to identify the sensory spaces of perception verbs.  

Code in this repository relies on the UMBC corpus (Han 2013) and the Lancaster Sensorymotor Norms Dataset (Lynott 2020).

## Data
Collocational data is organized into directories as follows:
- dendrograms/ contains dendrograms for top descriptors by association index (OAI) for each perception verb
- lancaster/ contains Lancaster data for descriptors for each perception verb
- statistics/ contains the figures in the paper and other statistics such as siloutte scores and part of speech frequencies
- top_descriptors/ contains the roughly 1600 most frequently occuring descriptors and the top 300 descriptors by association index for each perception verb
- perception_analysis.ipynb contains the code used to generate the collocational data

# Works Cited
Roxana Girju and David Peng. Exploring the Sensory Spaces of English Perceptual Verbs in Natural Language Data. In the Proceedings of the 1st Workshop on Multisensory Data and Knowledge (MDK 2021), collocated with the 3rd Conference on Language, Data and Knowledge (LDK 2021), CEUR-WS.org, Zaragoza, Spain, Sept. 2021.

# License
This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit https://creativecommons.org/licenses/by/4.0/.
