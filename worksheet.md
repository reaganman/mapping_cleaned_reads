# Mapping Cleaned Reads Worksheet

<!--- Write name below --->
## Name: Reagan McKee

<!--- For this worksheet, answer the following questions --->

## Q1: What does it mean to map/align reads to a reference?
Answer: Find the position where the read is most similar to the reference

## Q2: What read mapper does the mapping_cleaned_reads.sh script use?
Answer: bwa

## Q3: Both Illumina and Nanopore reads are used for this assignment. What are the major differences between the methodology used for these sequencing platforms?
Answer: Illumina is sequencing by synthesis with shorter reads. Nanonpore works by measuring the change in electrical current as an already synthesized DNA strand is passing through and get you longer reads.

## Q4: What differences do you notice between the Illumina and Nanopre raw_data fastq file sizes? Which are larger?
Answer: The nanopore fastq files are larger

## Q5: What differences do you notice between the Illumina and Nanopore cleaned_reads fastq file sizes? Which are larger?
Answer: The illumina cleaned reads are larger 

## Q6: What explains the difference in your responses of Q4 and Q5? (HINT: Take a glimpse at the raw data .fastq files themselves)
Answer: I think it probably stems from the fact that you get longer reads with nanopore so the raw read files will be larger. After filtering, its possible that the Nanopore files are smalling because more of them are getting removed as quality is generally lower than illumina. 

## Q7: What is the average read depth for the Illumina data across all samples for the genomic regions that were mapped to?
Answer: 37901

## Q8: What is the average read depth for the Illumina data across all samples for all genomic regions?
Answer: 338

## Q9: What is the average read depth for the Nanopore data across all samples for the genomic regions that were mapped to?
Answer: 0.0465426

## Q10: What is the average read depth for the Nanopore data across all samples for all genomic regions?
Answer: 0.0176322
