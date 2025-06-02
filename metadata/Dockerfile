FROM ghcr.io/compbiocore/ccv_bootcamp_annotations:jun_02_03-22-28_2025
RUN apt-get update && \
	apt-get -y --no-install-recommends install --fix-missing \
        libopenblas-dev \
	&& apt-get clean && rm -rf /var/lib/apt/lists/*
