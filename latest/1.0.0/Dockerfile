FROM satijalab/seurat

#Install other R Packages
RUN R --no-echo --no-restore --no-save -e "install.packages(c('dplyr', 'ggplot2', 'stringr', 'patchwork', 'clustree', 'presto', 'cowplot', 'scGate', 'ggpubr', 'presto'))"

#Install scDblFinder
RUN R --no-echo --no-restore --no-save -e "BiocManager::install('scDblFinder')"

#Install Libra
RUN R --no-echo --no-restore --no-save -e "remotes::install_github('neurorestore/Libra')"

CMD ["R"]
