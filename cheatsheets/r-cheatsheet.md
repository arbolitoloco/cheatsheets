# R Packages


# RStudio

Command | Description
------------------------------
available.packages() | displays list of installed packages
install.packages("packagename") | installs package
install.packages(c("pack1", "pack2", "pack3")) | installs multiple packages at once
via menu: Tools -> Install Packages | pick the repository and package for installation
search() | shows all functions from loaded packages
source("http://bioconductor.org/biocLite.R"); biocLite(); biocLite(c("pack1", "pack2")) | installs package from from Bioconductor repository
