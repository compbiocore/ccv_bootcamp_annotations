FROM ghcr.io/compbiocore/ccv_bootcamp_annotations:jun_10_03-44-35_2024
RUN apt-get update && \
	apt-get -y --no-install-recommends install --fix-missing \
        libRlapack \
	&& apt-get clean && rm -rf /var/lib/apt/lists/*
