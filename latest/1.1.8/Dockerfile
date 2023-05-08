FROM bioinformaticsmusc/biocm-seurat:1.1.7

#install libbz2-dev and liblzma-dev
RUN apt-get install libbz2-dev liblzma-dev

#install archR
RUN R -e "remotes::install_github('GreenleafLab/ArchR', ref = 'master', repos = BiocManager::repositories())"

CMD ["R"]
