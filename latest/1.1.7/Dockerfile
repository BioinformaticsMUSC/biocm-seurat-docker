FROM bioinformaticsmusc/biocm-seurat:1.1.6

#install clue, Rspectra, heatmap3, ConsensusClusterPlus
RUN R -e "install.packages('clue')"

RUN R -e "install.packages('heatmap3')"

RUN R -e "install.packages('RSpectra')"

RUN R -e "BiocManager::install('ConsensusClusterPlus')"

CMD ["R"]
