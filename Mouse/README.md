# Initial GitHub documentation package

The descriptions below refer to the local candidate. FASTA and full metadata are omitted from this initial upload. The full mouse FASTA has not been publicly released. PENDING source sequences are excluded from this upload. Category counts describe the candidate, not released sequences.

# Mouse Small RNA Reference Database v1.0

Package date: 2026-11-05 (packaging date, not a new reference build). Status: LOCAL RELEASE CANDIDATE, NOT UPLOADED.

Reused B_Internal/Mouse_reference; FASTA copied byte-for-byte. 8,477 unique sequences and 12,472 source records retained. Taxonomy ID 10090. No sequence deletion, reannotation, or reference rebuilding. All existing source records retained in source_records_json, enriched with provenance and license fields. UNKNOWN means evidence missing, not unrestricted use.

## Processing

Inherited construction: uppercase DNA alphabet, U to T; exact full-length deduplication; all source records retained. Category counts overlap across multi-category sequences. No new length filter or biological species inference was applied in packaging. Human/mouse common sequences can exist naturally; matching nucleotide strings across species do not imply contamination. Taxid and explicit IDs checked; independent taxonomic revalidation was not performed.

Historical Ensembl filtering excludes missing transcript_biotype and lncRNA, misc_RNA, piRNA, retained_intron, TEC. Mature GtRNAdb and NCBI precursor records keep inherited maturity labels; mature and precursor miRNA status is not inferred from length. miRBase21 addition is inherited from the complete internal package, not newly built.

## Sources, citations and conditions

- Ensembl116; version 116 / GRCm39; 5548 source records. Download URL: https://ftp.ensembl.org/pub/release-116/fasta/mus_musculus/ncrna/Mus_musculus.GRCm39.ncrna.fa.gz. Status: PENDING. Policy: https://www.ensembl.org/about/articles/ensembl-content-disclaimer. Cite Ensembl, release 116; project-generated data unrestricted, third-party provenance unresolved.
- GtRNAdb_mm39; version Mmusc39 / mm39; 407 source records. Download URL: https://gtrnadb.ucsc.edu/genomes/eukaryota/Mmusc39/mm39-mature-tRNAs.fa. Status: PENDING. Policy: https://gtrnadb.org/citation.html. Chan & Lowe (2016), GtRNAdb 2.0, NAR 44:D184-D189; database redistribution permission unresolved.
- NCBI_45S; version NR_046233.2; 1 source records. Download URL: https://www.ncbi.nlm.nih.gov/sviewer/viewer.cgi?tool=portal&save=file&log$=seqview&db=nuccore&report=fasta&id=577019615&extrafeat=null&conwithfeat=on&hide-cdd=on&ncbi_phid=CE89E1AFAB9B8DF10000000000B800B0. Status: REDISTRIBUTION_ALLOWED_WITH_CONDITIONS. Policy: https://www.ncbi.nlm.nih.gov/home/about/policies/. Cite NCBI RefSeq NR_046233.2; molecular-data distribution policy with third-party rights caveat.
- local_mmu_mirna_DNA; version UNKNOWN; 1978 source records. Download URL: UNKNOWN. Status: PENDING. Policy: UNKNOWN. Credit original provider after verification; filename does not establish upstream license/version.
- local_mmu_other_DNA; version UNKNOWN; 3345 source records. Download URL: UNKNOWN. Status: PENDING. Policy: UNKNOWN. Credit original provider after verification; filename does not establish upstream license/version.
- miRBase 21 mouse; version 21; 1193 source records. Download URL: UNKNOWN. Status: PENDING. Policy: https://www.mirbase.org/. Cite miRBase release21; archived file download URL and applicable redistribution terms not verified.

## Rights and limitations

This project does not own third-party data copyrights. No blanket CC0 or redistribution authorization is asserted. 8476 sequences have at least one PENDING source record; they are preserved and must not be treated as cleared. An UNKNOWN download URL remains a provenance gap requiring confirmation. GitHub/Zenodo publication requires final approval after unresolved rights are addressed.
