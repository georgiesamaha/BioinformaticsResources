# BioinformaticsResources
List of tools for various bioinformatics methods and datasets

## Genomics 

|Data type|Tool                                                  |Function                                    |Input requirements|Resources                                              |
|---------|------------------------------------------------------|--------------------------------------------|------------------|-------------------------------------------------------|
|WGS      |[Slivar](https://github.com/brentp/slivar)            |Population-based annotation, filter variants|vcf.gz            |[Wiki](https://github.com/brentp/slivar/wiki)          |
|WGS      |[SURVIVOR](https://github.com/fritzsedlazeck/SURVIVOR)|Filter, merge, evaluate structural variants |vcf (not .gz)     |[Wiki](https://github.com/fritzsedlazeck/SURVIVOR/wiki)|
|WGS      |[BCFtools](https://samtools.github.io/bcftools/bcftools.html)|Filter, merge, subset, evaluate vcfs |vcf.gz     |[Cheatsheet](https://gist.github.com/elowy01/93922762e131d7abd3c7e8e166a74a0b)|
|WGS      |[Hap.py](https://github.com/Illumina/hap.py)|Gold standard vcf comparison tool (haplotype based) |vcf.gz     |[Bio validation](https://github.com/Sydney-Informatics-Hub/GermlineShortV_biovalidation)|
|WGS      |[GRIDSS2](https://github.com/PapenfussLab/gridss)            |Structural variant caller |bam           |[Wiki](https://github.com/PapenfussLab/gridss/wiki/Somatic-Filtering)          |
|Array, WGS      |[Plink](https://www.cog-genomics.org/plink2/)            |Everything |vcf, bcf, plink     ||
|Array      |[SNPflip](https://github.com/biocore-ntnu/snpflip)            |find reverse and ambiguous strand SNPs |plink .bim     ||
|Reference      |[Liftoff](https://github.com/agshumate/Liftoff)            |remap annotations between assemblies |gff, gtf   ||
|WGS|[VCFvalidator](https://github.com/EBIvariation/vcf-validator)|Validate vcf integrity|vcf.gz vcf.bz2||
|WGS|[LINX](https://github.com/hartwigmedical/hmftools)|Somatic structural variant classification|vcf|[Visualisation](https://github.com/hartwigmedical/hmftools/blob/master/linx/README_VIS.md)|
|WGS|[PURPLE](https://github.com/hartwigmedical/hmftools/blob/master/purple/README.md)|Tumour purity and ploidy estimator|bam, vcf|[GPL pipeline](https://github.com/hartwigmedical/gridss-purple-linx)|


## RNAseq
|Data type|Tool                                                  |Function                                    |Input requirements|Resources                                              |
|---------|------------------------------------------------------|--------------------------------------------|------------------|-------------------------------------------------------|
|RNAseq      |[TMPcalculator](https://github.com/ncbi/TPMCalculator)            |find reverse and ambiguous strand SNPs |bam, gtf   ||


## De novo transcriptomics
## Hi-C
## Metagenomics
## Nextflow

## Useful curated bioinformatics script and resource repos 

|Who|Repo                                                  |Utility                                     |
|---|------------------------------------------------------|--------------------------------------------|
|PeterMac|[PMCC](https://github.com/PMCC-BioinformaticsCore/scripts)|plotting, fastqc, rnaseq, performance, filtering|
|AstrobioMike|[Bioinformatics Tools](https://github.com/AstrobioMike/bit)|filtering, db querying|
|davfre|[SAM and BAM oneliners](https://gist.github.com/davfre/8596159) |read counting, filtering|
|EBI|[EBI Variation](https://github.com/EBIvariation)|various|
|Hartwig medical foundation | [HMFtools](https://github.com/hartwigmedical/hmftools)|Various WGS|
|Daniel Cook|[Awesome bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics)|curated resource lists|

## Compute resource profiling

|Tool|Platform                                              |
|----|------------------------------------------------------|
|[async-profiler](https://github.com/jvm-profiling-tools/async-profiler)|cloud, VM                                             |
|[HPC usage reports](https://github.com/Sydney-Informatics-Hub/HPC_usage_reports)|HPC, Artemis, Gadi, Flashlite   |
|[Memray](https://github.com/bloomberg/memray) |cloud, VM|

## Plotting 
