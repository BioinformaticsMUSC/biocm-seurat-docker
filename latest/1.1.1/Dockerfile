FROM bioinformaticsmusc/biocm-seurat:1.1.0

#Install other R Packages
RUN R -e "remotes::install_github('immunogenomics/harmony')"

#Install Libra

RUN apt-get update
RUN apt-get install -y cmake 

RUN R -e "BiocManager::install(c('limma', 'edgeR', 'DESeq2'))"

RUN R -e "remotes::install_github('neurorestore/Libra')"

CMD ["R"]
