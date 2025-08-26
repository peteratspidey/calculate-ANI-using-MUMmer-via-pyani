# calculate-ANI-using-MUMmer-via-pyani
usign MUMmer for alignment and then caluclate the ANI for finding the relation between 2 sequence usign pyani (automated ANIm,ANIb
# 
| Method          | Tool Used    | How It Works                                                                 | Notes                                        |
| --------------- | ------------ | ---------------------------------------------------------------------------- | -------------------------------------------- |
| **ANIb**        | BLASTN       | Breaks genomes into 1,020 bp fragments and aligns using BLASTN               | Slower but accurate                          |
| **ANIm**        | MUMmer       | Whole-genome alignment using MUMmer                                          | Fast, recommended for highly similar genomes |
| **ANIblastall** | Legacy BLAST | Older version of ANIb using `blastall`                                       | Deprecated                                   |
| **TETRA**       | None         | Uses **tetranucleotide frequency correlation** instead of sequence alignment | Useful for distant genomes                   |
