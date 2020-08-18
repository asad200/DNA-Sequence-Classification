# DNA-Sequence-Classification
Classification of E. Coli bacteria DNA to identify if the DNA sequence is "promoter" or "non-promoter".

### Data Attribute Information:

1. One of {+/-}, indicating the class ("+" = promoter).
2. The instance name (non-promoters named by position in the 1500-long nucleotide sequence provided by T. Record).
3-59. The remaining 57 fields are the sequence, starting at position -50 (p-50) and ending at position +7 (p7). Each of these fields is filled by one of {a, g, t, c}.

### Relevant Papers:

Harley, C. and Reynolds, R. 1987. "Analysis of E. Coli Promoter Sequences." Nucleic Acids Research, 15:2343-2361.
[Web Link]

Towell, G., Shavlik, J. and Noordewier, M. 1990. "Refinement of Approximate Domain Theories by Knowledge-Based Artificial Neural Networks." In Proceedings of the Eighth National Conference on Artificial Intelligence (AAAI-90).
[Web Link] 

### Source:

Creators:

1. promoter instances: C. Harley (CHARLEY '@' McMaster.CA) and R. Reynolds

2. non-promoter instances and domain theory: M. Noordewier
-- (non-promoters derived from work of lab of Prof. Tom Record, University of Wisconsin Biochemistry Department)

Donor:

M. Noordewier and J. Shavlik, {noordewi,shavlik}@cs.wisc.edu
