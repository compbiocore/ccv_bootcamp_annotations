FROM ghcr.io/compbiocore/ccv_bootcamp_annotations:jun_02_06-14-49_2025
RUN apt-get update && \
	apt-get -y --no-install-recommends install --fix-missing \
        r-base-dev \
	&& apt-get clean && rm -rf /var/lib/apt/lists/*
	    
RUN R -e "BiocManager::install(c('apeglm'))"
RUN R -e "BiocManager::install(c('msigdbr', 'airway', 'SummarizedExperiment', 'DESeq2', 'vsn', 'IHW', 'DiffBind', 'ChIPpeakAnno', 'ChIPseeker', 'ChIPQC', 'chromstaRData'))"
RUN R -e "install.packages('PoiClaClu')"
RUN R -e "install.packages('mvtnorm')"

