# Initial GitHub documentation package

The descriptions below refer to the local candidate. FASTA and full metadata are omitted from this initial upload. Category counts describe the candidate, not released sequences.

# Human Small RNA Reference Database v1.0

Package date: 2026-11-05 (packaging date, not a new reference build). Status: LOCAL RELEASE CANDIDATE, NOT UPLOADED.

Reused A_Public/Human_reference; FASTA copied byte-for-byte. 32,294 unique sequences and 57,778 source records retained. Taxonomy ID 9606. No sequence deletion, reannotation, or reference rebuilding. All existing source records retained in source_records_json, enriched with provenance and license fields. UNKNOWN means evidence missing, not unrestricted use.

## Processing

Inherited construction: uppercase DNA alphabet, U to T; exact full-length deduplication; all source records retained. Category counts overlap across multi-category sequences. No new length filter or biological species inference was applied in packaging. Human/mouse common sequences can exist naturally; matching nucleotide strings across species do not imply contamination. Taxid and explicit IDs checked; independent taxonomic revalidation was not performed.

## Sources, citations and conditions

- NCBI_RefSeq:NCBI_RefSeq; version NR_145819.1; 1 source records. Download URL: UNKNOWN. Status: REDISTRIBUTION_ALLOWED_WITH_CONDITIONS. Policy: https://www.ncbi.nlm.nih.gov/home/about/policies/. Cite NCBI RefSeq NR_145819.1; original download URL absent from inherited metadata; record URL https://www.ncbi.nlm.nih.gov/nuccore/NR_145819.1
- RNAcentral_R20:alignment; version 20; 45798 source records. Download URL: UNKNOWN. Status: REDISTRIBUTION_ALLOWED. Policy: https://rnacentral.org/license. RNAcentral Consortium, RNAcentral 2021, NAR; CC0 applies from release20 onwards. Original download URL absent from inherited metadata.
- RNAcentral_R20:expert-database; version 20; 11979 source records. Download URL: UNKNOWN. Status: REDISTRIBUTION_ALLOWED. Policy: https://rnacentral.org/license. RNAcentral Consortium, RNAcentral 2021, NAR; upstream database labels preserved; release20 CC0 policy.

## Rights and limitations

This project does not own third-party data copyrights. No blanket CC0 or redistribution authorization is asserted. 0 sequences have at least one PENDING source record; they are preserved and must not be treated as cleared. An UNKNOWN download URL remains a provenance gap requiring confirmation. GitHub/Zenodo publication requires final approval after unresolved rights are addressed.
