# SRA-to-FASTQ
Convert SRA files to FASTQ files in BASH

# This script processes SRA files in subdirectories of a specified input directory
# It uses fasterq-dump to convert SRA files to FASTQ format and moves the resulting files to a specified output directory for downstream analysis
# Ensure you have SRA toolkit installed
# This code requires SRA subdirectories to be downloaded from NCBI via <prefetch --option-file SraAccList.txt>
# To make an SraAccList.txt file visit: https://www.ncbi.nlm.nih.gov/sra/docs/sradownload/
