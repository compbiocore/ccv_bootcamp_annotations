FROM ghcr.io/compbiocore/ccv_bootcamp_annotations:jun_10_04-43-11_2024

RUN apt-get update && \
	apt-get -y --no-install-recommends install --fix-missing \
        libmkl-rt \
        libglpk40 \
	&& apt-get clean && rm -rf /var/lib/apt/lists/*

RUN R -e "install.packages('igraph')"
