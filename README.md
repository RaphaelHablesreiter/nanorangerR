# nanoranger.R
R package for down-stream processing of [nanoranger](https://github.com/mehdiborji/nanoranger) output.

The package provides capabilities to read out single nucleotide variants, insertions/deletions,
fusion genes and CAR sequences from amplicons sequenced with long-read sequencing with the *nanoranger* protocol. 

---

![PCR scheme](man/20230212_PCR_scheme.png)

## Implemented functions

extract_mutation(): extraction of single nucleotide variants<br>
extract_indel(): extraction of insertions or deletions with specific length<br>
extract_length_diff(): detect truncated transcripts <br>
extract_fusion_gene9): extraction of fusion genes or CAR sequences
