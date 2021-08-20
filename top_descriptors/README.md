# Top Descriptors
Information for descriptors is organized in the following directories:

differences/ contains select differences of two perception verbs, or the descriptors that are unique to one perception and not the other. The format is as follows: 
- Unnamed: 0: The descriptor with its POS tag
- OlfN: Frequency of descriptor in the +/- 4 word context window of the corresponding perception verb in the UMBC corpus
- TotalN: Frequency of descriptor in the entire UMBC corpus
- Tokens: All POS versions of the descriptor
- OAI: Association index of descriptor
- OSI: Specificity index of descriptor

intersections/ contains significant intersections of two perception verbs, or descriptors common to both. Format is as follows:
- Unnamed: 0: The descriptor with its POS tag
- OlfN_x: Context frequency of descriptor for first perception
- TotalN_x: Corpus frequency of descriptor for first perception
- Tokens_x: POS versions of the descriptor for first perception
- OAI_x: Association index of descriptor for first perception
- OSI_x: Specificity index of descriptor for first perception
The same data is repeated for the second perception verb.

top_by_association_index_300/ has the same data format as differences/ and contains the top 300 descriptors by association index for each perception verb.

top_by_frequency_1600/ has the same data format as differences/ and contains the top roughly 1600 descriptors by context frequency for each perception verb.
