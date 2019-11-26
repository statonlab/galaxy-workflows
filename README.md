# Galaxy Workflows

**Quality Control - Perform trimming on raw next generation sequencing reads (Illumina only) with Trimmomatic and get a quality report from FastQC.**

+ [Sequence quality control (single-end)](hwg_workflows/sequence-quality-control-single-end.ga)
+ [Sequence quality control (paired-end)](hwg_workflows/sequence-quality-control-paired-end.ga)

**Sequence Analysis**

+ **Mapping** - Map short next generation sequencing reads to a reference genome.

    - [Short Read Mapping using Bowtie2 (single-end)](hwg_workflows/mapping-bowtie2-single-end.ga)
    - [Short Read Mapping using Bowtie2 (paired-end)](hwg_workflows/mapping-bowtie2-paired-end.ga)
    - Short Read Mapping using HISAT2 (single-end) (available soon)
    - Short Read Mapping using HISAT2 (paired-end) (available soon)

+ **Functional Gene Annotation** - Get predicted function of gene sequences.

    + [BLASTP to compare protein sequences to a protein database - SwissProt protein database provided, or upload your own protein database](hwg_workflows/blast-protein-sequences.ga)
    + [InterProScan protein domain functional analysis for protein or nucleotide sequences](hwg_workflows/interproscan-protein-functional-analysis.ga) 

**Transcriptomics**

+ RNA-Seq differential expression analysis (htseq-count, DESeq2)

    - [Counting mapped reads](hwg_workflows/htseq-count-mapped-reads.ga)
    - [Differential expression analysis with DESeq2](hwg_workflows/differential-expression-deseq2-analysis.ga)

**Variant Analysis**

+ [Short Variant Analysis with FreeBayes and SnpEff](hwg_workflows/variant-analysis-freebayes-snpeff.ga)
