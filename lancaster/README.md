# Lancaster
This directory contains Lancaster data for each perception verb's top descriptors, including aggregate statistics for modality and concreteness.

## Format
top_300_descriptors/ contains Lancaster data for the top 300 descriptors by association index (OAI) for each perception verb. top_1600_descriptors/ contains the same data for the roughly top 1600 descriptors by frequency.

The Lancaster_intersection.csv files contains the Lancaster data, with columns as follows:
- Word: The descriptor with its POS tag
- Dominant Perceptual: The dominant perceptual modality of the descriptor
- Exclusivity: Exclusivity score of dominant perceptual modality
- Strength Perceptual: Strength score of dominant perceptual modality

The Lancaster_missing.csv files contains the descriptors that were in the top descriptors of a perception verb but not in Lancaster. The format is as follows:
- Unnamed: 0: The descriptor with its POS tag
- OlfN: Frequency of descriptor in the +/- 4 word context window of the corresponding perception verb in the UMBC corpus
- TotalN: Frequency of descriptor in the entire UMBC corpus
- Tokens: All POS versions of the descriptor
- OAI: Association index of descriptor
- OSI: Specificity index of descriptor

Aggregate Lancaster statistics can be found in top_300_descriptors/modality_concreteness
