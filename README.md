# DNA_modification_data

Matlab data files with DNA sequences and their corresponding nucleosome wrapping energies, corresponding to the article 

R. Giniūnaitė, T. Iešmantas, D. Petkevičiūtė-Gerlach. The impact of DNA point mutations and epigenetic modifications on the nucleosome wrapping energy. Submitted, 2024.

Each file contains a structure D with fields S (n x 147) containing n 147bp DNA sequences and u (1 x n), containing predicted nucleosome wrapping energies for each sequence. In the files with CG in their name, D also contains a field m with positions of all the CpG dinucleotides in the original sequence. Further description of the data can be found in the article.
