FROM ghcr.io/compbiocore/ccv_bootcamp_annotations:jun_02_06-09-38_2025
RUN R -e "BiocManager::install(c('apeglm'))"
RUN R -e "BiocManager::install(c('msigdbr', 'airway', 'SummarizedExperiment', 'DESeq2', 'vsn', 'IHW', 'DiffBind', 'ChIPpeakAnno', 'ChIPseeker', 'ChIPQC', 'chromstaRData'))"
RUN R -e "install.packages('PoiClaClu')"
