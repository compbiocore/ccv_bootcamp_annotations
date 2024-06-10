FROM ghcr.io/compbiocore/lee_rnaseq:apr_26_01-36-57_2024

RUN R -e "BiocManager::install("airway")"
RUN R -e "BiocManager::install("AnnotationHub")"
RUN R -e "BiocManager::install("enrichplot")"
RUN R -e "BiocManager::install("biomaRt")"
RUN R -e "BiocManager::install("DESeq2")"
RUN R -e "BiocManager::install("GenomicFeatures")"
RUN R -e "BiocManager::install("BSgenome")"
RUN R -e "BiocManager::install("BSgenome.Hsapiens.UCSC.hg19")"
RUN R -e "BiocManager::install("clusterProfiler")"
