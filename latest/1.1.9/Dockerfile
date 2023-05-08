FROM bioinformaticsmusc/biocm-seurat:1.1.8

#install genomes
RUN R -e "BiocManager::install(c('BSgenome.Hsapiens.UCSC.hg38','BSgenome.Mmusculus.UCSC.mm10'))"

CMD ["R"]
