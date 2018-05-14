# Galaxy Workflows

* **Quality Control**
    - **Use user uploaded reads files**
        + [sequence-quality-control-single-end.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/sequence-quality-control-single-end.ga)
        + [sequence-quality-control-paired-end.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/sequence-quality-control-paired-end.ga)
    
    - **Use reads downloaded from NCBI SRA**
    + [sequence-quality-control-single-end-fastq-dump.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/sequence-quality-control-single-end-fastq-dump.ga)
    + [sequence-quality-control-paired-end-fastq-dump.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/sequence-quality-control-paired-end-fastq-dump.ga)

* **Sequence Analysis**
    - **Mapping**
        + [mapping-bowtie2-single-end.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/mapping-bowtie2-single-end.ga)
        + [mapping-bowtie2-paired-end.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/mapping-bowtie2-paired-end.ga)
        + [mapping-hisat2-single-end.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/mapping-hisat2-single-end.ga)
        + [mapping-hisat2-paired-end.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/mapping-hisat2-paired-end.ga)
        
    - **Mapping (workflows below download reads from NCBI SRA)**    
        + [mapping-bowtie2-single-end-fastq-dump.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/mapping-bowtie2-single-end-fastq-dump.ga)
        + [mapping-bowtie2-paired-end-fastq-dump.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/mapping-bowtie2-paired-end-fastq-dump.ga)
        + [mapping-hisat2-single-end-fastq-dump.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/mapping-hisat2-single-end-fastq-dump.ga)
        + [mapping-hisat2-paired-end-fastq-dump.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/mapping-hisat2-paired-end-fastq-dump.ga)
        
    - **Annotation**
        + [genome-annotation-augustus-blastp.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/genome-annotation-augustus-blastp.ga)
        + [blast-protein-sequences.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/blast-protein-sequences.ga)
        + [interproscan-protein-functional-anlaysis](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/interproscan-protein-functional-analysis.ga)
    
* **Transcriptomics**
    + [transcripts-assembly-paired-end.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/transcripts-assembly-paired-end.ga)
    + [transcripts-assembly-single-end.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/transcripts-assembly-single-end.ga) 
    + differential expression analysis
        - step 1: [htseq-count-mapped-reads.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/htseq-count-mapped-reads.ga)
        - step 2: [differential-expression-deseq2-analysis.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/differential-expression-deseq2-analysis.ga)
    + [wgcna-analysis.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/wgcna-analysis.ga)

* **Variant Analysis**
    + [variant-analysis-freebayes-snpeff.ga](https://raw.githubusercontent.com/MingChen0919/galaxy-workflows/master/variant-analysis-freebayes-snpeff.ga)