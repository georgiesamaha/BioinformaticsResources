# BioinformaticsResources
List of tools for various bioinformatics methods and datasets

## NGS data processing
### Genomics 

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

### RNAseq
|Data type|Tool                                                  |Function                                    |Input requirements|Resources                                              |
|---------|------------------------------------------------------|--------------------------------------------|------------------|-------------------------------------------------------|
|RNAseq      |[TMPcalculator](https://github.com/ncbi/TPMCalculator)            |find reverse and ambiguous strand SNPs |bam, gtf   ||



### De novo transcriptomics
|Data type|Tool                                                  |Function                                    |Input requirements|Resources                                              |
|---------|------------------------------------------------------|--------------------------------------------|------------------|-------------------------------------------------------|
|De novo transcriptomics      |[Trinity runtime profiling](https://github.com/trinityrnaseq/trinityrnaseq/wiki/Trinity-Runtime-Profiling)            |Understand resource requirements of a trinity run |NA ||
|De novo transcriptomics      |[Trinity benchmarking](https://trinityrnaseq.github.io/performance/benchmark.html#)            |Understand resource requirements of a trinity run |NA ||

## Commandline utilities 

## Pipeline/workflow management 
### Tool installation guides
### Nextflow
[DIY Nextflow tutorial](https://sateeshperi.github.io/nextflow_varcal/nextflow/)   
[Building DSL2 pipelines](https://antunderwood.gitlab.io/bioinformant-blog/posts/building_a_dsl2_pipeline_in_nextflow/)   

### Galaxy
[Galaxy training network](https://training.galaxyproject.org/training-material/)  

## Useful curated bioinformatics script and resource repos 

|Who|Repo                                                  |Utility                                     |
|---|------------------------------------------------------|--------------------------------------------|
|PeterMac|[PMCC](https://github.com/PMCC-BioinformaticsCore/scripts)|plotting, fastqc, rnaseq, performance, filtering|
|AstrobioMike|[Bioinformatics Tools](https://github.com/AstrobioMike/bit)|filtering, db querying|
|davfre|[SAM and BAM oneliners](https://gist.github.com/davfre/8596159) |read counting, filtering|
|EBI|[EBI Variation](https://github.com/EBIvariation)|various|
|Hartwig medical foundation | [HMFtools](https://github.com/hartwigmedical/hmftools)|Various WGS|
|Daniel Cook|[Awesome bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics)|curated resource lists|
|nf-core|[nf-core tools](https://github.com/nf-core/tools)|nf-core helper scripts|
|AWS|[amazon-genomics-cli](https://github.com/aws/amazon-genomics-cli)|tool to simplify the processes of deploying the AWS infrastructure|
|BioWulf|[GATK benchmarking](https://hpc.nih.gov/training/gatk_tutorial/)|benchmarking, scalability of GATK commands|
|Xiaole Shirley Liu et al.|[Introduction to Bioinformatics and Computational Biology](https://liulab-dfci.github.io/bioinfo-combio/)|Course material for STAT115/215 BIO/BST282 at Harvard University|


## Compute resource profiling

|Tool|Platform                                              |
|----|------------------------------------------------------|
|[async-profiler](https://github.com/jvm-profiling-tools/async-profiler)|cloud, VM                                             |
|[HPC usage reports](https://github.com/Sydney-Informatics-Hub/HPC_usage_reports)|HPC, Artemis, Gadi, Flashlite   |
|[Memray](https://github.com/bloomberg/memray) |cloud, VM|
|[NetData](https://github.com/netdata/netdata)|VM, cloud|


## Plotting 
[vcfR](https://github.com/knausb/vcfR)   
[CMplot](https://github.com/YinLiLin/CMplot)  
[ggsashimi](https://github.com/guigolab/ggsashimi)  
[BioCircos](https://cran.r-project.org/web/packages/BioCircos/vignettes/BioCircos.html)  
[karyotypeR](https://bernatgel.github.io/karyoploter_tutorial/)  
[samplot](https://github.com/ryanlayer/samplot)  
[colourfindr](https://github.com/zumbov2/colorfindr)  
[NanoPlot](https://github.com/wdecoster/NanoPlot)  
[Raincloud plots](https://www.cedricscherer.com/2021/06/06/visualizing-distributions-with-raincloud-plots-and-how-to-create-them-with-ggplot2/)  
[chromoMap](https://lakshay-anand.github.io/chromoMap/docs.html#Getting_Started)  
[nVennR](https://cran.r-project.org/web/packages/nVennR/vignettes/nVennR.html)  
[HaplotypePlot](https://neobernad.github.io/haplotype_plot/#/)  
[Ideogram](https://eweitz.github.io/ideogram/)  
[R graph grammar](https://www.huber.embl.de/msmb/Chap-Graphics.html)  
[DiscoPlot](https://github.com/mjsull/DiscoPlot)  
