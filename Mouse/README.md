# Mouse ncRNA reference expansion

Local replacement candidate for `wwdff/SmallRNA-Reference-Database/Mouse`.

This reference contains 29,531 distinct full sequences, including all 8,477 sequences and IDs in the current `Mouse/reference.fa`. The expansion adds 21,054 sequences. The FASTA contains 15,514 records below 200 nt and 14,017 records at least 200 nt long.

The core combines the historical five-source reference with local Ensembl 89, GtRNAdb mm10, miRBase 21, Rfam 12.3 and rRNAdb files. The source configuration follows the [SPORTS1.1 mouse reference layout](https://github.com/junchaoshi/sports1.1). The candidate excludes piRBase and whole-genome contigs.

Identical full sequences share a FASTA ID. Metadata preserves source aliases and RNA categories. The sources include GRCm38 and GRCm39 annotations, stem-loop precursors, rRNA precursors, long ncRNA transcripts and Rfam coordinate regions. Sequence lengths describe FASTA records. 51 records contain bases beyond A/C/G/T.

## Sources, citations and conditions

- **SPORTS1.1 mouse reference resources.** The expansion uses the local mouse reference files corresponding to the SPORTS1.1 configuration: Ensembl release 89 (GRCm38 ncRNA), GtRNAdb mm10 tRNA, miRBase 21 mouse stem-loop sequences, Rfam 12.3 mouse regions, and the rRNAdb rRNA/Y RNA collection. Source counts and aliases are recorded by underlying database. The redistribution status of these local source files remains `PENDING`. [SPORTS1.1 repository](https://github.com/junchaoshi/sports1.1)
- **Suggested citation.** Shi J, Ko E-A, Sanders KM, Chen Q, Zhou T. *SPORTS1.0: A Tool for Annotating and Profiling Non-coding RNAs Optimized for rRNA- and tRNA-derived Small RNAs*. Genomics, Proteomics & Bioinformatics (2018). [doi:10.1016/j.gpb.2018.04.004](https://doi.org/10.1016/j.gpb.2018.04.004)

### Source record counts

| Source | Records |
|---|---:|
| Ensembl116 | 5,548 |
| Ensembl89_GRCm38 | 19,414 |
| GtRNAdb_local_mm10 | 906 |
| GtRNAdb_mm39 | 407 |
| NCBI_45S | 1 |
| Rfam12.3_local_mouse | 47,503 |
| local_mmu_mirna_DNA | 1,978 |
| local_mmu_other_DNA | 3,345 |
| miRBase 21 mouse | 1,193 |
| rRNAdb_local_mouse | 10 |


## Publication status

29,531 sequences have at least one source record marked PENDING under the recorded provenance and redistribution audit. Source-specific redistribution review is needed before public release.
