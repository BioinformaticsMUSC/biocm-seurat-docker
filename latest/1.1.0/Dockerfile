FROM bioinformaticsmusc/biocm-seurat:1.0.0

#Install other R Packages
RUN R -e "remotes::install_github('immunogenomics/presto')"

RUN git clone https://github.com/BioinformaticsMUSC/biocm-resources.git

CMD ["R"]
