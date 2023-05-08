FROM bioinformaticsmusc/biocm-seurat:1.1.2


#need JAGS
RUN apt-get update && apt-get install jags

#Install SCEVAN
RUN R -e "BiocManager::install('infercnv')"

CMD ["R"]
