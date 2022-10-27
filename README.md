# Supplementary_Tables_Chapter_4
Chapter 4. Supplementary Tables S1-S3 for the PhD-Thesis: Genetics of Bottlenecked Species Through Time: Insights from Ancient Genomes of the Alpine ibex by Mathieu Robin

## Table S1: Sample information and mapping statistics
### Sampling Information: 
Sample information of all samples used in this study. Sample ID is the unique sample identification code. C14 Laboratory ID describes the AMS-14C dating, assigned by the respective radiocarbon dating facility according to international conventions. Age, the age of the sample: BP (before present) and CE (common era, equal to AD). Species, the respective species assignment of the sample. Museums ID, museum-specific identification code given by the museum, institution, or private owner. Owner, the donor of the sample. Country, the country of origin of the specimen. Age class, the age group following Raxworthy and Smith (2021), recent (0-10 years old), historic (<300 years old), and ancient (> 300 years old). Population, the population assignment code for group-wise analysis of samples. Longitude_WGS84 and Latitude_WGS84 are the sampling locations in WGS84 format. Comments describe additional information we have about the samples, such as ambiguous sampling locations. 
### Screening Statistics: 
Screening, previously sequenced samples sequenced by Grossen et. al (2020) and by the NextGen Consortium (https://nextgen.epfl.ch), “Success” labels are samples that passed the screening run and are used in the main analysis, “Failed” label is for samples that did not pass the screening process. The following statistics have been calculated with samtools v.1.10 (Li et al. 2009); Total Reads [N]: the total number of reads assigned to the respective sample on chromosome 1 (ARS1, Bickhart et al. 2017). Mapped Reads [N] is the number of mapped reads, filtered for MQ 30. Duplicates are the number of reads which are PCR duplicates. Duplicates [%] is the percentage of PCR duplicates of mapped reads. Reads surviving [N] is the number of reads which are not PCR duplicates and have a mapping quality MQ >30. Endogenous MQ30 [%] describes the endogenous DNA content in the sample. 
### Deep Sequencing Statistics:
Sequencer, Illumina Sequencer used to generate the sequencing data. Note that mapping statistics of Illumina HiSeq X have been published in Robin et al. (2022). The following statistics were inferred using ATLAS pipeline v.5.0 (Kieser et al. 2020). Average Read Length [bp], mean read length. Total Reads [N], the sum of reads assigned to a sample. Mean Read Depth [N], coverage as read depth per sample.



## Table S2: Nucleotide diversity
Nucleotide diversity statistics for different age categories and spatial distribution of samples. Age group, species, and age classes were analysed together. Mean group-wise nucleotide diversity, inferred with saf2theta (ANGSD). Standard Deviation, standard deviation calculated with R. Individuals [N], number of individuals in each age group. Dates, dates from the youngest to the oldest sample per age group. Time ranges [Years], the years between the youngest and oldest sample in the respective age group. 

## Table S3: Mapping statistics 
### Genome-wide theta:
A summary of raw data statistics, summarised from the output produced with the ATLAS pipeline v.5.0 implemented task = BAMDiagnostics (Kieser et al. 2020). Species, the species assignment. Sampling group: recent (0-10 years old), historic (<300 years old), and ancient (> 300 years old). Atlas Theta, heterozygosity inferred by ATLAS for 29 autosomes per sample. Standard Deviation, the standard deviation for Atlas Theta, calculated with R. Individuals [N], number of samples. 
### Relativised Derived Allele Ratio:
Genetic load calculated with snpEff v.5.0-1 by dividing the derived allele ratio (derived allele count / total allele count) of the respective category through the derived allele ratio. HIGH, variants with disruptive impact on the protein. MODERATE, Non-disruptive variant that changes protein effectiveness. LOW, mostly harmless protein behaviour. MODIFIER, Non-coding variants or variants affecting non-coding genes. nonCodingRegions, sites that originate from intergenic regions only (not divided by itself).  
### Rxy Analysis: 
Rxy < 1 indicates a relative frequency deficit in the respective sampling group compared to the recent Alpine ibex. Load categories as above. 
